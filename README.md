# Product Configuration
## index.json

| key     | value                                                                                                               |
|---------|---------------------------------------------------------------------------------------------------------------------| 
| vendor  | The vendors name                                                                                                    |
| ident   | the ident of the vendor. Must be a valid directory/filename and the name of the directory the index.json file is in |
| devices | list of the vendors devices                                                                                         |

### Device
| key                    | value                                                                                                               |
|------------------------|---------------------------------------------------------------------------------------------------------------------|
| vendor                 | The vendors name                                                                                                    |
| ident                  | the ident of the vendor. Must be a valid directory/filename                                                         |
| guid                   | the guid of the module the device instance is created from                                                          |
| configurationType      | how the device is set up. See [configurationType](#configurationtype)                                               |
| moduleConfiguration    | guid -> object with property names as keys and property values as values                                            |
| instanceConfiguration  | property names as keys and property values as values. Only used by the default configurationType                    |

#### configurationType
| value      | description                                                                                                                                             |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| modbus-tcp | A Modbus Gateway and a Client Socket are created for the device instance. The user is asked for the host and port and the `template` is imported          |
| default       | The device instance is created without any data flow, so no host and port are asked for. The instance is set up by `instanceConfiguration` instead of a `template` |

#### instanceConfiguration
Only used by the `default` configurationType. The properties of the created device instance are set directly from this object before the changes are applied.
```
{
    "instanceConfiguration": {
        "SomeProperty": 5,
        "AnotherProperty": "value"
    }
}
```

#### moduleConfiguration
##### Lists
If the value of a property is a List/Object the property will be treated as a JSON encoded list. and the contents defined will be added to that list.

##### ~
If a value of a property starts with a ~ it will be replaced with the value for that key found in the 'configuration' field provided by the visualization. A list of all available parameters:
- ~Name
- ~Phases
- ~MaxChargingCurrent

##### Variables
If the value should be a variable ID, a parameter value prefixed with * will be treated as an ident and replaced with the matching variable ID of the selected or newly created device.

##### Properties
If the value comes from a property, a parameter value prefixed with § will be treated as a property name and will be replaced of the value of that property.

#### logging
The key is the ident of a variable below the created device instance. The value is the aggregation Type.
{
    "logging": {
        "defaultIdent": 0,
        "counterIdent: 1,
    }
}

#### parent
If this parameters is a number the parent will be set to this number as id. If the value is a string the parent will be the object that has the given ident below the main category

parameter value prefixed with * will be treated as an ident and replaced with the matching variable value