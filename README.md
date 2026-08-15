# Sub-Chapter-1.1-Non-blocking-programming---LCD-Basics

## Description
### In this repository, we will learn the basics of LCD using the non-blocking timer refresh. Also, we'll apply it to projects of Chapter 1. 
### It is important to know we'll simplified the LCD wiring by using a I2C driver, that only need 4 wires: VCC (To 5V pin), GND, SDA (to A4 pin) and SCL(to A5 pin);
### We will also use the LiquidCrystal_I2C.h library, there are many others, but we'll use that one!, you can use your favorite one, but make sure if need to change the pin connections.

## Features:
### - Non-blocking programming (Can print data to LCD without blocking other components, like LEDs or motors)

## Main hardware:
### - LCD 0X27 ; Size 16x2
### - I2C Driver
### - Arduino UNO
