# 🌍 GDG Hackathon Hyderabad 

## 🧠 Overview

This project is an **Bridge Talk** built for the **GDG Hackathon Hyderabad**, focused on empowering **deaf, mute, and visually impaired users**.

The platform enables:
- **Sign Language → Text** using the **Google Gemini API**
- **Text → Sign Language** using **3D sign avatar animations**
- **Smart navigation for visually impaired users**, with intelligent routing and real-time obstacle detection

---

## ✨ Features

### 🖐️ Sign Language to Text
- Users perform sign language gestures
- Gestures are interpreted using **Gemini AI**
- Converted into readable **text in real time**

---

### ✍️ Text to Sign (3D Animation)
- Users provide text input
- The system generates **3D sign language animations**
- Powered by an **ASL-optimized Sign Avatar dataset**

> ⚠️ Text-to-Sign runs through a **separate server** (setup required)

---

### 🧭 Smart Navigation for Visually Impaired Users

#### 🚍 Journeys Greater Than 1 KM
- Provides:
  - Public bus routes
  - Step-by-step navigation
  - Continuous journey guidance

#### 📷 Journeys Less Than 1 KM
- Activates live camera assistance
- Uses **COCO Object Detection Model**
- Detects obstacles and helps users avoid collisions safely

---

## 🛠️ Tech Stack

- **Frontend:** React + TypeScript  
- **AI / NLP:** Google Gemini API  
- **3D Animation:** Sign Avatar Dataset (ASL optimized)  
- **Computer Vision:** COCO Object Detection  
- **Backend / Scripts:** Python  
- **Build Tool:** Vite  

---

## 📂 Project Structure

```text
gdg-hackathon-hyderabad/
│
├── src/
│   ├── components/      # UI components
│   ├── pages/           # Application pages
│   ├── services/        # Gemini API & AI services
│   └── utils/           # Helper utilities
│
├── scripts/
│   ├── download_models.py
│   ├── inspect_smplx.py
│   ├── install_openh264.py
│
├── public/
├── App.tsx
└── README.md


🚀 Getting Started
✅ Prerequisites

Make sure you have the following installed:

Node.js (v18+ recommended)

Python 3.8+

Git

Google Gemini API Key

📦 Installation
git clone https://github.com/sanjayy-22/SignAvatars
cd gdg-hackathon-hyderabad
npm install

🔐 Environment Variables

Create a .env file in the root directory and add your Gemini API key:

GEMINI_API_KEY=your_gemini_api_key_here

▶️ Run the Application Locally
npm run dev


The application will start locally and be ready for use.

🤖 Text to Sign – Server Setup (Required)

⚠️ Note:
Text-to-sign animation does not run directly inside this repository.
A separate server is required.

🔹 Step 1: Clone the Sign Avatar Server
git clone https://github.com/sanjayy-22/SignAvatars
cd SignAvatars

🔹 Step 2: Download the Dataset

Request access to the dataset by filling out the form below:

🔗 Dataset Request Form : https://docs.google.com/forms/d/e/1FAIpQLSc6xQJJMf_R4xJ1sIwDL6FBIYw4HbVVv_HUgCqeiguWX5XGPg/viewform

Dataset Details:

ASL-optimized Sign Avatar dataset

File format: .pkl

Approximate size: 12 GB

🔹 Step 3: Run the Text-to-Sign Server
python desktop/text_to_sign_server.py


Once the server is running, the main application will send text input to this server, which generates 3D sign language animations using the Sign Avatar dataset.

👁️ Object Detection & Camera Guidance

Uses COCO pre-trained object detection model

Detects:

People

Objects

Obstacles

Provides real-time guidance for visually impaired users to ensure safe navigation

🎯 Use Cases

🧏 Deaf users converting sign language into readable text

🗣️ Mute users expressing text through 3D sign animations

👨‍🦯 Blind users navigating safely indoors and outdoors

🚌 Inclusive navigation for public transport and city travel
# foss-hack
# hack
