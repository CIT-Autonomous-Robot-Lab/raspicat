[![ros-noetic-ci](https://github.com/CIT-Autonomous-Robot-Lab/raspicat/actions/workflows/build_push.yaml/badge.svg)](https://github.com/CIT-Autonomous-Robot-Lab/raspicat/actions/workflows/build_push.yaml)
# raspicat

# インストール方法
```
mkdir ~/raspicat_ws/src -p && cd ~/raspicat_ws/
curl -sL "https://raw.githubusercontent.com/CIT-Autonomous-Robot-Lab/raspicat/master/raspicat_navigation.repos" -o /tmp/raspicat_navigation.repos
vcs import ~/raspicat_ws/src < /tmp/raspicat_navigation.repos --debug --recursive
catkin b
source ~/raspicat_ws/devel/setup.bash
```