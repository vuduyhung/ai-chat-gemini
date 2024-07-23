# Project Name

This is the README file for the **AI Chat Gemini** monorepo.

Based on this youtube tutorial:
[![Lama Dev](https://img.youtube.com/vi/8iAQ1h30n5I/0.jpg)](https://www.youtube.com/watch?v=8iAQ1h30n5I)

## Technology Stacks

This project is built using a variety of technologies and frameworks to provide a robust and scalable AI chat solution. Here's a breakdown of the main technologies used:

### Frontend

- **React 19**: A JavaScript library for building user interfaces.
- **Vite**: A modern frontend build tool that significantly improves the development experience.
- **CSS**: For styling components.

### Backend

- **Node.js**: Current running version is `20.15.0`.
- **Express**: A minimal and flexible Node.js web application framework.

### AI

- **Gemini API**: https://ai.google.dev/gemini-api

### Database

- **MongoDB**: A NoSQL database used to store chat and user data.

### Code Quality Tools

- **ESLint**: A static code analysis tool for identifying problematic patterns in JavaScript code.
- **Prettier**: An opinionated code formatter that supports many languages and integrates with most editors.

This stack was chosen for its flexibility, performance, and the strong community support each technology receives.

## Description

The **AI Chat Gemini** is a monorepo project built with React. It aims to provide an AI-powered chatbot called Gemini.

## Features

- AI chatbot powered by Gemini with real-time streaming, chat image recognition
- Clerk authentication
- React css animation
- React Image upload & optimization by ImageKit.io
- React 19 React Query
- Mongo db with Mongoose
- React-based frontend
- Node Express backend

## Installation

To install and run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/vuduyhung/ai-chat-gemini.git`
2. Navigate to the backend & client project directories, then install dependencies with `-f` flag: `npm install -f`. Because we use react 19, which is currently unstable
3. First start the backend development server: `npm start`. Then start the client development: `npm run dev`

## Usage

Once the both backend server & client are running, you can access the application by opening your browser and navigating to `http://localhost:5172`.


## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or support, please contact the project maintainer at [email@example.com](mailto:email@example.com).
