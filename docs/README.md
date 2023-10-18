# Installation instructions
1. Install pypot:
```
pip install pypot
pip install pypot --upgrade --no-deps
```
2. Install poppy robot:
```
pip install poppy-ergo-jr
pip install poppy-ergo-jr --upgrade --no-deps
```
3. Upgrade numpy:
```
pip install --upgrade numpy
```

# Violin instructions

1. Position the robot & chair where desired, attach the 3d printed head, making sure the notch in the attachment is aligned
2. Attach the violin the to left arm. The green hand sits between pegs 2 and 3. The spike sits in the recess with the most marks from the spike
3. Switch on PC – password is robotorchestra
4. Attach the white USB extension cable to the laptop
5. Attach the USB hub to the extension cable
6. Attach the two USB devices to the hub in the following order:
7. Attach the power leads to the two 
   1. Device attached to small green PCB with large capacitor
   2. Device attached to large stripboard
8.  Click on file manager (the small white icon to the left of the world (browser) symbol at the bottom left of the screen)
9.  The window will open at /home/alastair. Navigate to /home/alastair/opt/packages/pycharm/pycharm-community-2016.1.4/bin
10. Double click on pycharm.sh. Choose the 'execute' option. The program will open with the file robot_test_json.py open in the main editor pane. A terminal will open in the pane at the bottom of the screen.
11. To run a program, click into the terminal pane, and press the 'up' key on the keyboard until the desired program is displayed in the command prompt. The three programs are listed below:
    1. Python robot_test_json.py - makes the robot move it's arm back and forth in an infinite loop
    2. Python robot_retract.py – moves the robot to it's open armed position
    3. Python robot_point.py – moves the robot to it's closed armed position
12. Run robot_retract.py
13. When the robot has finished moving, attach the bow to the green hand of the right arm. Tighten the bolts holding it in place.
14. The robot is now ready!