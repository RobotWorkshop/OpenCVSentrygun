# OpenCVSentrygun
A Nerf sentry gun with machine vision based on Open CV.

Two Servos control the pitch and pan. Machine vision achieved with Raspberry Pi 3b and Pi camera module. The firing mechanism consists of two dc spinner motors for propulsion and a servo "firing pin" and an Adafruit PCA9685 16-Channel Servo Driver.

# BOM

Pan Stepper: 1x MG995

Pitch Servo: 1x MG995

Firing servo: 1x MG90S

DC motors: 2x RF-300CA

Control board: 1x Raspi 3b

Servo driver: 1x PCA9685 

Camera: Raspi Cam module 5mp

All frame material is made from miscellaneous scrap

# Code

I have split the code into several modules to make it easier to debug. I self-taught most of the Raspi code from several sources (sources) and have use some of their techniques in my code. I have also included optional code bits that I used for testing throughout the process.
CAD Models

I modeled all the frame components in Solidworks before fabricating. Almost the entire frame is made from miscellaneous scrap.
