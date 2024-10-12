# Kalman Filter Fun!

### (WIP)

The Kalman filter is a recursive optimal estimation algorithm, designed to solve the discrete-data filtering problem. It has enabled significant advancements in modern control theory, GNC systems, computer vision, signal processing, voice recognition, and much more. I got particularly interested in it after reading about it in "Controls Engineering in the FIRST Robotics Competition" by Tyler Veness. I decided to try making an application of a linear Kalman filter in Python. Luckily, there are lots of robust implementations online so I had plenty of help!

The goal of this project is to investigate and solve a theoretical problem wherein the end user wants to approximate a moving vehicle’s position, given external conditions (such as passing through a tunnel) that can cause noise and interference with the vehicle’s sensors. These conditions affect the quality and reliability of the data and renders the position readings unreliable. The objective is to implement a "quick and dirty" Kalman filter algorithm that can fuse the noisy parameters available (position, velocity, and acceleration) from the onboard sensors and produce position estimates that respond and update in real-time to new data. 
