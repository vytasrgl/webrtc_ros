webrtc_ros [![Build Status](https://api.travis-ci.org/RobotWebTools/webrtc_ros.png)](https://travis-ci.org/RobotWebTools/webrtc_ros)
================

#### Streaming of ROS Image Topics using WebRTC
This node provides a WebRTC peer that can be configured to stream a ROS image topic and recieve a stream that is published to a ROS image topic.
The node hosts a webserver that serves a simple test page and offers a websocket server that can be used to create and configure a WebRTC peer.

For full documentation, see [the ROS wiki](http://ros.org/wiki/webrtc_ros).

[Doxygen](http://docs.ros.org/indigo/api/webrtc_ros/html/) files can be found on the ROS wiki.

This project is released as part of the [Robot Web Tools](http://robotwebtools.org/) effort.

### License
webrtc_ros is released with a BSD license. For full terms and conditions, see the [LICENSE](LICENSE) file.

### Authors
See the [AUTHORS](AUTHORS.md) file for a full list of contributors.

### Required packages to be installed 

With HR stack already installed. Might need aditional packages on bare ROS.

```
sudo apt-get install default-jdk
sudo apt-get install libdbus-glib-1-dev 
sudo apt-get install libnss3-dev
sudo apt-get install libudev-dev
sudo apt-get install libpulse-dev
sudo apt-get install libasound2-dev
sudo apt-get install ros-indigo-async-web-server-cpp
```
