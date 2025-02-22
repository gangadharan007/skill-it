# Skill It - Revolutionizing Career Discovery & Skill Exchange

## 🚀 Overview
Skill It is an AI-driven career discovery and skill exchange platform designed to empower individuals with the right tools for their professional growth. Our intuitive platform leverages cutting-edge AI to provide personalized career insights, real-time peer-to-peer skill exchange, and an interactive voice-based AI chatbot for guidance. Skill It isn’t just an app—it’s a movement towards redefining the future of career development.

## 🔥 Key Features
- **AI-Powered Career Assessment** – A 20-question interactive quiz that provides deep insights into career paths based on user responses.
- **Skill Exchange Hub** – Seamless user-to-user skill-sharing network, fostering a collaborative learning environment.
- **Voice-Enabled AI Chatbot** – An intelligent chatbot offering real-time career guidance and support.
- **Immersive UI/UX** – A sleek, navy-blue themed professional design with a technical background for a futuristic experience.
- **Seamless Firebase Integration** – Secure authentication, real-time database, and scalable hosting.

## 📌 Installation & Setup
### Prerequisites
- Install [Node.js](https://nodejs.org/)
- Install [Firebase CLI](https://firebase.google.com/docs/cli)
- Set up a Firebase project

### Clone the Repository
```sh
git clone https://github.com/your-repo/skill-it.git
cd skill-it
```

### Install Dependencies
```sh
npm install
```

### Firebase Configuration
1. Create a `.env` file and add your Firebase credentials:
   ```sh
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```
2. Initialize Firebase:
   ```sh
   firebase init
   ```
   - Select **Hosting** and choose your Firebase project.
   - Set the public directory to `public` or the correct path containing `index.html`.
   - Enable **Single Page App (SPA) support**.

### Running Locally
```sh
firebase serve
```
Visit `http://localhost:5000` to explore the platform.

### 🚀 Deployment
```sh
firebase deploy
```
Your project will be live at `https://skill-it.web.app`.

## 🎯 How It Works
1. **Discover Your Passion** – Take the AI-powered quiz and unlock tailored career insights.
2. **Learn & Share Skills** – Connect with peers for hands-on learning and knowledge exchange.
3. **AI-Driven Guidance** – Engage with the voice chatbot to get career advice and industry insights.

## 💡 Why Skill It Stands Out
- **Data-Driven Personalization** – Every interaction refines the recommendations.
- **Global Skill Network** – Learn from experts and contribute your knowledge.
- **AI & Real-Time Collaboration** – A tech-first approach to career development.

## 🛠️ Contributing
We welcome contributors to enhance the platform! Follow these steps:
1. Fork the repository.
2. Create a feature branch (`feature-branch`).
3. Commit your changes (`git commit -m 'New Feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

## 📜 License
Licensed under the MIT License.

---
For any inquiries, reach out at **support@skillit.com** or open an issue on GitHub. Let’s revolutionize career discovery together! 🚀
