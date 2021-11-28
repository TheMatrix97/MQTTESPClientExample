
# MQTT Telemetry Example ESP8266

This example shows how to send temperature and humidity telemetry using a NodeMCU(ESP8266) and DHT11 sensor

## Compile

Use visual studio with platformIO for compilation

### Wifi configuration

Add your wifi information in file `variablesWIFI.c`, following the provided template

````c
char* SSID = "ExampleWLAN";
char* PASSWORD = "ExampleWLANPassword";
char* MQTTBROKER = "ExamplePrivateIPMQTTServer";
````