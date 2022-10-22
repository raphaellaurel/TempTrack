# TempTrack (A Temperature/Moisture/Light Sensor relay system) 

#SensorRelay 
- SensorRelay is run for downstream communication 

#TeensyConnect 
- TeensyConnect is used to establish commincation between edge tier and sensor tier aspects of the IoT network 
- Commands are written to Serial1 throught the '/dev/rfcomm0' Bluetooth port 

#TempTracking 
- TempTracking reads the data gathered from the sensing tier and sends it to AWS via IP address "3.25.99.2" (Upstream communication)

