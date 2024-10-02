This file shows the steps to install the ROS 2 Galactic

My setup: 
OS: Ubuntu 20.04
Laptop: Omen 16


Step 1: Set locale

locale  # check for UTF-8 

sudo apt update && sudo apt install locales
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8

locale  # verify settings

Step 2: Ensure that the Ubuntu Universe repository is enabled.

$ sudo apt install software-properties-common

$ sudo add-apt-repository universe

Step


Follow the steps given in the link to install it

https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html


