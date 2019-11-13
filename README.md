# LIDAR- [LIDAR](#lidar)
  - [Missions](#missions)
  - [Usage](#usage)
  - [Relevant links](#relevant-links)


## Missions
- [ ] Create record Rosbags script
- [ ] Record Data
  
## Usage
### Getting started with the Velodyne VLP16
See [ROS tutorial](http://wiki.ros.org/velodyne/Tutorials/Getting%20Started%20with%20the%20Velodyne%20VLP16)

### Recording and playing back data
#### Recording data (creating a bag file)
```
rosbag record -O <Bag name> <Topic1 Name> <Topic2 Name> ...
```
#### Examining and playing the bag file
```
rosbag info <your bagfile>
or
rosbag play <your bagfile>
```
## Relevant links