# Implemented Modbus Templates

## Batteries
Template                  | Supports Energy Manager                         | Supports Energy Distribution    | Tested with real device | Source
------------------------- | ----------------------------------------------- | ------------------------------- | ----------------------- | -----------
Kostal Plenticore Plus    | yes                                             | yes                             | no                      | Initial Set
SolarEdge Home Batterie   | yes                                             | yes                             | no                      | Initial Set
SMA Sunny Boy Storage 3.7 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SMA Sunny Boy Storage 5.0 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SMA Sunny Boy Storage 6.0 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SAX Power Home (Plus)     | no (do not understand template)                 | no (do not understand template) | no                      | https://community.symcon.de/t/modbus-vorlage-sax-power-home-plus/137646

## Thermal Loads
Template                      | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
----------------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
Weishaupt Aeroblock (WAB)     | yes                     | no (no consumption variable) | no                      | Initial Set
Weishaupt Biblock (WBB)       | yes                     | no (no consumption variable) | no                      | Initial Set
Weishaupt Splitblock (WSB)    | yes                     | no (no consumption variable) | no                      | Initial Set
Weishaupt Geoblock (WGB)      | yes                     | no (no consumption variable) | no                      | Initial Set
Mitsubishi Melcobems Mini A1M | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-mitsubishi-waermepumpe-melcobems-mini-a1m/135028
Buderus WPM100                | no (no status variable) | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-buderus-wpm100/135274
Wallbe Eco 2.0                | yes                     | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-wallbox-wallbe-eco-2-0/135458
Finder 7M24                   | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-finder-zaehler-7m24-7m38/136305
Finder 7M38                   | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-finder-zaehler-7m24-7m38/136305

## eHZ
Template              | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
--------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
Janitza UMG           | yes                     | yes                          | no                      | Initial Set
Phoenix EEM-EM        | yes                     | yes                          | no                      | Initial Set
SolarEdge Smart Meter | yes                     | yes                          | no                      | Initial Set

## Inverters
Template           | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
------------------ | ----------------------- | ---------------------------- | ----------------------- | -----------
SolarEdge SE 12,5K | no                      | yes                          | no                      | Initial Set
SolarEdge SE 25K   | no                      | yes                          | no                      | Initial Set
Solar-Log Base     | no                      | yes                          | no                      | Initial Set
Solar-Log 200      | no                      | yes                          | no                      | Initial Set
Solar-Log 250      | no                      | yes                          | no                      | Initial Set
Solar-Log 300      | no                      | yes                          | no                      | Initial Set
Solar-Log 500      | no                      | yes                          | no                      | Initial Set
Solar-Log 1000     | no                      | yes                          | no                      | Initial Set
Solar-Log 1900     | no                      | yes                          | no                      | Initial Set
Solar-Log 2000     | no                      | yes                          | no                      | Initial Set
OpenFEMS           | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-openfems-fenecon-heckert-speichersystem/135948
Fronius Primo      | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-fronius-primo-symo-xx-nicht-gen24/135831
Fronius Symo       | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-fronius-primo-symo-xx-nicht-gen24/135831
Growatt TL3-X      | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-growatt/135534
Growatt SPH BH-UP  | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-growatt/135534/6

## Meters
Template               | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
---------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
Eastron SDM72D-M       | yes                     | yes                          | no                      | Initial Set
Eastron SDM120-M       | yes                     | yes                          | no                      | https://community.symcon.de/t/sdm120m-vorlage-v1/135768/1
ABB A41 112-100        | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-abb-a41-112-100/135660
Schneider iEM3155      | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-schneider-electric-iem3155/135732/2
Siemens 7KT1666        | yes                     | yes                          | no                      | https://community.symcon.de/t/siemens-7kt1666-vorlage/135766
Fronius 5kA-3          | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-fronius-smartmeter/135832/6
Carlos Gavazzi EM24 E1 | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-carlo-gavazzi-em24-e1/137191

## Wallboxes
Template                          | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
--------------------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
ABL eMH4                          | yes                     | yes                          | no                      | Initial Set
Alfen Eve Single S-line           | yes                     | yes                          | no                      | Initial Set
Alfen Eve Single Pro-line         | yes                     | yes                          | no                      | Initial Set
Alfen Eve Double Pro-line         | yes                     | yes                          | no                      | Initial Set
Alfen Eve Twin 4/5XL              | yes                     | yes                          | no                      | Initial Set
Alfen Smart Charging Network      | yes                     | yes                          | no                      | Initial Set
Keba P 30                         | yes                     | yes                          | no                      | Initial Set
Mennekes AMEDIO Professional      | yes                     | yes                          | no                      | Initial Set
Mennekes AMTRON Charge Control 11 | yes                     | yes                          | no                      | Initial Set
Mennekes AMTRON Professional      | yes                     | yes                          | no                      | Initial Set
Schneider EVlink Wallbox G4 Smart | yes                     | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-schneider-evlink-wallbox-g4-smart/136491
ABB Terra AC                      | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-abb-terra-ac-wallbox/136993 

# Other Templates

## Batteries
Template                            | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
----------------------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
Goodwe Energy Storage               | yes                     | no                           | no                      | Initial Set
Symcon Battery Storage (Simulation) | yes                     | yes                          | no                      | Initial Set
Tesla Powerwall                     | no                      | yes                          | no                      | Initial Set
Tesla Powerwall 2                   | no                      | yes                          | no                      | Initial Set
Tesla Powerwall 3                   | no                      | yes                          | no                      | Initial Set

## Wallboxes
Template                  | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
------------------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
openWB series2            | yes                     | no                           | no                      | Initial Set
Symcon E-Car (Simulation) | yes                     | yes                          | no                      | Initial Set

## Tariffs
Template          | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
----------------- | ----------------------- | ---------------------------- | ----------------------- | -----------
Symcon Strompreis | yes                     | no                           | no                      | Initial Set
