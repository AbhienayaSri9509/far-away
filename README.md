
# 🤟 Sign Bridge AI – Real-Time Sign Language Communication Platform

Sign Bridge AI is an **AI-powered sign language communication platform** designed to make conversations more inclusive for the deaf and hard-of-hearing community.  
It combines **real-time sign recognition**, **text-to-sign animation**, **voice output**, and **multilingual support** to bridge the communication gap between sign language users and non-signers.

---

## 🌟 Features

- 🎥 **Real-Time Sign Recognition**
  - Detects and interprets sign language gestures using AI + webcam input.

- 🔤 **Text to Sign Translation**
  - Converts typed text into sign language animations using a separate Sign Avatar server.

- 🔊 **Speech Output**
  - Converts recognized signs into spoken audio for easier communication.

- 🌍 **Multi-Language Support**
  - Supports **English** and **Tamil** for broader accessibility.

- 🧠 **AI-Powered Assistance**
  - Uses **Google Gemini API** for smart interpretation and language processing.

- 🧍 **3D Interactive Sign Avatar**
  - Displays animated sign language using a 3D avatar system.

- 🎨 **Modern Interactive UI**
  - Built with a clean and accessible interface for real-time use.

---

## 🚀 Problem Statement

Communication between sign language users and non-signers is often difficult in everyday life such as:

- Classrooms
- Hospitals
- Public services
- Interviews
- Customer support
- Emergency situations

**Sign Bridge AI** solves this by enabling:
- **Sign → Text / Speech**
- **Text → Sign Animation using a human sign video system powered by a large sign avatar dataset**

This creates a **two-way communication bridge**.

---

## 💡 Solution Overview

BridgeTalk AI acts as a **real-time accessibility assistant**:

1. User performs a sign in front of the webcam  
2. AI recognizes the gesture  
3. Recognized output is shown as text  
4. Text can be converted into speech  
5. Typed text from another user is sent to the Sign Avatar server  
6. The avatar displays the corresponding sign animation  

This allows **bidirectional communication** between:
- Deaf / hard-of-hearing users
- Non-signers
- Teachers / students
- Doctors / patients
- Interviewers / candidates

---

## 🛠️ Tech Stack

### Frontend
- **Next.js**
- **React.js**
- **Tailwind CSS**
- **Three.js**
- **React Three Fiber**
- **React Three Drei**

### AI / Backend
- **Google Gemini API**
- **Python (Text-to-Sign Server)**
- **Sign Avatar Dataset (.pkl based animation system)**

### State / Utilities
- **Zustand**
- **Webcam / Media APIs**
- **Text-to-Speech Integration**

---

## 📂 Project Structure

```bash
hacker/
│
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   ├── ai/                         # AI-based sign processing
│   │   │   ├── gemini-sign-language/       # Real-time sign recognition API
│   │   │   ├── gemini-sign-suggestions/    # Text-to-sign suggestions
│   │   │   └── lovo-tts/                   # Text-to-speech integration
│   │   └── page.js                         # Main application page
│   │
│   ├── components/
│   │   ├── CVCamera.jsx                    # Webcam sign recognition
│   │   ├── MessagesList.jsx                # Chat / output display
│   │   ├── BoardSettings.jsx               # App controls and settings
│   │   └── Experience.jsx                  # 3D environment / scene
│   │
│   ├── services/                           # Gemini API & AI services
│   ├── utils/                              # Helper utilities
│   └── hooks/
│       └── useAITeacher.js                 # State management / AI logic
│
├── scripts/
│   ├── download_models.py
│   ├── inspect_smplx.py
│   ├── install_openh264.py
│
├── public/
├── App.tsx
└── README.md
