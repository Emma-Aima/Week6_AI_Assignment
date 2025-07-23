# Week6_AI_Assignment
Artificial Intelligence for Software Engineering Course

## Project Lead:
Emmanuella Aimalohi Ileogben - emmanuellaileogben@gmail.com

## Project Overview

This repository contains a comprehensive collection of AI-related tasks covering Edge AI, Quantum AI, AI Ethics, Smart Agriculture, Futuristic AI Proposals, and Quantum Computing Simulations. Each task includes theoretical explanations, practical implementations, and ethical considerations.

## Table of Contents
1. Essay Questions

- Edge AI vs. Cloud AI
- Quantum AI vs. Classical AI
- Human-AI Collaboration in Healthcare

2. Case Study Critique

- AI-IoT in Smart Cities (Traffic Management)

3. Practical Implementations

- Edge AI Prototype (Recyclable Item Classifier)
- AI-Driven Smart Agriculture System

4. Ethics in AI

- Bias in Genomic AI (Cancer Treatment)

5. Futuristic AI Proposal

- Neural Interface Cognitive Augmentation (2030 Vision)

6. Bonus: Quantum Computing

- IBM Quantum Circuit for Drug Discovery

## Detailed Breakdown
### 1. Essay Questions
- Q1: Edge AI vs. Cloud AI
**Key Points:**

- Edge AI reduces latency by processing data locally (e.g., autonomous drones).
- Enhances privacy (no data sent to cloud).
- Example: Smart trash bins sorting recyclables in real time.

Q2: Quantum AI vs. Classical AI
**Key Points:**

- Quantum AI excels at optimization (e.g., logistics, drug discovery).
- Industries: Pharma, finance, supply chain.

Q3: Human-AI Collaboration in Healthcare
**Key Points:**

- AI assists radiologists (anomaly detection) and nurses (chatbots).
- Shifts roles toward empathy-driven care.

### 2. Case Study: AI-IoT in Smart Cities
- Focus: Traffic management via AI and IoT sensors.

- Benefits:
Adaptive traffic lights reduce congestion (e.g., Barcelona’s 21% improvement).

- Challenges:
Data security (hacking risks).
Legacy system interoperability.

### 3. Practical Implementations
**Task 1: Edge AI Prototype**
- Goal: Build a lightweight image classifier for recyclable items.
- Tools: TensorFlow Lite, Raspberry Pi (simulated in Colab).

- Steps:
Train MobileNetV2 on TrashNet dataset (~85% accuracy).
Convert to TFLite (quantization reduces size to 2MB).
Deploy on edge devices for real-time inference.

- Deliverable: Code + report with accuracy metrics.

**Task 2: AI-Driven Smart Agriculture**
- Sensors: Soil moisture, temperature, humidity, CO₂.
- AI Model: Random Forest/LSTM for yield prediction.

**Data Flow:**
Sensors → Edge Gateway → Cloud AI → Farmer Alerts  

Deliverable: 1-page proposal + diagram.

### 4. Ethics in Personalized Medicine
- Dataset: Cancer Genomic Atlas (TCGA).

- Biases:
Underrepresentation of ethnic minorities.
Socioeconomic disparities in data collection.

- Solutions:
Diverse training data.
Fairness-aware algorithms (e.g., demographic parity).

Deliverable: 300-word analysis.

### 5. Futuristic AI Proposal (2030)
- Idea: Neural Interface Cognitive Augmentation (NICA).
- Problem: Neurodegenerative diseases (Alzheimer’s, Parkinson’s).

- Workflow:
Neural implants + wearables collect real-time data.
Hybrid AI (SNNs + RL) adjusts brain stimulation.

- Risks: Privacy, inequality, ethical concerns.

Deliverable: 1-page concept paper.

### 6. Bonus: Quantum Computing Simulation
- Tool: IBM Quantum Experience (Qiskit).
- Task: 2-qubit circuit simulating molecular binding.
- AI Link: Quantum parallelism speeds up drug discovery (e.g., VQE algorithm).

Deliverable: Qiskit code + 1-page explainer.

### How to Use This Repository
- Code: Check /code for Python scripts (TFLite, Qiskit).
- Reports: PDFs in /docs for essays and proposals.
- Diagrams: Draw.io files in /assets.

### Dependencies
Python 3.8+, TensorFlow 2.10, Qiskit 0.39.

### License
MIT. Contributions welcome!

#### Note: 
Replace placeholder links (e.g., [TrashNet]) with actual dataset URLs before deployment.

**For questions, open an Issue or contact @[Emma-Aima].**

