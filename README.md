# 🤖 Email Generator - AI-Powered Email Reply Assistant

[![Java](https://img.shields.io/badge/Java-21-orange.svg)](https://www.oracle.com/java/)
[![React](https://img.shields.io/badge/React-19.1.1-blue.svg)](https://reactjs.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.4-green.svg)](https://spring.io/projects/spring-boot)

> Transform your email responses with intelligent AI-powered suggestions. Generate professional, contextual replies with customizable tones instantly.

## 📋 Table of Contents

- [🚀 Description](#-description)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📦 Installation](#-installation)
- [🎯 Usage](#-usage)
- [📞 Contact](#-contact)

## 🚀 Description

**Email Generator** is a full-stack web application that leverages artificial intelligence to help users generate smart, contextual email replies. Whether you're responding to business inquiries, customer support tickets, or personal emails, this tool analyzes the original email content and generates appropriate responses based on your selected tone and style.

The application consists of a modern React frontend with Material-UI components and a robust Spring Boot backend that processes email content and generates intelligent responses using AI algorithms.

## ✨ Features

- 🧠 **AI-Powered Generation** - Intelligent email reply generation based on context
- 🎨 **Customizable Tone** - Choose from multiple response tones (Professional, Friendly, Formal, etc.)
- ⚡ **Real-time Processing** - Instant email reply generation with loading indicators
- 📱 **Responsive Design** - Modern, mobile-friendly interface built with Material-UI
- 🔄 **Cross-Origin Support** - Seamless frontend-backend communication
- 🛡️ **Error Handling** - Comprehensive error management and user feedback
- 🎯 **User-Friendly Interface** - Clean, intuitive design for effortless interaction

## 🛠️ Tech Stack

### Frontend
- **React** 19.1.1 - Modern JavaScript library for building user interfaces
- **Material-UI (MUI)** 7.3.1 - React component library for faster development
- **Vite** 7.1.2 - Fast build tool and development server
- **Axios** 1.11.0 - HTTP client for API communication
- **ESLint** - Code linting and formatting

### Backend
- **Java** 21 - Latest LTS version of Java
- **Spring Boot** 3.5.4 - Production-ready framework for Java applications
- **Spring Web** - RESTful web services
- **Spring WebFlux** - Reactive programming support
- **Lombok** - Reduce boilerplate code
- **Maven** - Dependency management and build tool

### Development Tools
- **VS Code** - Primary development environment
- **Git** - Version control
- **npm** - Package management for frontend
- **Maven Wrapper** - Consistent Maven builds

## 📦 Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **Java 21** or higher
- **Node.js** 18+ and **npm**
- **Git**

### Backend Setup (Spring Boot)

1. **Clone the repository**
   ```bash
   git clone https://github.com/strange8969/Email-Generator-Full-Stack.git
   cd Email-Generator-Full-Stack/email-generator-spring-boot
   ```

2. **Build and run the Spring Boot application**
   ```bash
   # Using Maven Wrapper (recommended)
   ./mvnw clean install
   ./mvnw spring-boot:run
   
   # Or using system Maven
   mvn clean install
   mvn spring-boot:run
   ```

3. **Verify backend is running**
   - The server will start on `http://localhost:8080`
   - Check the application endpoint: `http://localhost:8080/api/email/generate`

### Frontend Setup (React)

1. **Navigate to frontend directory**
   ```bash
   cd ../email-generator-react
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Access the application**
   - Frontend will be available at `http://localhost:5173`
   - The app will automatically connect to the backend API

## 🎯 Usage

### Basic Usage

1. **Start the Application**
   - Ensure both backend (port 8080) and frontend (port 5173) are running
   - Open your browser and navigate to `http://localhost:5173`

2. **Generate Email Replies**
   ```
   📧 Paste or type the original email content
   🎭 Select your preferred response tone
   ⚡ Click "Generate Reply"
   📋 Copy the generated response
   ```

3. **Example Workflow**
   ```
   Original Email: "Hi, I'm interested in your product pricing..."
   Selected Tone: "Professional"
   Generated Reply: "Thank you for your interest in our products..."
   ```

### API Endpoints

The backend exposes the following REST API:

```http
POST /api/email/generate
Content-Type: application/json

{
  "emailContent": "Original email content here",
  "tone": "professional"
}
```

**Response:**
```json
{
  "generatedReply": "AI-generated email response based on content and tone"
}
```

## 📞 Contact

**Developer:** strange8969

- 🐙 **GitHub**: [@strange8969](https://github.com/strange8969)
- 📧 **Email**: [adityaraj896919@gmail.com]
- 💼 **LinkedIn**: [[LinkedIn](https://www.linkedin.com/in/aaditya-raj-/)]

---

### 🌟 Show Your Support

If this project helped you, please consider giving it a ⭐ on GitHub!

### 🔮 Future Enhancements

- [ ] Multiple AI model support
- [ ] Email template library
- [ ] Advanced tone customization
- [ ] Email history and favorites
- [ ] Multi-language support
- [ ] Integration with email clients

---

**Built with ❤️ using React, Spring Boot, and AI**
