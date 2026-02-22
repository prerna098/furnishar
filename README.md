#  FurnishAR

An Augmented Reality (AR) interior design application built with Unity that enables users to visualize and interact with virtual furniture in real-world environments using mobile AR technology.

FurnishAR bridges physical space and digital content, allowing users to preview furniture placement, scale, and layout before making real-world decisions.

---

##  Project Overview

FurnishAR is a location-aware and surface-detection-based AR system that allows users to:

- Place 3D furniture models in real space
- Interact with objects using touch gestures
- Rotate, scale, and reposition virtual furniture
- Visualize interior layouts before purchase

This project simulates a production-style AR furnishing application similar to those used in modern e-commerce and interior design platforms.

---

##  Core Features

###  AR Plane Detection
- Detects horizontal surfaces
- Anchors 3D objects to real-world planes
- Stable object placement using AR tracking

###  Furniture Placement
- Tap-to-place interaction
- Supports multiple furniture objects
- Dynamic prefab-based loading

###  Object Interaction
- Drag to reposition
- Pinch to scale
- Two-finger rotate gestures
- Real-time transform updates

###  User Interface
- Clean object selection panel
- Thumbnail previews
- Minimal and intuitive interaction design

###  Modular Architecture
- Script-based AR management
- Separated UI and interaction logic
- Easily extendable model system

---

##  Tech Stack

- Unity Engine
- AR Foundation
- ARCore (Android)
- ARKit (iOS)
- C#
- Unity UI System
- 3D Models (FBX / OBJ)
- Mobile Build Support

---


- **Scripts/** → Handles AR logic and user interactions  
- **Models/** → 3D furniture assets  
- **Prefabs/** → Reusable AR objects  
- **Scenes/** → Unity scenes  
- **UI/** → Interface layout and components  

---

##  How To Run

###  Prerequisites

- Unity 2019.4+ (recommended LTS version)
- AR Foundation installed via Unity Package Manager
- ARCore (for Android) or ARKit (for iOS) enabled
- Physical AR-supported mobile device

---

###  Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/prerna098/furnishar.git

