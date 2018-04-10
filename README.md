# hokuyo_neato_navigation

# Sbpl Lattice Planner

## Installation instructions

```
mkdir -p neato_sbpl_ws/src
cd neato_sbpl_ws/src
git clone https://github.com/wmlynar/hokuyo_neato_navigation.git
git clone https://github.com/MASKOR/maskor_navigation.git
cd ..
rosdep install --from-paths src --ignore-src --rosdistro=kinetic -y
catkin_make
source devel/setup.bash
```

## Running the demo

```
roslaunch neato_navigation woj_sbpl.launch
```
