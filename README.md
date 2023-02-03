# voelund-modbus-ha
Vølund smo s40 modbus configuration for home assistant - use at own risk!


This is the configuration i'm using for home assistant to communicate with vølund smo s40 control unit (Heat pumpt)

It doesn't include all registres, for a complete list of the registres please take a look at: 
[SMO S40 modbus](https://www.nibe.eu/download/18.3db69dc1795e0d992c5722/1622634529178/Modbus%20S-series%20EN%20M12676EN-1.pdf)


To include it in you configuration simply download the varmepumpe.yaml file, place it next to your configuration.yaml. And add the following in configuration.yaml:


```
modbus: !include varmepumpe.yaml
```
After this, remember to edit the ip address of your heatpump in the varmepumpe.yaml file.


All names in the varmepumpe.yaml are in danish some day i might edit them to english.
