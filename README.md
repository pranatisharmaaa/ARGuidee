# 🥽 ARGuide – AI-Powered Augmented Reality Remote Assistance Platform

ARGuide is a real-time augmented reality collaboration platform that enables experts to remotely guide field technicians through interactive AR annotations, gesture-based controls, AI-powered assistance, and low-latency live video communication.

**Top 10 Finalist – Google Developer Groups (GDG) Hackathon**

---

## Problem Statement

Remote troubleshooting often relies on traditional video calls where experts verbally explain procedures without being able to interact directly with the technician's environment.

This leads to:

* Longer resolution times
* Increased operational costs
* Communication gaps
* Higher chances of human error

ARGuide solves this by providing real-time visual guidance through augmented reality overlays and intelligent assistance.

---

## Key Features

### Real-Time Expert Assistance

* Live technician-to-expert communication
* Interactive visual guidance
* Session-based collaboration

### AR Annotation System

* Draw directly on the technician's workspace
* Persistent visual overlays
* Real-time synchronization

### Gesture-Based Interaction

* Pinch-to-Draw
* Wave-to-Erase
* Touchless interaction using MediaPipe

### AI Assistance Layer

* Gemini-powered troubleshooting support
* Context-aware guidance generation
* Intelligent assistance recommendations

### Motion Tracking

* Sum of Absolute Differences (SAD) based motion detection
* Improved annotation stability
* Real-time tracking optimization

---

## System Architecture

Technician Dashboard
↓
WebRTC Video Stream
↓
Expert Dashboard
↓
MediaPipe Gesture Engine
↓
Three.js AR Annotation Layer
↓
WebSocket Synchronization Server
↓
Real-Time AR Overlay Rendering

---

## Technology Stack

### Frontend

* React
* TypeScript

### Backend

* Node.js
* Express.js

### Communication Layer

* WebRTC
* WebSockets

### Computer Vision

* MediaPipe

### Motion Detection

* Sum of Absolute Differences (SAD)

### 3D Rendering

* Three.js

### AI Layer

* Google Gemini API

---

## Technical Highlights

### WebRTC-Based Streaming

Implemented peer-to-peer low-latency video streaming architecture for real-time communication between technicians and remote experts.

### Real-Time Synchronization

Used WebSockets to synchronize annotations, gesture events, and interaction states across multiple connected clients.

### Gesture Recognition Engine

Integrated MediaPipe hand tracking to detect:

* Pinch gestures for drawing
* Wave gestures for erasing

allowing completely touchless AR interaction.

### AR Rendering Pipeline

Built a Three.js-based rendering engine for creating dynamic overlays and annotations directly on top of live video streams.

### Motion Detection System

Implemented a Sum of Absolute Differences (SAD) algorithm for frame-to-frame motion estimation, improving tracking consistency and annotation accuracy.

### AI-Powered Assistance

Integrated Gemini API to generate contextual troubleshooting suggestions and support technicians during maintenance operations.

---

## Impact

Compared to conventional video-call-based troubleshooting, ARGuide enables:

* Faster issue resolution
* Reduced communication ambiguity
* Improved technician productivity
* More intuitive remote collaboration
* Reduced operational downtime

---

## Hackathon Recognition

🏆 Top 10 Finalist – Google Developer Groups (GDG) Hackathon

Selected among leading student innovation teams for developing a practical AR-powered remote assistance solution.

---

## Team

* Pranati Sharma
* Team Members (4 Total)

Team Size: 4 Members

---

## Live Demo

### Technician Dashboard

https://ar-vr-guide-technician.vercel.app/#/live-session

### Expert Dashboard

https://ar-vr-guide-expert.vercel.app/

---

## Future Enhancements

* Multi-expert collaboration
* AR object anchoring
* Voice-command integration
* LLM-powered maintenance workflows
* Edge AI deployment
