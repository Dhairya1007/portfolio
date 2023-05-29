---
title: "LoRAWAN based Air Quality Monitoring System"
description: "IoT meets LoRA!"
dateString: Dec 2019 - Jun 2020
draft: false
tags: ["IoT", "LoRa", "Arduino IDE", "Analytics", "Sensor", "Air Quality"]
showToc: false
weight: 204
cover:
    image: "projects/lora-air-quality-system/cover.jpg"
--- 
## Description

This project presents a real-time and long-range air pollution monitoring system for indoor and outdoor environments. The system implemented a wireless sensor network using LoraWAN technology for data communication between all nodes and sensors. The system consists of two nodes distributed within a distance one kilometer to gateway for measuring the concentration of **VOCs (Volatile Organic Compounds)**, **Carbon Dioxide (CO2)** and **PM2.5 (Particulate Matter 2.5um)** readings. Experimental results show the system is reliable in both indoor and outdoor applications. 

The distance coverage achieved up to *900 meters* and can be displayed through a web-based client (Thingspeak) and also from an Android or iOS application. The experiment with LoraWAN transmission has shown that the LoraWAN technology is very suitable for the air pollution system especially in long range transmission compared to other wireless transmission techniques and the power consumption of the system is also considerably lower than the existing systems and also some actuation techniques would be discussed and demonstrated.

Here is a schematic diagram of how the nodes and the LoRa Gateway operate.

![](/projects/lora-air-quality-system/schematic.jpg)

I have written a complete tutorial for this project on **hackster.io**. Additionally, all the code covered in this tutorial can be found in the project's GitHub Repository. Links to both these resouces can be found below:

### 🔗 [Complete Project Tutorial](https://www.hackster.io/358708/lora-powered-air-quality-monitoring-system-e96aa9)

### 🔗 [GitHub Repository](https://github.com/Dhairya1007/Lora-Powered-Air-Quality-Monitoring-System)