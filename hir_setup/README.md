# setup

## installing ros indigo

## installing gazebo 7
Before you install gazebo 7 make sure to build your workspace with gazebo 2. This way you can avoid conflict error.
```
sudo apt-get remove gazebo2
./install_gazebo7
sudo apt-get install ros-indigo-gazebo7-ros-pkgs
sudo apt-get install ros-indigo-gazebo7-ros-control
```
## installing keras
```
sudo apt-get update
sudo apt-get install libcupti-dev
pip install tensorflow-gpu (if cpu, tensorflow)
pip install numpy scipy
pip install scikit-learn
pip install pillow h5py
pip install keras
```
