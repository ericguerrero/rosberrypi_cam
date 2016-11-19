# rosberrypi_cam

ROS driver for RaspberryPi camera module

## Dependencies

### Raspicam:

```
$ cd ~/catkin_ws
$ mkdir external_src
$ cd external_src
$ wget http://sourceforge.net/projects/raspicam/files/raspicam-0.1.3.zip/download
$ mv download raspicam-0.1.3.zip
$ unzip raspicam-0.1.3.zip
$ cd raspicam-0.1.3
$ mkdir build
$ cd build
$ cmake ..
```

## Usage

Run roscore locally on the Pi or remotely (set the ROS_MASTER_URI accordingly).
Run the rosberrypi_cam_node

```
$ rosrun rosberrypi_cam rosberrypi_cam_node
```


