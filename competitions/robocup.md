# 🥈 RoboCup Singapore Soccer Open 2025

<p align="center">
<img src="https://github.com/LEST0808/LEST0808/blob/main/resources/gallery/RoboCup/robocup.png" width="800">
</p>

> **2nd Place — First Runner-Up**  
> Robot Soccer · Computer Vision · PID Control · Omni-Directional Drive

---

## 📌 Competition Overview

**RoboCup Singapore Soccer Open 2025** featured autonomous robots competing in the **RoboCup Junior Robot Soccer** category.

Our team developed an autonomous soccer robot using an **ESP32** as the main controller and a four-wheel omni-directional drive system. This competition required two robots per team. We chose to use the same design for both as it is easier to 3D print a spare part.

---

## 🎯 My Role

I contributed to the robot's **software, vision, and movement control**.

I worked with:

- **OpenMV + conical mirror** for wide-angle vision
- **Pixy2** for front-facing ball tracking
- PID-based movement control
- Software tuning and debugging during the competition
- Robot design
- Conical mirror design
- Robot circuit system
- 3D printing

---

## 🤖 Robot

The robot used **four omni-directional wheels positioned 90° apart**, allowing it to move in different directions without rotating.

For vision, two camera systems were used for different purposes:

- **OpenMV + conical mirror** — wide-angle environmental vision
- **Pixy2** — front-facing ball detection and tracking

The robot was designed with 4 separate floor, each floor holds different functions. First floor contains driving system, ball dribbler, sensors, and weight blocks. Second floor holds the battery system and motor driver. Third floor is the main part of the robot which is the microcontroller. And the last floor is the camera system. 

### Main Technologies

`ESP32` `OpenMV` `Pixy2` `PID Control` `Computer Vision` `Fusion 360`

---

## 🏆 Result

**2nd Place — First Runner-Up**

Our initial performance was below expectations. Through iterative software adjustments and testing during the competition, we significantly improved the robot's performance and finished as **First Runner-Up**.
