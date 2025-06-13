# 🎯 Valorant Agent Detection with YOLOv11

This project focuses on **fine-tuning a pretrained YOLOv11 model** to detect and classify four agents from the game **Valorant**: **Phoenix, Jett, Brimstone, and Sage**. The goal is to build an accurate object detection pipeline capable of identifying these characters in chaotic gameplay frames.

## 🕹️ Challenge Overview

**Valorant** is a tactical first-person shooter where players control unique characters known as _agents_, each with distinct abilities and visuals. In this challenge, you're tasked with building a computer vision system to:

- Detect agents within in-game screenshots.
- Classify them correctly as **Phoenix**, **Jett**, **Brimstone**, or **Sage**.

### 📦 Dataset

- A curated set of Valorant gameplay screenshots.
- Bounding boxes provided in **Pascal VOC (XML)** format.
- Images do **not** have annotations drawn — all bounding info is in XML files.

This setup is ideal for exploring:
- Object detection
- Transfer learning with YOLOv11
- Game analytics and video understanding
