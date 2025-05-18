---
title: ECE196 SP25 DHT11 Tutorial
date: 2025-05-17
authors:
  - name: Mark Sui
---

![relevant graphic or workshop logo](image/path)

## Introduction
In this tutorial, we will learn how to use a DHT11 sensor with an ESP32 board. We will connect the sensor, read the temperature and humidity, and show the readings on the computer screen. That this can help us to track the indoor environment. By the end, we will know how to add simple sensors to our own projects and knows how the Inter-Integrated Circuit(I2C) works.
### Learning Objectives

* Learn what a DHT11 sensor does
* Learn how to hook up the DHT11 to an ESP32 board
* Install Arduino IDE and add ESP32 support
* Use the DHT library to read sensor data
* Write and run code to print readings to the screen
* Learn what is Inter-Integrated Circuit(I2C)

### Background Information

This tutorial is about the DHT11 sensor and how to use it with the ESP32 board. The DHT11 is a small and cheap sensor that can measure temperature and humidity. It sends this data to the ESP32, which then shows it on the computer screen through the Serial Monitor.

We use the DHT11 because it’s easy to find, low-cost, and simple to use for beginners. There are other sensors like the DHT22 or BME280 that can do the same thing but with better accuracy or extra features. However, the DHT11 is good enough for basic projects.

The DHT11 works by using a special chip inside to measure temperature and humidity from the air. It sends this data as a digital signal to the ESP32 through a single data wire.

- Digital Signal: The DHT11 sends data using 0s and 1s, so the ESP32 can read it.

- Humidity: How much water vapor is in the air.

- Temperature: How hot or cold the air is.

This sensor is useful in weather stations, smart homes, and school projects. It’s a great way to learn how to use sensors with microcontrollers.

## Getting Started

For any software prerequisites, write a simple excerpt on each
technology the participant will be expecting to download and install.
Aim to demystify the technologies being used and explain any design
decisions that were taken. Walk through the installation processes
in detail. Be aware of any operating system differences.
For hardware prerequisites, list all the necessary components that
the participant will receive. A table showing component names and
quantities should suffice. Link any reference sheets or guides that
the participant may need.
The following are stylistic examples of possible prerequisites,
customize these for each workshop.

* **Arduino IDE** installed on your computer
* **ESP32 board files** added to the Arduino IDE
* **DHT library** installed in Arduino IDE

1. Go to [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software) and install the Arduino IDE.
2. Open Arduino IDE, go to *File > Preferences*, and add this URL under *Additional Boards Manager URLs*: `https://dl.espressif.com/dl/package_esp32_index.json`
3. Go to *Tools > Board > Boards Manager*, search for "ESP32" and install "esp32 by Espressif Systems."
4. Go to *Sketch > Include Library > Manage Libraries*, search for "DHT sensor library" by Adafruit and install it.


### Required Downloads and Installations

List any required downloads and installations here.
Make sure to include tutorials on how to install them.
You can either make your own tutorials or include a link to them.


### Required Components

List your required hardware components and the quantities here.

| Component Name      | Quantity |
| ------------------- | -------- |
| ESP32 Dev Board     | 1        |
| DHT11 Sensor        | 1        |
| Breadboard          | 1        |
| Jumper Wires        | 5        |


### Required Tools and Equipment

* USB cable for the ESP32
* A computer with Windows, macOS, or Linux

## Part 01: Name

### Introduction

Briefly introduce what  you are teaching in this section.

In this part, you will wire the DHT11 to the ESP32 and run a simple program to read data.

### Objective

- Learn how to connect the DHT11 sensor to the ESP32 board

- Understand which pins to use for power, ground, and data

- Upload and run a basic program that reads sensor values

- Open the Serial Monitor to see temperature and humidity results

- Make sure the code works and can handle errors when the sensor is not working


### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills

### Components

- List the components needed in this challenge

### Instructional

Teach the contents of this section

## Example

### Introduction

Introduce the example that you are showing here.

### Example

Present the example here. Include visuals to help better understanding

### Analysis

Explain how the example used your tutorial topic. Give in-depth analysis of each part and show your understanding of the tutorial topic

## Additional Resources

### Useful links

List any sources you used, documentation, helpful examples, similar projects etc.
