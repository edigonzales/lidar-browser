# LiDAR-Browser

Potree based browser application for lidar data of canton Solothurn. It's just a nginx docker image with burned in Potree. The lidar data can be found here: https://geo.so.ch/geodata/

Build:
```
./gradlew versionTxt buildDockerImage
```

Run:
```
docker run -p 8083:8080 sogis/lidar-browser
```
