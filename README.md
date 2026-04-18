# SensAI Kits 🎎

This is a collection of context-aware AI kits, fully integrated with the Meta XR SDK and Unity.  
Vision kits are built to support Meta Camera Access (PCA).

![497919668-61759309-e613-454c-a5c1-4fc4c0aaf1ef](https://github.com/user-attachments/assets/27231d3b-42dc-4c8e-bc3f-356d6e9dff88)

## 🎥 Tutorials & Demos

[Watch the playlist](https://www.youtube.com/watch?v=WmOXKcG9dBk&list=PLRQI9ZSqDkKcs_nAnBkrKzbskUQyqnggh)
▶️ Explore step-by-step tutorials and demos

## 📝 Table of Contents

1. [Spectacles Reachy Mini](#1-spectacles-reachy-mini) 
2. [AI Capabilities Workbench](#2-ai-capabilities-workbench) 
3. [Zero-Shot Object Detection Kit](#3-zero-shot-object-detection-kit)  
4. [Custom AI Model Training Kit (Roboflow)](#4-custom-ai-model-training-kit-roboflow)  
5. [Poker AI Assistant (Roboflow)](#5-poker-ai-assistant-roboflow)  
6. [Acknowledgements & Credits](#6-acknowledgements--credits)  
7. [License](#7-license)
8. [Contact](#8-contact)


## Overview

## 1. Spectacles Reachy Mini

🎯 A Snap Spectacles application that enables robot control through AR hand tracking.
<br>
- Control Reachy Mini robot using hand gestures through Spectacles
- Real-time hand tracking to robot movement mapping
- AR visualization of robot controls

<br>

:warning: Setup Notes
* **Hardware Required**: Requires Reachy Mini robot and Snap Spectacles
* **Configuration**: Robot and Spectacles must be connected


#### GitHub: 👉 [Spectacles Reachy Mini](https://github.com/V4C38/spectacles-reachy-mini) 

<img src="https://github.com/user-attachments/assets/f0403599-ffd0-44fa-a249-619bfb68d72a" alt="ReachyMiniSnap" width="540px">

---

## 2. AI Capabilities Workbench

🎯 A Unity based workbench implementing 7 workflows and 10 providers, to bring contextual AI to your apps. Compatible with Meta Quest.
<br>
- Multi-AI Provider Support – Supports Nvidia, OpenAI, Google Gemini, Groq, Roboflow, Stability AI, and AWS  
- Pre-configured scenes with easy API key management, enabling quick AI-powered XR prototypes 

<br>

:warning: Limitations
* **Requires API Keys:** Users must register with the AI providers and configure their own API keys for detection to work  
* **Requires Internet:** Some of the workflows send calls to cloud API


#### GitHub: 👉 [AI Capabilities Workbench](https://github.com/rikturnbull/xr-ai-workbench) 

<img src="https://github.com/user-attachments/assets/c076bb52-f885-4925-9134-9ece9f9e6b0c" alt="AICapabilities" width="540px">

---

## 3. Zero-Shot Object Detection Kit

🎯 A Unity plugin that enables real-world object detection in XR using Microsoft Florence-2 on Meta Quest.
<br>
- Instantly detect objects in your environment with zero-shot AI (no training required)  
- Send image data from your Quest to the Florence API and receive rich detection \& description results  
- Fully integrated with Unity for easy setup and flexible use in XR workflows  

<br>

:warning: Limitations
* **Not Real-Time:** API response times mean detection is fast but not instantaneous  
* **Requires Internet:** Wi-Fi needed to send images to the cloud API
* **No Timestamps:** Bounding boxes are not time-synced  


#### GitHub: 👉 [Zero-Shot Object Detection Kit](https://github.com/lucas-martinic/Unity-MetaXR-AI-ZeroShot)  

<img src="https://github.com/user-attachments/assets/af060cf1-c1d7-4d1d-9e15-552d8bfa2212" alt="MetaPCARoboflow" width="540px">

---

## 4. Custom AI Model Training Kit (Roboflow)

🤖 A Unity plugin that brings you custom-trained object detection to XR — powered by Roboflow and optimized for Meta Quest.
<br>
- Upload and annotate your own image datasets (capturing directly on Meta Quest recommended)  
- Run models locally on-device for faster inference and offline use  
- Fully integrate detection results into your Unity XR app  


<br>

:warning: Setup Notes

- **Setup Time:** Requires effort to collect, annotate, and train datasets  
- **CUDA & Docker Setup Needed:** See [Roboflow’s repo](https://github.com/roboflow/inference)


#### GitHub: 👉 [Custom AI Model Training Kit](http://github.com/nigelhartm/MetaPCARoboflow)  

<img src="https://github.com/user-attachments/assets/a1ac22fc-464e-49b6-8e95-367dd802c66b" alt="MetaPCARoboflow" width="540px">

---

## 5. Poker AI Assistant (Roboflow)

♣️ A Meta Quest application that uses computer vision and Poker Odds API to calculate poker hand strenght in real time. 
<br>
- Detects poker cards and calculates odds and win probabilities
- Runs 100,000+ simulations for highly accurate predictions using the Poker Odds API
- Performs local inference directly on Meta Quest
- Minimalistic UI/UX optimized for wearables 


<br>

:warning: Setup Notes

- **Wi-Fi Configuration:** Ensure Meta Quest is on the same Wi-Fi as your server
- **Server Setup:** Local Roboflow inference server and Node.js Poker Odds server must be running
- **Permissions & IP:** Verify permissions on Meta Quest and correct IP address in RoboflowCaller  
- **CUDA & Docker Setup Needed:** See [Roboflow’s repo](https://github.com/roboflow/inference)  

#### GitHub: 👉 [Poker AI Assistant](https://github.com/nigelhartm/PokerAssistant)  

<img src="https://github.com/user-attachments/assets/f1708647-8ff1-47a1-b5a2-89a327b1f620" alt="MetaPCARoboflow" width="540px">

---

## 6. Acknowledgements & Credits
* Join [SensAI Hack](https://sensaihack.com) and connect with a community of creators and innovators.
* Explore our [SensAI World Model Kits](https://github.com/SensAIHackademy/SensAIWorldModelKits) for templates to build interactive 3D world models across WebXR, Unity, and Unreal Engine.
* Check out our [SensAI PICO Kits](https://github.com/SensAIHackademy/SensAI-PICO-Kits) for XR development tools optimized for PICO devices, including voice, multi-view panels, and world models.
* Visit our [SensAI Knowledge Hub](https://xrbootcamp.notion.site/SensAI-Knowledge-Hub-21f0095e34d880ec9826d9749ae56619) for curated learning use cases and inspiration across AI, XR, and robotics.
* Huge thanks to [Lucas Martinic](https://www.linkedin.com/in/lucas-martinic/) for the Zero-Shot Object Detection Kit.
* Thanks to [Nigel Hartman](https://www.linkedin.com/in/nigelhartman/) for the Custom AI Model Training Kit (Roboflow).
* Big shoutout to [Rik Turnbull](https://x.com/rikturnbull) for the AI Capabilities Workbench.
* And thanks to [Johannes Tscharn](https://x.com/JohannesTscharn) for the Spectacles Reachy Mini.

Powered by [SensAI Hackademy](https://sensaihackademy.com)

---

## 7. License
📜 By downloading and using these kits, you agree to the [License Terms](./LICENSE).


---

## 8. Contact
✉️ Have questions, suggestions, or feedback? We’d love to hear from you!
Reach out to us at hello@sensaihack.com

<br>

---
