
Stage 1 — Ignite Challenge
Challenge 1 - Board Bring-Up (“Wake the board”)
1.	Enter your preferred disk to format. Please not that the storage of SD card should be greater than 8 GB
2.	Flashing the device
a.	Run RDK Studio as administrator.
b.	Select Flasher
c.	Choose device “RDK X5”
d.	Choose image
e.	Flash disk
f.	Confirm finalization

3.	Network connectivity
a.	Connect the board to wifi
b.	ping -c 4 google.com to verify its connectivity

4.	SSG login
a.	Find the username and IP address via RDK terminal hostname -I
b.	Open windows PowerShell and ssh root@192.168.128.10
c.	Enter root as the password

Challenge 2 - Sensor Explorer
Preferred sensor: Camera 
1. Upgrade the system using these commands
1.	SSH login to the system via windows power shell and enter these commands.
a.	sudo apt update 
b.	sudo apt-get upgrade
2.	Restart the device
a.	Sudo reboot
2.Login from RDK studio 
a.	Open RDK studio
b.	Connect to the device
3.Programming sensors – camera 
a.	Select code editor and install code-sever editor
b.	Open code-editor or VS Studio
c.	Install suitable configurations
d.	There was a problem with MIPI camera interface, I decided to work with USB camera.
e.	Create a python file and create a camera.py
f.	pip3 install opencv-python
g.	Copy and paste following code to camera.py

Challenge 3 - First AI Task
1.	Download the model library from github
a.	https://github.com/D-Robotics/rdk_model_zoo
2.	Downlaod the model yolov5 model from github
a.	Navigate to cd ~/rdk_model_zoo/samples/vision/yolov5/model
b.	wget https://archive.d-robotics.cc/downloads/rdk_model_zoo/rdk_x5/yolov5s_tag_v2.0_detect_640x640_bayese_nv12.bin
c.	Navigate to  cd ~/rdk_model_zoo/samples/vision/yolov5/runtime/python
d.	Python3 main.py to run the file
e.	Result image shown below





