# 🚀 CivicLens – AI-Powered Civic Issue Detection & Routing System

CivicLens is a smart civic issue management platform designed to transform how urban problems are reported and resolved. By combining Computer Vision, automation, and intelligent decision-making, it enables faster, more efficient, and data-driven governance.

---

## 🌍 Problem Statement

Urban civic issues such as potholes, garbage accumulation, and water leakage often remain unresolved due to:

* Manual and unstructured reporting systems
* Lack of prioritization of critical issues
* Inefficient routing and delayed response

These challenges lead to poor infrastructure management, slower resolution times, and reduced citizen trust.

---

## 💡 Proposed Solution

CivicLens introduces an AI-powered system that:

* Detects civic issues directly from images
* Automatically assigns priority based on real-world factors
* Routes complaints to the correct department without manual intervention
* Provides a real-time dashboard for monitoring and resolution

The goal is to move from **complaint collection → intelligent resolution**.

---

## 🧠 Core Features

* 📸 **AI-Based Issue Detection**
* ⚡ **Smart Priority Engine**
* 🔄 **Automated Routing System**
* 🗺️ **Live Monitoring Dashboard**
* 🔔 **Status Tracking**
* 🧠 **Duplicate Detection**

---

## 🏗️ System Architecture

```mermaid
graph LR
    A[User Web App React] --> B[Backend API Node]
    B --> C[FastAPI AI Service]
    C --> D[YOLOv8 OpenCV Processing]
    D --> E[MongoDB Database]
    B --> F[Municipal Dashboard React]
    F --> E
```

---

## 🔄 System Workflow

```mermaid
flowchart LR
    A[User Upload Image] --> B[Backend Receive Request]
    B --> C[AI Process Image]
    C --> D[Detect Issue]
    D --> E[Assign Priority]
    E --> F[Check Duplicate]
    F --> G[Route Department]
    G --> H[Authority Dashboard]
    H --> I[Resolve Issue]
    I --> J[Notify User]
```

---

## 🧠 AI Processing Pipeline

```mermaid
flowchart LR
    A[Input Image] --> B[Preprocessing OpenCV]
    B --> C[YOLOv8 Detection]
    C --> D[Classification]
    D --> E[Severity Estimation]
    E --> F[Output Issue + Priority]
```

---

## 📊 Data Flow Diagram

```mermaid
sequenceDiagram
    participant User
    participant Frontend
    participant Backend
    participant AI
    participant DB
    participant Authority

    User->>Frontend: Upload Image
    Frontend->>Backend: Send Request
    Backend->>AI: Process Image
    AI-->>Backend: Result
    Backend->>DB: Store Data
    Backend->>Authority: Assign Issue
    Authority-->>Backend: Update Status
    Backend-->>Frontend: Send Updates
    Frontend-->>User: Notify
```

---

## 🧰 Technology Stack

### Frontend

* React.js
* Vercel

### Backend

* Node.js
* FastAPI
* Render

### AI / ML

* YOLOv8
* OpenCV

### Database

* MongoDB

### DevOps

* Docker

---

## ⚙️ System Intelligence

* Real-time processing
* Location-aware prioritization
* AI-driven decisions
* Scalable architecture

---

## 📈 Feasibility

* Uses pre-trained models
* Lightweight tech stack
* Easy to scale
* Hackathon-ready

---

## 📈 Impact

* 🏙️ Smarter city management
* ⚡ Faster issue resolution
* 📊 Data-driven governance
* 🤝 Better transparency
* ⚙️ Efficient resource use

---

## 🌱 SDG Alignment

Aligned with **UN SDG 11: Sustainable Cities and Communities**

---

## 🔮 Future Scope

* WhatsApp integration
* Voice-based reporting
* Predictive analytics
* Smart city integration

---

## 👨‍💻 Team

* Rishabh Dev Pandey
* Raghav Rege
* Devansh Saxena
* Swarnava Sarkar

---

## 📌 Note

This project is currently in the design phase.
