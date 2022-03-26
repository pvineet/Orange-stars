# Roomba for Mirrors and Windows
I am sure all of us have seen the marks formed by water on bathroom mirrors, shower glasses and windows. The marks are even more conspicuous if the water being used has higher total dissolved solids. Why not think of a device to clean the above mentioned glass surfaces.
## Keeping it simple and stupid.
I want to keep the first idea super simple and stupid. Drawing inspiration from the way glass exterior of high rise buildings are cleaned. The initial idea is to have a gantry robot which moves along the mirror while cleaning it. Mechanical and materials improvements like robot with suction wheels which can move like a spider can be thought of later.
<p align="center">
  <img src="https://raw.githubusercontent.com/pvineet/Orange-stars/9b0ad5d8d81018b8c1ed6d03a14c3b9ba3859ed0/HW1/MirrorRoomba.svg">
</p>

## Basic cleaning workflow
- Find the limits or edges of the mirror or window.
- Clean the glass with top down swipes from left to right.

## Block Diagram
<p align="center">
  <img src="https://raw.githubusercontent.com/pvineet/Orange-stars/f852535f52e59f6191e94962e0f8c450743ba59f/HW1/BlockDiagram.svg">
</p>

## Components

Processor controls mirror roomba
Flash Code and logging storage
Motor driver controlled via PWM and drives different motors
Water sensor monitors water level
Soap/water dispensor dispenses soap to clean
Edge sensor senses the edges of mirror or window.
