# Interview IQ 🎯
### AI-Powered Mock Interview Platform

Interview IQ is an AI-powered mock interview platform designed to help candidates prepare for technical interviews through intelligent interview simulations, real-time interaction, and personalized practice.

The platform provides an interactive environment where users can practice interviews, improve their technical knowledge, and build confidence before facing real-world interviews.

## ✨ Features

- **AI-Powered Interviews:** Generate intelligent interview interactions using AI.
- **Mock Interview Practice:** Practice interview questions in an interactive environment.
- **Speech Interaction:** Use browser speech capabilities for voice-based interaction.
- **Real-Time Responses:** Interact with the interview system dynamically.
- **User-Friendly Interface:** Clean and responsive interface for a smooth experience.
- **Payment Integration:** Razorpay integration in test mode.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, JavaScript, HTML, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI Integration | OpenRouter API |
| Voice Integration | Web Speech API |
| Payment Gateway | Razorpay |
| Development Tools | Git, GitHub, VS Code, Postman |

## 📁 Project Structure

```text
Interview-IQ/
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── public/
│   ├── index.js
│   └── package.json
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Somya5662/Interview-IQ.git
```

### 2. Navigate to the Project

```bash
cd Interview-IQ
```

### 3. Install Frontend Dependencies

```bash
cd client
npm install
```

### 4. Install Backend Dependencies

Open another terminal:

```bash
cd server
npm install
```

### 5. Configure Environment Variables

Create `.env` files in the client and server directories.

Add the environment variables required by your application, including your database connection string, AI API key, and payment gateway credentials.

Do not upload environment files or secret API keys to GitHub.

### 6. Run the Application

Start the backend:

```bash
cd server
npm start
```

Start the frontend in another terminal:

```bash
cd client
npm run dev
```

Open the local URL displayed by Vite in your browser.

*Note: Use the scripts defined in your respective package.json files if your start commands differ.*

## 🔐 Security

- Environment variables are used to protect sensitive credentials.
- API keys and database credentials should never be committed to GitHub.
- Razorpay is configured for test-mode integration.

## 🚀 Future Improvements

- Advanced interview performance analytics.
- Personalized feedback and improvement suggestions.
- More interview categories and difficulty levels.
- Enhanced interview evaluation and reporting.

## 👩‍💻 Author

**Somya Singh**

- GitHub: [Somya5662](https://github.com/Somya5662)
- Project Repository: [Interview IQ](https://github.com/Somya5662/Interview-IQ)

## 📄 License

This project is available for educational and learning purposes. Add a formal license if you intend to distribute it under specific reuse terms.
