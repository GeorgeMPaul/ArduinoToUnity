# ArduinoToUnity Via MQTT
To send sensor data from Arduino to Unity. 

Overview:
The arduino randomly switches on and off its builtin LED pin. This is sensor data is sent to Unity via MQTT. The topic name is "led/sensor".

Hardware:
Arduino Uno R4 Wifi

Requirements:
Install libraries - WifiS3 and PubSubClient

The TestMqtt.ino file publishes the sensor data to the topic.
Unity recieves the data via this documentation - https://www.emqx.com/en/blog/using-mqtt-in-unity-with-m2mqttunity-library-a-step-by-step-guide
