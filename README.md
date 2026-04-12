# RF-SDA-System
## Building a Doppler-based Space Domain Awareness system using COTS technology and machine learning.
---
This repository represents my first step towards a project I have been thinking about pursuing for a while: a localized Space Domain Awareness (SDA) system that tracks the velocity and direction of satellites overhead using the Doppler from their telemetry.

Initially, I intend to use software defined radios (RTL SDR v4 & HackRF) along with antennas suited for CubeSat telemetry reception. The first step is to develop the basic capability to detect and record CubeSat telemetry. Following that, I will work probably the most difficult portion of this project: sensing and utilizing the Doppler to determine satellite direction and velocity. I will use updated two line element (TLE) codes as my reference data to validate my system. After developing a satisfactory Doppler-sensing capability, I intend to train an AI/ML model on this data to further automate the SDA system.

AI DISCLAIMER: I fundamentally believe that AI has become the next information revolution, comparable to the advent of the internet. It will only become more prominent in future workflows. In light of that, I intend to use frontier LLMs (alongside locally-run LLMs that I have configured) to assist my learning and development process. However, I will not steal AI work and pass it as my own - by doing so, I would only be shooting myself in the foot. Instead, each update to this project will include a thorough log of AI contributions to the project. This README will always be a reflection of my own words untouched and un-reviewed by AI.

This project will be updated at least once a week until completion.
