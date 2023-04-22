# Toucan Crossing Simulation Coursework
This is a Python script that simulates a Toucan crossing using LEDs controlled by a BlinkStick. The Toucan crossing is a type of pedestrian crossing that allows both pedestrians and cyclists to cross a road at the same time.

# Prerequisites
Python 3.x
The blinkstick Python module (can be installed via pip)
# Usage
Connect a BlinkStick to your computer.
Run the toucan_crossing.py script with Python.
The script will loop indefinitely, simulating the Toucan crossing by cycling through a predetermined sequence of LED colors.

# Code Structure
The script consists of three functions:

**set_traffic_lights(bstick, road, setting)**: sets the LED colors for a set of traffic lights based on a given sequence of light settings.

**set_crossing_light(bstick, setting)**: sets the LED colors for the Toucan crossing lights based on a given sequence of light settings.

**main()**: the main loop of the script, which cycles through the predetermined sequence of LED colors for the traffic lights and Toucan crossing lights.

The script also includes several constant variables that define the LED index numbers, colors, and the sequence of LED colors for the traffic lights and Toucan crossing lights.

# License
This code is released under the MIT License. See LICENSE for more information.
