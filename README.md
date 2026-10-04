# 🚁 SkyForge Mini FPV

## Custom 3-Inch FPV Quadcopter

SkyForge Mini FPV is a custom-built 3-inch FPV drone designed and developed from scratch.

The project focuses on building a custom flight controller, custom transmitter, wireless control system, FPV video system, custom frame, and complete drone electronics.

---

## 🎯 Project Goal

The goal of this project is to design and build a working 3-inch FPV quadcopter using individually selected components and custom electronics.

Instead of using a commercial flight controller, this project uses an ESP32-based custom flight controller.

---

## ⚙️ Main Features

- Custom 3-inch drone frame
- ESP32-based custom flight controller
- MPU6050 IMU
- nRF24L01 wireless communication
- Arduino UNO-based transmitter
- Custom transmitter PCB design
- Custom flight-controller PCB design
- 4-in-1 ESC
- 4 × 1404 4500KV brushless motors
- 3-inch propellers
- 4S LiPo battery
- FPV camera
- 5.8GHz analog video transmitter
- Analog FPV goggles
- Battery voltage monitoring
- Failsafe system

---

## 🧠 Flight Controller

The custom flight controller is based on an ESP32.

### Components

- ESP32
- MPU6050
- nRF24L01 receiver
- 5V regulator
- Battery voltage sensing

### Flight Controller Flow

```text
nRF24L01 Receiver
        ↓
      ESP32
        ↕
     MPU6050
        ↓
 Motor Mixing / PID
        ↓
    4-in-1 ESC
## Project Design

### Drone Hardware

![SkyForge Mini FPV Drone](1000072591.jpg)

### Custom Transmitter

![SkyForge Mini FPV Transmitter](1000072592.jpg)
   ↓   ↓   ↓   ↓
  M1  M2  M3  M4
