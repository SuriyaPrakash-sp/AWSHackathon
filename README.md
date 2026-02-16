# AWSHackathon
# AURA-EDU
**AI-powered Unified Rehabilitation Assistant for Educational environments**

*Classroom-integrated wearable AI for real-time spatial neglect rehabilitation*

## Why This Matters

Hemispatial neglect significantly impacts a student's ability to engage with classroom material, yet rehabilitation typically occurs outside the learning environment.  

AURA-EDU brings intelligent, real-time assistive support directly into classrooms — enabling continuous rehabilitation without disrupting education.

## Problem Statement

Over 5 million stroke and traumatic brain injury survivors experience hemispatial neglect—a condition where patients fail to attend to stimuli on one side of their visual field. Traditional rehabilitation requires expensive clinical sessions that are often inaccessible to students in educational settings, leaving many without adequate support during critical learning years.

## Our Solution

AURA-EDU is a wearable AI system that provides continuous, personalized spatial neglect rehabilitation directly in classroom environments. The system uses computer vision, biometric monitoring, and adaptive AI to detect attention deficits in real-time and deliver discrete haptic feedback to help users develop compensatory strategies.

## Key Features

- **Real-Time Detection**: Computer vision algorithms identify spatial neglect patterns with prototype-level accuracy in controlled conditions
- **Adaptive AI**: Neuroadaptive reinforcement learning personalizes therapy intensity based on biometric feedback
- **Classroom Integration**: Discrete haptic feedback operates silently without disrupting educational activities
- **Privacy-First**: All AI processing occurs locally on-device with no cloud dependency
- **Continuous Monitoring**: 4-hour battery life supports extended classroom sessions
- **Multi-Modal Sensing**: Integrates RGB-D camera, IMU, heart rate, and electrodermal activity sensors

## Architecture Overview

```
Wearable Sensors → Edge AI Processing → Neuroadaptive Engine → Haptic Feedback → Secure Dashboard
```

**Core Components:**
- **Hardware**: NVIDIA Jetson Nano, Intel RealSense D435i, biometric sensors, vibrotactile array
- **AI Pipeline**: CLAP-ED vision processing, OSP-ED eye tracking, Q-learning adaptation
- **Interface**: Web-based rehabilitation dashboard for therapists and educators

## Technology Stack

**Hardware Platform:**
- NVIDIA Jetson Nano (Edge AI processing)
- Intel RealSense D435i (RGB-D + IMU)
- MAX30102 (Heart rate variability)
- Custom vibrotactile feedback array

**Software Framework:**
- Python 3.8 with PyTorch 1.9
- TensorRT 8.0 for model optimization
- OpenCV 4.5 for computer vision
- Flask for web dashboard
- SQLite for local data storage

**AI/ML Libraries:**
- YOLOv5 for object detection
- MediaPipe for eye tracking
- Stable-Baselines3 for reinforcement learning

## 🚀 What Makes AURA-EDU Different

- **Edge AI Processing**: Sub-200ms response times with complete privacy through local inference
- **Multi-Modal Sensor Fusion**: Synchronized RGB-D, motion, and biometric data with millisecond precision
- **Neuroadaptive Learning**: Q-learning algorithms that continuously adapt based on real-time performance
- **Educational Integration**: Purpose-built for classroom environments with discrete operation
- **Scalable Design**: Prototype targets <$500 per unit with support for 5 concurrent devices

## Prototype Scope

**Hackathon Deliverables:**
- Functional wearable prototype with core sensor integration
- Real-time spatial neglect detection demonstration
- Basic adaptive feedback system
- Web dashboard for progress monitoring
- Controlled environment validation

**Technical Targets:**
- 200ms processing latency for computer vision pipeline
- 4-hour continuous operation on single charge
- Validated in controlled prototype testing
- Precise head tracking for spatial orientation

## Future Scope

**Clinical Validation:**
- Longitudinal studies with educational institutions
- Integration with standardized cognitive assessments
- FDA guidance compliance for educational wellness devices

**Technology Enhancement:**
- Advanced eye tracking with gaze prediction
- Federated learning for population-level insights
- Integration with existing educational technology platforms
- Extended battery life and miniaturization

**Market Expansion:**
- Adaptation for other cognitive rehabilitation needs
- Professional therapy clinic integration
- Home-based rehabilitation support

## Team

Tharvin M
Suriya Prakash SP
Saran Vishakan RG
Sanjay R

## Vision

AURA-EDU represents a step toward intelligent assistive technology that integrates seamlessly into everyday learning environments — making rehabilitation continuous, accessible, and stigma-free.
