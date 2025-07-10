# Deep Truth: A Multimodal Lie Detection System

## 📘 Project Overview

**"Real-Time Lie Detection via Micro-Expression and Voice Analysis"** is an AI-driven system designed to identify deceptive behavior through involuntary facial cues and vocal patterns. Micro-expressions—fleeting, subconscious muscle movements—can reveal hidden emotions often suppressed during deception. By integrating **Computer Vision**, **Machine Learning**, and **Speech Analysis**, this project provides a **non-invasive, real-time lie detection framework** that mimics human intuition with computational precision.

---

## 🧠 Key Features

- ⚡ **Real-Time Detection** of lies through facial expressions and speech
- 👁️ **Facial Landmark Tracking** using MediaPipe for micro-movement analysis
- 🎙️ **Voice Input Processing** for natural speech-based detection
- 📈 **Multimodal Classification** using deep learning models
- 🧰 **Preprocessing & Augmentation** pipeline for enhanced robustness
- 🖼️ **Live Visualization** with labeled outputs (Lie/Truth + probability score)
- 🔒 **Optional Face Snapshot Saving** with prediction logging

---

## 🔧 Technologies & Tools

| Tool            | Purpose                                           |
|------------------|---------------------------------------------------|
| 🐍 Python         | Core programming language                         |
| 📷 OpenCV         | Frame capture, face detection, and display       |
| 🎯 MediaPipe      | Real-time facial landmark detection              |
| 🗣️ SpeechRecognition | Audio capture and speech-to-text conversion     |
| 🤖 TensorFlow / PyTorch | Deep learning model training & inference     |
| 🌲 Scikit-learn (Random Forest) | Baseline ML classifier              |
| 🧵 Threading       | Asynchronous processing for real-time execution |

---

## 🧪 How It Works

1. **Capture:** Video input is split into frames; face and landmarks are detected in real-time.
2. **Voice Input:** Speech is transcribed and analyzed during response.
3. **Feature Extraction:** Facial tension zones and vocal patterns are extracted.
4. **Classification:** The model classifies the input as **Lie** or **Truth**.
5. **Output:** Prediction is shown live, with optional face snapshot logging.

---

## 🌐 Real-World Applications

- 👮‍♂️ **Law Enforcement & Interrogation Analysis**
- 🧠 **Psychological & Behavioral Research**
- 💼 **Job Interviews & Candidate Screening**
- 🤖 **Emotion-Aware Human-Computer Interaction (HCI)**
- 🛡️ **Border Security & Surveillance Intelligence**

---

## 🚀 Why This Matters

This project explores the intersection of AI and human psychology, offering a non-intrusive, scalable, and real-time approach to understanding human behavior through facial expressions. As smart systems become more human-aware, tools like these can redefine the way we interpret and respond to emotions in both digital and real-world settings.
