---
title: "AI-Driven Agricultural Pest Detection"
excerpt: "[/assets/videos/pest-detection.mp4](https://github.com/user-attachments/assets/eeb3ac0f-87be-4d02-9336-bc3d047e5408) (click to play)"
collection: portfolio
---

**MothEye: AI-Robotic Pest Detection**


MothEye is a robotic vision system designed to rapidly detect diamondback moth (DBM) infestations in commercial brassica transplant shipments. Current inspections rely on manual sampling, making it difficult to thoroughly screen the thousands of plants transported into agricultural regions.

We developed a robotic inspection platform that combines automated camera motion, computer vision, and AI-based pest detection. A robotic arm moves a multi-camera array around brassica plants, capturing consistent views that are automatically processed to distinguish infested from healthy plants. The approach is designed to eventually inspect transplant trays directly on delivery trucks—without unloading them.

<img width="3151" height="4996" alt="Artboard 3_1" src="https://github.com/user-attachments/assets/c8865b0d-2cba-4456-9975-0eec7b56f230" />

**From Robot Motion to AI Detection**

For our proof-of-concept, we used a robotic arm to automatically collect video of both DBM-infested and uninfested plants. The repeatable robot trajectories provided consistent imaging conditions while reducing variability introduced by manual data collection. Video frames were extracted and labeled to create a training dataset for a YOLO-based vision model.

The prototype identified DBM infestation across 14 plants in just 10 seconds with 98.7% classification accuracy, demonstrating the potential for robotics and AI to dramatically increase the speed and coverage of agricultural pest inspection.


<img width="3151" height="3782" alt="Artboard 4" src="https://github.com/user-attachments/assets/5b90011a-724a-451d-8b66-9c7498fe61b5" />


**Scaling to Real-World Inspection**


The next-generation system, MothEye, expands this concept into a mobile robotic platform capable of inspecting stacked transplant trays directly inside shipping trucks. Thin camera probes capture plants from multiple viewpoints, while a multi-view AI architecture fuses information across cameras to improve detection under occlusion and other challenging conditions.

The long-term goal is a field-ready system capable of inspecting one tray in approximately 10 seconds, dramatically increasing inspection coverage while maintaining high detection accuracy and avoiding damage to the plants.
