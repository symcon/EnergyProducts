# Implemented Modbus Templates

## Batteries
Template                  | Supports Energy Manager                         | Supports Energy Distribution    | Tested with real device | Source
------------------------- | ----------------------------------------------- | ------------------------------- | ----------------------- | -----------
Kostal Plenticore Plus    | yes                                             | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-kostal-plenticore-plus-gen-1/138404
SolarEdge Home Batterie   | yes                                             | yes                             | no                      | Initial Set
SMA Sunny Boy Storage 3.7 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SMA Sunny Boy Storage 5.0 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SMA Sunny Boy Storage 6.0 | no (passive with two separate charge/discharge) | yes                             | no                      | https://community.symcon.de/t/modbus-vorlage-sma-sunny-boy-storage-fw-4-04-03-r-country-data-set-spec-of-year-2018/137432
SAX Power Home (Plus)     | no (do not understand template)                 | no (do not understand template) | no                      | https://community.symcon.de/t/modbus-vorlage-sax-power-home-plus/137646
PACE BMS                  | no (no percentual current, also A instead of W) | no (current in Ampere)          | no                      | https://community.symcon.de/t/modbus-vorlage-pace-gobel-power-bms/135897
Huawei Sun 2000           | yes (TODO: Included Inverter)                   | yes                             | no                      | https://community.symcon.de/t/modbus-vorlagen-huawei-pv/135450

## Thermal Loads
Template                      | Supports Energy Manager              | Supports Energy Distribution | Tested with real device | Source
----------------------------- | ------------------------------------ | ---------------------------- | ----------------------- | -----------
Weishaupt Aeroblock (WAB)     | yes                                  | no (no consumption variable) | no                      | Initial Set
Weishaupt Biblock (WBB)       | yes                                  | no (no consumption variable) | no                      | Initial Set
Weishaupt Splitblock (WSB)    | yes                                  | no (no consumption variable) | no                      | Initial Set
Weishaupt Geoblock (WGB)      | yes                                  | no (no consumption variable) | no                      | Initial Set
Mitsubishi Melcobems Mini A1M | yes                                  | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-mitsubishi-waermepumpe-melcobems-mini-a1m/135028
Buderus WPM100                | no (no status variable)              | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-buderus-wpm100/135274
Wallbe Eco 2.0                | yes                                  | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-wallbox-wallbe-eco-2-0/135458
Finder 7M24                   | yes                                  | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-finder-zaehler-7m24-7m38/136305
Finder 7M38                   | yes                                  | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-finder-zaehler-7m24-7m38/136305
Lambda Heat Pump              | no (no on/off or percentual current) | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-lambda-waermepumpe/138332
Maico WS 320                  | no (no on/off or percentual current) | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-maico-kwl-320-470-und-andere/138436
Gondzik Delta 9               | yes                                  | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-gondzik-delta-waermepumpe/137385
Waterkotte EcoTouch 5029 Ai   | yes                                  | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-waterkotte-waermepumpe/138686/8
MyPV AC ELWA 2                | no (no idea what to switch)          | no (no idea what to switch)  | no                      | https://community.symcon.de/t/modbus-vorlage-mypv-ac-elwa-2/138454/4

## eHZ
Template              | Supports Energy Manager        | Supports Energy Distribution | Tested with real device | Source
--------------------- | ------------------------------ | ---------------------------- | ----------------------- | -----------
Janitza UMG           | no (need conversion to meters) | yes                          | no                      | Initial Set
Phoenix EEM-EM        | no (need conversion to meters) | yes                          | no                      | Initial Set
SolarEdge Smart Meter | no (need conversion to meters) | yes                          | no                      | Initial Set

## Inverters
Template                 | Supports Energy Manager | Supports Energy Distribution | Tested with real device | Source
------------------------ | ----------------------- | ---------------------------- | ----------------------- | -----------
SolarEdge SE 12,5K       | no                      | yes                          | no                      | Initial Set
SolarEdge SE 25K         | no                      | yes                          | no                      | Initial Set
Solar-Log Base           | no                      | yes                          | no                      | Initial Set
Solar-Log 200            | no                      | yes                          | no                      | Initial Set
Solar-Log 250            | no                      | yes                          | no                      | Initial Set
Solar-Log 300            | no                      | yes                          | no                      | Initial Set
Solar-Log 500            | no                      | yes                          | no                      | Initial Set
Solar-Log 1000           | no                      | yes                          | no                      | Initial Set
Solar-Log 1900           | no                      | yes                          | no                      | Initial Set
Solar-Log 2000           | no                      | yes                          | no                      | Initial Set
OpenFEMS                 | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-openfems-fenecon-heckert-speichersystem/135948
Fronius Primo            | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-fronius-primo-symo-xx-nicht-gen24/135831
Fronius Symo             | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-fronius-primo-symo-xx-nicht-gen24/135831
Growatt TL3-X            | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-growatt/135534
Growatt SPH BH-UP        | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-growatt/135534/6
Solax X3-PRO             | no                      | no                           | no                      | https://community.symcon.de/t/solax-x3-pro-mic-wechselrichter/138202
Solax X3-MIC             | no                      | no                           | no                      | https://community.symcon.de/t/solax-x3-pro-mic-wechselrichter/138202
SolarEdge Inverter       | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-solaredge-wechselrichter-address-40070-40107/134885, https://community.symcon.de/t/modbus-vorlage-solaredge-wr/135693
Sofar Solar HYD-5-20 KTL | no                      | no                           | no                      | https://community.symcon.de/t/sofar-solar-hyd-5-20ktl/139079
Sungrow SH10RT           | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-sungrow-wr-sh10rt/136446
Sungrow SBR128           | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-sungrow-wr-sh10rt/136446
M-TEC Hybrid             | no                      | no                           | no                      | https://community.symcon.de/t/modbus-vorlage-m-tec-hybrid-wechselrichter-energy-butler/141301

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
SolarEdge Meter 1      | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-solaredge-messgeraet-1-address-40121-40293/134888
Siemens PAC2200        | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-siemens-pac2200/138337
EMU Professional 3/75  | yes                     | yes                          | no                      | https://community.symcon.de/t/vorlage-fuer-mbs-profesional-3-75-tcp-ip/139889/6
Janitza UMG            | yes                     | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-janitza-umg/140677

## Wallboxes
Template                          | Supports Energy Manager     | Supports Energy Distribution | Tested with real device | Source
--------------------------------- | --------------------------- | ---------------------------- | ----------------------- | -----------
ABL eMH1                          | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/abl/
ABL eM4                           | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/abl/
Alfen Eve Single S-line           | yes                         | yes                          | no                      | Initial Set
Alfen Eve Single Pro-line         | yes                         | yes                          | no                      | Initial Set
Alfen Eve Double Pro-line         | yes                         | yes                          | no                      | Initial Set
Alfen Eve Twin 4/5XL              | yes                         | yes                          | no                      | Initial Set
Alfen Smart Charging Network      | yes                         | yes                          | no                      | Initial Set
Keba P 30                         | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/keba/
Keba P 40                         | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/keba/
Mennekes AMEDIO Professional      | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Mennekes AMTRON Charge Control 11 | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Mennekes AMTRON Professional      | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Mennekes AMTRON Xtra              | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Mennekes AMTRON 4You              | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Mennekes AMTRON 4Business         | yes                         | yes                          | no                      | https://www.symcon.de/de/service/dokumentation/modulreferenz/geraete/mennekes/geraeteliste/
Schneider EVlink Wallbox G4 Smart | yes                         | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-schneider-evlink-wallbox-g4-smart/136491
ABB Terra AC                      | yes                         | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-abb-terra-ac-wallbox/136993
Warp Charger                      | yes                         | yes                          | no                      | https://community.symcon.de/t/modbus-vorlage-warp-charger-wallbox/137774
go-e Charger Gemini 2.0           | yes                         | no (no consumption variable) | no                      | https://community.symcon.de/t/modbus-vorlage-go-e-v2/135688
Schrack i-CHARGE CION             | yes                         | yes                          | no                      | https://community.symcon.de/t/modbus-vorlag-schrack-cion-wallbox/140375/1
ChargeHere Zaptec Pro             | no (no switchable variable) | no (no Energy Manager)       | no                      | https://community.symcon.de/t/modbus-vorlage-chargehere-wallbox/140678

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
