# 🧪 TestGenius - AI-Powered Testing Platform

## ✨ Key Features

### 🧠 **AI Test Generation**
- **Smart DOM Analysis** – Uses Google Gemini AI to analyze website structure
- **Intelligent Test Creation** – Generates comprehensive Playwright test scripts
- **Interactive Element Detection** – Identifies buttons, forms, links, and user interactions
- **Scenario-Based Testing** – Creates realistic user journey tests

### 🎯 **Advanced Test Execution**
- **Playwright Browser Automation** – Supports Chromium, Firefox, and Safari
- **Real-time Test Monitoring** – Live execution status and progress tracking
- **Detailed Test Reporting** – Pass/fail/skip breakdown with execution times
- **AI-Powered Failure Analysis** – Intelligent error diagnosis and suggestions

### 📊 **Comprehensive Dashboard**
- **User Authentication** – Firebase-based secure user management
- **Test History Tracking** – Complete test execution timeline
- **Visual Results Display** – Interactive test results with filtering
- **Performance Metrics** – Test execution analytics and trends

### 🖼️ **Screenshot & Media Capture**
- **Automated Screenshots** – Before/after test execution captures
- **Failure Evidence** – Visual proof of test failures and errors
- **Video Recording** – Full test execution recordings (configurable)
- **Media Management** – Organized storage and retrieval system

### 🌐 **Cloud-Ready Architecture**
- **Multi-Platform Deployment** – Vercel, Railway, Heroku, Docker support
- **Scalable Backend** – Node.js + Express with proper error handling
- **Database Integration** – Firebase Firestore for data persistence
- **Production Optimized** – Built-in health checks and monitoring

---

## 🛠️ Technology Stack

### Frontend Stack
- **React 18** with TypeScript for type safety
- **Tailwind CSS** for modern, responsive UI design
- **Vite** for fast development and optimized builds
- **Lucide React** for consistent iconography
- **Firebase SDK** for authentication and data management

### Backend Stack
- **Node.js + Express** for robust API development
- **Playwright** for browser automation and testing
- **Google Generative AI (Gemini)** for intelligent test generation
- **Cheerio** for HTML parsing and DOM analysis
- **Firebase Admin** for server-side user management

### Development Tools
- **ESLint + TypeScript** for code quality and type checking
- **Concurrently** for parallel frontend/backend development
- **Nodemon** for automatic server reloading
- **PostCSS + Autoprefixer** for CSS processing

### Cloud & Deployment
- **Docker** containerization for consistent deployments
- **Vercel** for frontend hosting and serverless functions
- **Railway** for full-stack deployment
- **Netlify** for static site hosting with edge functions
- **Firebase Firestore** for real-time database
- **Firebase Authentication** for user management

---


### Quick Demo Flow
1. **Sign up/Login** with Firebase authentication
2. **Enter any website URL** (try: https://example.com)
3. **Select test type** (Basic, Forms, Responsive, Comprehensive)
4. **Choose language** (JavaScript or Python)
5. **Generate AI tests** with Google Gemini
6. **Execute tests** with Playwright automation
7. **View results** with screenshots and AI analysis

---

## 🏃‍♂️ Quick Start

### Prerequisites
- **Node.js** 18+ and npm
- **Git** for version control
- **Google Gemini API Key** ([Get one here](https://ai.google.dev/))
- **Firebase Project** ([Firebase Console](https://console.firebase.google.com/))

### 1. Clone and Setup
```bash
git clone https://github.com/your-username/TestGenius.git
cd TestGenius/project
npm install
```

### 2. Environment Configuration
Create a `.env` file in the `project` directory:
```env
# Required: Google Gemini AI API Key
GEMINI_API_KEY=your_gemini_api_key_here

# Required: Firebase Configuration
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your-project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_STORAGE_BUCKET=your-project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=123456789
VITE_FIREBASE_APP_ID=1:123456789:web:abcdef123456

# Optional: Server Configuration
NODE_ENV=development
PORT=3001
DEBUG=true
```

### 3. Install Playwright Browsers
```bash
npx playwright install chromium --with-deps
```

### 4. Start Development Server
```bash
npm run dev
```
This runs both frontend (http://localhost:5173) and backend (http://localhost:3001) concurrently.

### 5. Build for Production
```bash
npm run build:production
```
### Feature Completeness
- ✅ User Authentication (Firebase)
- ✅ AI Test Generation (Google Gemini)
- ✅ Test Execution (Playwright)
- ✅ Results Visualization
- ✅ Screenshot Capture
- ✅ Multi-language Support
- ✅ Cloud Deployment
- ✅ Responsive Design

---


