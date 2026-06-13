🤟 Sign Bridge AI – Your Smart Real-Time Sign Language Communication Companion

Transform everyday communication with Sign Bridge AI – an AI-powered platform that bridges the gap between deaf or hard-of-hearing individuals and non-signers through real-time sign recognition, text-to-sign human video generation, speech output, and multilingual support.

⸻
✨ Key Features

Core Functionality

🎥 Real-Time Sign Recognition

Detects and interprets sign language gestures using AI + live webcam input.
Recognizes signs in real time and converts them into meaningful text output.

🔊 Sign-to-Text & Speech

Converts recognized sign language into instant text and spoken audio output using the Google Gemini API Key.
Helps non-signers understand sign language quickly and naturally through AI-powered interpretation.

🎬 Text-to-Sign Human Video Output

Converts typed text into realistic human sign language video output using a separate Sign Avatar server.
Powered by a large 12GB sign avatar dataset, enabling more natural and expressive sign communication.

🔄 Two-Way Communication

Enables complete bidirectional communication between sign language users and non-signers in real time.

⸻

Accessibility & Interaction

🌍 Multi-Language Support

Supports English and Tamil for broader accessibility and inclusive communication across different users.

🧍 3D Interactive Sign Avatar

Displays animated sign language using a 3D avatar-based system.
Provides a more engaging and understandable visual communication experience.

🎨 Modern Interactive UI

Built with a clean, accessible, and responsive interface for real-time usability.
Designed for smooth interaction in classrooms, hospitals, public services, and workplaces.
⸻

🚀 Problem Statement

Communication between sign language users and non-signers is often difficult in everyday life such as:
	•	Classrooms
	•	Hospitals
	•	Public services
	•	Interviews
	•	Customer support
	•	Emergency situations

Without interpreters, communication can become slow, expensive, or inaccessible.

Sign Bridge AI solves this by enabling:
	•	Sign → Text / Speech using Google Gemini API Key
	•	Text → Sign Human Video Output using a Sign Avatar system powered by a 12GB dataset

This creates a complete two-way communication bridge.

⸻

💡 Solution Overview

Sign Bridge AI acts as a real-time accessibility assistant:
	•	User performs a sign in front of the webcam
	•	AI recognizes the gesture in real time
	•	Recognized output is processed using the Google Gemini API Key
	•	The output is shown as text
	•	Text is converted into speech for non-signers
	•	Typed text from another user is sent to the Sign Avatar server
	•	The avatar displays the corresponding human sign language video output using a 12GB sign avatar dataset

This allows bidirectional communication between:
	•	Deaf / hard-of-hearing users
	•	Non-signers
	•	Teachers / students
	•	Doctors / patients
	•	Interviewers / candidates

🚀 Getting Started

Installation Steps

1. Clone the Repository



If you have forked the repository, replace YOUR_GITHUB_USERNAME with your GitHub username and run:
	git clone https://github.com/YOUR_GITHUB_USERNAME/hacker.git
	
Then, navigate to the project folder:
	cd hacker


2. Set Up Development Environment

Install dependencies:
	npm install
	
Run the frontend:
	npm run dev

3. Set Up Sign Avatar Server

Run the Python-based sign animation / human video server:
	cd sign-avatar-server
	pip install -r requirements.txt
	python server.py
	

4. Configure Gemini API Key

Create a .env.local file in the project root and add your Google Gemini API Key:
	GEMINI_API_KEY=your_gemini_api_key_here
	This API key is used for:
	•	Sign-to-Text processing
	•	Sign-to-Speech output
	•	Smart AI-based language interpretation

5. Open the Application

Open your browser and go to:
	http://localhost:3000

🧩 Using Sign Bridge AI

🎥 Real-Time Sign Recognition
	•	Open the app in your browser
	•	Allow webcam access
	•	Perform sign language gestures in front of the camera
	•	The system detects and interprets the signs in real time
	•	Output is displayed as text and can be converted into speech using the Google Gemini API Key

⸻

🎬 Text-to-Sign Human Video Communication
	•	Enter text into the input field
	•	The text is sent to the Sign Avatar server
	•	The system uses the 12GB sign avatar dataset
	•	The avatar generates the corresponding human sign language video output
	•	Enables non-signers to communicate visually with sign language users

⸻

🌍 Multilingual Communication
	•	Choose supported languages such as English or Tamil
	•	Improve accessibility and usability for a wider audience

⸻

🛠 Technical Stack

Frontend Technologies
	•	Next.js for application structure
	•	React.js for dynamic UI components
	•	Tailwind CSS for modern responsive styling
	•	Three.js for 3D rendering
	•	React Three Fiber for 3D integration in React
	•	React Three Drei for 3D utilities and helpers

⸻

AI / Backend
	•	Google Gemini API Key for Sign-to-Text, Sign-to-Speech, and AI-powered interpretation
	•	Python for the Text-to-Sign backend server
	•	Sign Avatar System for human sign language video generation
	•	12GB Sign Avatar Dataset for realistic sign animation / human sign output
	•	Webcam / Media APIs for live video input
	•	Text-to-Speech Integration for voice output

⸻
State / Utilities
	•	Zustand for lightweight state management
	•	Custom utility services for API handling and communication flow


🤝 Contributing

We love your input! Want to contribute? Here’s how:
	•	Fork the repository
	•	Create your feature branch
	•	Commit your changes
	•	Submit a pull request

⸻

👨‍💻 Contributors:
	•	@afra245
	•	@abhienayaSri9509
	•	@Sanjay-2806

⸻

📜 License

This project is licensed under the [MIT License](LICENSE).

⸻

❤️ Made with Love by Team Apple
