---
layout: post
title: "Configure"
comments: true
lang: en
date: 2020-11-23
description: "Configure Intro"
tag: Configure
---


### Overview

Configure is the auxiliary software for LiteSilver flight control. It sets flight control parameters and updates firmware through graphical interface.

It's still a work in progress.



### Introduce

#### 1、Connect flight control

- FC Status displays the basic information of the current flight control, including the name of the flight control, version, compile time, etc
- <img src="https://i.loli.net/2020/11/19/ZT3gMpavE9XCmWY.png" alt="image-20201119182947100" style="zoom:67%;" />



#### 2、Update firmware

- Select the corresponding option for brush and brushless FCS
- <img src="https://i.loli.net/2020/11/19/HjdIFvNu8JnyQpq.png" alt="image-20201119183209728" style="zoom:67%;" />



#### 3、Set Rates

- After connecting the flight control, select Enable Expert Mode in the Setup page and enter Rates Settings
- <img src="https://i.loli.net/2020/11/19/b8tEM1QSBwNn4rA.png" alt="image-20201119183551660" style="zoom:67%;" />

### Download

- [v0.1](https://github.com/BETAFPV/BETAFPV.github.io/releases/tag/0.1)



### Other

- How to update firmware
  - Press and hold the button at the bottom of the flight control, and then plug in the USB. At this time, only the power led is on (red led).
  - Switch to config's Flasher page, click Local, and load the firmware via the Open File button.
  - In the Communication Area, select the serial port number corresponding to the flight control and connect.
  - Check Warn Checkbox, then click the Download button and wait for the downloading.
  - When the progress bar is complete, disconnect the USB and the update is complete.
  - Note: You do not need to connect flight control on the setup page to update the firmware.
  - Note: It is necessary to rebind after firmware update.
  - Note: Updating the firmware does not erase the bootloader, so don't worry if the update fails, try a few more times.
  - <img src="https://i.loli.net/2020/12/30/QXnVR1gDZejwypE.png" alt="image-20201230100022190" style="zoom:80%;" />

