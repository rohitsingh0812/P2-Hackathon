# P2-Hackathon
VM password: applehorsebanana
# HTTP Suite
1. Build the HTTP Server
```
cd ~/Documents/P2-Hackathon/HTTP_Suite/MuseNanoHttpServer/
ant
```
2. Build the HTTP Client
```
cd ~/Documents/P2-Hackathon/HTTP_Suite/MAVLinkJavaGeneratorGUI/
ant
```
3. Start the HTTP Server
```
cd ~/Documents/P2-Hackathon/HTTP_Suite/MuseNanoHttpServer/
java -jar muse_http_server.jar <httpPort> <simulatorIP> <simulatorPort>
```
4. Start the HTTP Client 
```
cd ~/Documents/P2-Hackathon/HTTP_Suite/MAVLinkJavaGeneratorGUI/
java -jar mavlink_http_client.jar <httpPort>
```

# Ardupilot
```
cd ~/Documents/P2-Hackathon/ardupilot/ardupilot-solo/ArduCopter
make clean
make configure
make px4-v2
```
The PX4Firmware and PX4NuttX directories are dependencies for the ardupilot
