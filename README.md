# Email Generator Full Stack

A full-stack web application for generating professional emails using AI. Built with React (frontend) and Spring Boot (backend).

## Features
- Generate emails based on user input
- Modern React UI with Vite
- RESTful API powered by Spring Boot
- Easy to deploy and extend

## Tech Stack
- **Frontend:** React, Vite
- **Backend:** Spring Boot (Java)
- **Build Tools:** Maven

## Project Structure
```
Email-Generator-Full-Stack/
├── email-generator-react/         # Frontend (React)
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
├── email-generator-spring-boot/   # Backend (Spring Boot)
│   ├── src/
│   ├── pom.xml
│   └── ...
```

## Getting Started

### Prerequisites
- Node.js & npm
- Java 17+
- Maven

### 1. Clone the repository
```sh
git clone https://github.com/<your-username>/Email-Generator-Full-Stack.git
cd Email-Generator-Full-Stack
```

### 2. Start the Backend (Spring Boot)
```sh
cd email-generator-spring-boot
mvn spring-boot:run
```

The backend will start on `http://localhost:8080`.

### 3. Start the Frontend (React)
```sh
cd email-generator-react
npm install
npm run dev
```

The frontend will start on `http://localhost:5173` (default Vite port).

## Usage
1. Open the frontend in your browser.
2. Enter your requirements for the email.
3. Click "Generate" to receive a professional email.

## API Endpoints
- `POST /generate-email` - Generates an email based on the request body.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
