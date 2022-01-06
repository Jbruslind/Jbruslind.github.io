---
layout: page
title: Mechanical
---

## Overview 

The Mechanical system was designed with modularity and easy assembly in mind. In the future, the system may be deployed in differing areas and require an increase or decrease in dimensions. The mechanical system must be designed to accommodate changes in dimensions to fit the users needs. In addition, the system will be used by users with little to no prior knowledge of how it was designed or any institutional knowledge of how it was originally assembled. The overall system was broken up into simple sub-assemblies to streamline the manufacturing and assembly process. 

![Full System](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Mechanical_assets/FullSystem.png "Full System")

## X Carriage Subassembly

![Carriage Subassembly](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Mechanical_assets/Carriage_Assembly.png "Carriage Subassembly")

The X Carriage Subassembly is the main motion platform for the HyperRail system. The assembly should allow for smooth motion along the lower 4060 T-slot track while also allowing the motor mechanism to interface to the belt track. 

The carriage assembly borrows ideas from the [Bell-Everman](https://www.bell-everman.com/products/linear-positioning/servobelt-linear-sbl)[^1] servo setup in which a static belt is used on the tracks and interfaces to a dynamic belt driven by a motor / pulley. A rack and pinion system would also work the same way (with more durability) however the realative costs were prohibitive for a system on this scale. For reference, the average cost per meter for the rack on a rack and pinion is ~$70/m whereas for this style, the belts are only ~$15/m. The projected user needs are for the system to extend up to 90ft or 30m making the rack and pinion very expensive. 

![Bell-Everman Servo](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Mechanical_assets/BellEverMan.jpg "Bell Everman Servo")

One of the big advantages to this style of mechanism is the ability to easily extend the track length to various sizes without needing to purchase specially made belts/tracks. This allows the overall system to maintain "modularity" with the x-direction, which is aimed to be the longer of the axes (x length >> y, z). If the user wants to add more length, they can easily attach another section of track (4060 with static belt attachment) to the original axis and align the track pieces together so the dynamic belt is able to mesh smoothly (see the Add-On module section). 

## X Rail Assembly

![X Rail](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Mechanical_assets/Side_Rail_Assembly.png)

The X Rail Assembly utilizes the carriage shown above and implements it onto a track along with a vertical 4040 T-slot beam. The assembly cantilevers the weight of the upper track length (mounted to the vertical beam) with the motor + planetary gearbox assembly so that the mass is relatively distributed along the base. The assembly is supported by a foot assembly which can be distributed and adjusted as needed based on the environment.

![X Rail Movement](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Mechanical_assets/MotorAdjust_Movement.gif)

## Top Frame Subassembly

## Y Carriage Subassembly

## Ebox Subassembly

## Main System

## References
[^1]: Bell-Everman, Inc. (2016, October 19). New ServoBelt™ LoopTrack Linear Stage. Retrieved from https://www.bell-everman.com/products/linear-positioning/servobelt-linear-sbl