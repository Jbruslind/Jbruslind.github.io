---
layout: page
title: Electrical
---

## Overview 

## Motor Nodes

![Motor Node](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Electrical_assets/IntegratedStepDriver.png)

## ESP-32 Controller

The ESP-32 Controller was designed to be the liaison between motion requests by the ROS software and the rest of the machine. The board itself is computationally powered with an ESP32-WROOM module (either through a daughter dev-board or embedded on the board) running the [GRBL_esp32](https://github.com/bdring/Grbl_Esp32) firmware. A key aspect of using the GRBL style firmware over other flavors (such as Marlin or otherwise) is that GRBL supports the ESP32 with no perquisites and can support a Web-UI natively for manual control. 

![GRBL Controller](https://raw.githubusercontent.com/Jbruslind/Jbruslind.github.io/main/assets/Electrical_assets/ESP32GRBLController.png)



## Magnetic End Stops

## Main System

