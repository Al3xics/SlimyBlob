# Alternative Controller – Visual Particle Experience  
*Unreal Engine 5 – Niagara – Alternative Controller*

![Status](https://img.shields.io/badge/Prototype-Yes-blue)
![Engine](https://img.shields.io/badge/Engine-UE5-black)
![Controller](https://img.shields.io/badge/Controller-Alternative-green)

---

## Project Description

![](Images/Image1.png)

This project proposes a visual experience highlighting **Niagara (UE5)**.  
The player controls a **sphere of colored particles** evolving in a **completely black environment**, structured only by **glowing neon lights** that define the map.

![](Images/Video.gif)

By passing through certain **light zones**, the sphere absorbs their **colors**, creating a strong contrast within the darkness.

![](Images/Video2.gif)

It is also possible to **control wind** to interact with the particles of the sphere when it changes color.

---

## Objectives

- Showcase the visual capabilities of **Niagara**  
- Create a minimalist environment based on light  
- Experiment with a **physical alternative controller**

---

## Alternative Controller

![](Images/Image6.jpg)

### 🔸 Movement — Breath + Balloon  
The player blows into a balloon which, as it inflates, presses a **physical button**.  
When the button is activated, the sphere moves forward.

![](Images/Image4.png)

**Logic:** interaction based on **air flow** and pressure buildup.

### 🔸 Rotation — Manual Wheel  
A **physical wheel** allows turning left and right.

![](Images/Image5.png)

---

## Gameplay

- Observe the movement of the sphere’s particles in a dark and silent world  
- Use **neon lights** as landmarks and boundaries  
- Change color by passing through light zones  
- Play physically: blow, turn, manipulate the controller  

---

## Technologies Used

| Technology | Usage |
|------------|-------|
| **UE5** | Game engine |
| **Niagara** | Particles & visual effects |
| **Microcontroller / Sensors** | Inputs & main board |
| **Cardboard prototype** | Current physical structure |

---

## Areas for Improvement

### 1. Air / Pressure Sensor  
Replace the balloon with:  
- a **differential pressure sensor**, or  
- an **airflow sensor**.

Objective: **precision**, **durability**, **hygiene**, better **responsiveness**.

### 2. Controller Structure  

![](Images/Image3.png)

The controller is currently made of **cardboard**.  
A future version could include:

- **3D-printed structure**  
- Internal components better integrated into the structure  
- Improved overall ergonomics  

Objective: **strength**, **quality**.
