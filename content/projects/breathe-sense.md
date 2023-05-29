---
title: "BreatheSense - An Added Sense for Disabled People"
description: "A 'breathe-to-speech' assistive system for people with disabilities."
dateString: Jan 2019
draft: false
tags: ["assistive technology", "IoT", "Walabot", "Raspberry Pi", "RF"]
showToc: false
weight: 206
cover:
    image: "projects/breathe-sense/cover.jpg"
--- 
### 🔗 [Project Tutorial](https://www.hackster.io/dhairya-parikh/breathe-sense-an-added-sense-for-disabled-people-b601e3)

## Abstract
People with disabilities face lot of difficulties communicating with normal people, especially the people who can’t speak or hear, i.e. the deaf and dumb people. They simply can’t engage in casual conversations with people, as the society views them differently, due to their uniqueness.

So, I have tackled the following problem by creating the system that can convert the “human breathe”into speech, enabling the deaf and dumb people to engage into a casual conversation with normal people without any difficulties. With this project, I have explained the components used for the system, and how the system actually works using diagrams and graphical representation of data.

## Introduction

**BreatheSense** is a *‘Breathe-to-Speech’ assistive device* which converts an individuals breathing data into speech. This system works on a sensor called *‘Walabot’*, which is manufactured by Vayyar Imaging Ltd. This is a 3D imaging sensor, which is embedded with 15 high accuracy Radio Frequency antennas. Its primary function is in-wall imaging, but due to these RF antennas, it can even detect the slightest of movements, like thumping of the human heart, or the movement of diaphragm. So, this enables it to perform the functions of **Heartbeat Sensing** and **Breathe Sensing**. I have used the Walabot Creator for my system, hence all the explanation will be with respect to the Walabot creator model.

![](/projects/breathe-sense/walabot.jpg)

## Aim of this Project

The final aim of this project is to recognizze certain breathing patterns and convert them into speech. This will be done by measuring the breathing patterns using the Walabot sensor, which gives a numric value for each breathe. These readings are then plotted, analysed by a python program written by me, which converts them into text messages, and sends it to the android app, which speaks it out loud (speech).

The entire project flow is shown below:

![](/projects/breathe-sense/schematic.jpg)

For detailed explanation and a step by step tutorial, just go to the **Hackster** article for this project. The link for the same is given on the top.

## Project Code
The entire project code is available in its GitHub Repository.

### 🔗 [GitHub Repository](https://github.com/Dhairya1007/BreatheSense)
