# Mini Robotics

The goal of this project is to run an extremely low cost, extremely low skill robotics competition. If you are a teacher, a parent, or simply someone who wants to get into robotics, this platform is for you.

The priorities (in rough order) are:
 - low skill floor: someone with no programming knowledge should be able to create and control a basic 2-wheeled robot using this platform.
 - easy entry: this platform is entirely browser-based. No software installs required.
 - low cost: under $20 per robot
 - upgradable: Someone can start with a basic 2-wheeled, Python-controlled robot, and slowly upgrade it with more features and more sophisticated code. This is pretty important for a learning platform. If you have build a robot using this platform, and want to translate your skills into the "real world", check out what's next? upgrades and beyond [TODO].

For these reasons, the project is based around the Raspberry Pi Pico 2W. It is extremely low cost, has Bluetooth capabilities, can embed MicroPython, and is powerful enough to be used for "real" projects. There are other good alternatives:
 - the original Raspberry Pi Pico W: even cheaper, but less powerful.
 - ESP32 devices: also a great fit
 - Raspberry Pi 3/4/5: more powerful, but not cheap.

I haven't written software for any of the alternatives, but if you want to contribute, I would welcome ports to any of these.

# Quickstart: Blink

This is not quite a robot, but will get you started running Python code on the microcontroller.

Materials needed:
 - chromebook, laptop, or computer with a USB port
 - USB to micro USB cable
 - Raspberry Pi Pico 2W

Instructions:
 - Hold down the button on the 2W. While holding the button, use the cable to plug the Pico 2W into your computer. It should pop up as a USB drive.
 - Download the runtime file from releases [TODO]. Then, drag the runtime file into the USB drive. The USB drive should disappear, and the LED on the Pico 2W should start blinking slowly (period of 4 seconds). 
 - Go to the programming interface website [TODO].
 - Click "connect over bluetooth".
 - Click examples, then choose the "blink" example.
 - Click "upload". The LED on the Pico 2W should start blinking quickly (period of 1 second). In the debug console, you should also see "turned on" and "turned off" messages. Congratulations, you are running Python code on the microcontroller!

# Mediumstart: 2 Wheeled Robot

Materials needed:
 - materials from quickstart
 - 2 motors
 - motor H-bridge driver board
 - 9 volt battery
 - breadboard
 - wires
 - cardboard
 - tape

Instructions:
 - Follow the quickstart: blink instructions if you haven't already.
 - Unplug the Pico 2W from your computer.
 - Follow building your first robot [TODO] to construct a 2-wheeled robot.
 - Plug in the 9V battery.
 - Go to the programming interface website, and connect to your robot over bluetooth.
 - Choose the "2 wheeled robot" example, and upload it to the robot.
 - Click on the "control" panel in the web interface.
 - Control your robot with WASD.

# Longstart: Multi-robot competition

If you want to run a competition between N robots, you just need to have the N participants follow the instructions above. This platform also allows the robots to connect to a central server, which is useful for running a robotics competition. 

Materials needed:
 - N times materials from 2 wheeled robot
 - a laptop or computer that you can install Python and VSCode on

Instructions:
 - 




