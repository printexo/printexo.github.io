# Quick Start

This page provides a brief introduction to **PrintExo**, an open-source, shoe-agnostic, 3D-printable ankle exoskeleton designed to lower the practical barriers associated with ankle exoskeleton research and education.

After reading this page, you will understand:
- what PrintExo is,
- what major components it consists of,
- how to navigate the documentation.

---

## 🧭 What is PrintExo?

PrintExo is an ankle exoskeleton platform developed with the following primary objective:

> **to lower the practical barriers that impede researchers and educators from entering ankle exoskeleton research.**

Typical challenges in this field include:

- long design iteration cycles  
- difficulty of fabrication  
- lack of reproducibility across laboratories  

PrintExo addresses these issues through three main design principles:

1. **All custom structural components are fabricated using consumer-grade desktop FDM 3D printers.**
2. **All non-printed components consist of standard off-the-shelf parts.**
3. **The device interfaces with commercially available footwear in a non-invasive manner without permanent modification.**

PrintExo is intended for:

- locomotion research  
- exoskeleton control development  
- classroom education and workshops  
- pilot validation studies  

> ⚠ PrintExo is a **prototype research platform**.  
> It is **not a certified medical device** and should not be used for diagnosis, treatment, rehabilitation, or unsupervised assistance.

---

## 🛠 System Components

PrintExo consists of four major subsystems that work together to deliver ankle assistance.

### 1) Actuation module

- CubeMars AK60-6 actuator with integrated driver  
- 1:4 3D-printed planetary gearbox  
- protective outer housing  
- bearings integrated into the planetary stage  

This module generates the assistive torque delivered to the ankle.

---

### 2) Shank structure

- mounted on the lateral side of the lower leg  
- vertically extended structural support  
- secured using a sports calf support sleeve  
- includes **passive inversion/eversion hinge** in the frontal plane  

The structure provides:

- attachment to the leg
- alignment with ankle kinematics
- mitigation of off-axis loading

---

### 3) Shoe interface

The shoe interface:

- uses **shoelace-based integration**
- requires **no permanent shoe modification**
- is positioned on the **dorsal midfoot**
- includes **auxiliary plantar lacing**

Key functional roles:

- anchors torque transmission to footwear  
- maintains interface contact during swing and stance  
- allows compatibility with diverse lace-up shoes  

The geometry is **parametric**, enabling printed size variations.

---

### 4) Electronics and control

The electronics architecture includes:

- actuator integrated motor driver
- wiring and power routing
- control software that applies prescribed torque profiles

Real-time gait phase estimation is performed using:

- IMU mounted on the dorsum of the shoe
- angular-velocity–based detection

---

## 📚 How to Use This Documentation

The documentation is structured to support:

- researchers
- students
- instructors
- builders

### If you want to build the device

Follow this order:

1. **Bill of Materials (BOM)**
2. **3D Printing Guide**
3. **Assembly Guide**
4. **Electronics Overview**
5. **Motor Driver and Configuration**
6. **Running Demo**

---

### If you are teaching or learning

See the **Workshop / Course** section:

- Lesson 1 — Introduction  
- Lesson 2 — 3D Printing  
- Lesson 3 — Assembly  
- Lesson 4 — Electronics & Control  
- Lesson 5 — Walking Demo  
- Final project module  

These materials are intended to support structured curricula.

---

### If you are conducting research

You may refer to:

- **System Design**
- **Fabrication & Implementation**
- **Pilot Validation**
- **Citation information**

---

### If you encounter issues

Check:

- Hardware troubleshooting  
- Electronics troubleshooting  
- Software troubleshooting  

---

## 🚀 Next Steps

Recommended reading order:

1. **System Design**
2. **Bill of Materials (BOM)**
3. **3D Printing Guide**
4. **Assembly Guide**

From there, continue to electronics and control.

---
