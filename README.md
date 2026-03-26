# DIT Zenoh Bridge
This project provides a Docker-based solution to establish a communication bridge between DDS in ROS2 using ```zenoh bridge```.

## Quick Start
### Start the container
```bash
cd DIT-ZenohBridge/docker
docker compose up -d
```

### Build the image
If you have modified the ```Dockerfile``` or the installation scripts, you need to rebuild the image.
```bash
cd DIT-ZenohBridge/docker
docker compose build
docker compose up -d
```

## Reference
- [ros2 humble cyclonedds](https://docs.ros.org/en/humble/Installation/RMW-Implementations/DDS-Implementations/Working-with-Eclipse-CycloneDDS.html)
- [zenoh-bridge github repository](https://github.com/eclipse-zenoh/zenoh-plugin-ros2dds)