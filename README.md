# React Quiz App

<div align="center">

![React](https://img.shields.io/badge/React-16.12-61DAFB?style=for-the-badge&logo=react)
![Redux](https://img.shields.io/badge/Redux-4.0-764ABC?style=for-the-badge&logo=redux)
![React Router](https://img.shields.io/badge/React_Router-5.1-CA4245?style=for-the-badge&logo=react-router)
![Firebase](https://img.shields.io/badge/Firebase-Hosting-FFCA28?style=for-the-badge&logo=firebase)

</div>

## Overview

A full-featured quiz application built with React and Redux. Allows users to take quizzes, view results, and create custom quizzes with authentication. Demonstrates Redux state management patterns and Firebase integration.

## Key Features

- **Take Quizzes**: Interactive quiz interface with real-time feedback
- **Create Quizzes**: Authenticated users can build custom quizzes with multiple questions
- **Authentication**: Firebase-based login/logout with protected routes
- **Results Tracking**: View quiz scores and review answers
- **Responsive Design**: Mobile-friendly UI with custom CSS modules

## Tech Stack

React 16.12, Redux 4.0, Redux Thunk 2.3, React Router 5.1, Axios, Firebase Hosting, Create React App

## Architecture

Classic Redux architecture with action creators, reducers, and thunks for async operations. Three main state slices (quiz, create, auth) combined in root reducer. React Router handles navigation with protected routes based on authentication state. Firebase hosts the production build with SPA rewrite rules.

## Prerequisites

- Node.js: `12.x` or higher

## Installation

```bash
git clone https://github.com/maxgalchenko/React-quiz.git
cd React-quiz
npm install
```

## Quick Start

```bash
npm start
# Open http://localhost:3000
```

## Available Scripts

- `npm start` – Runs the app in development mode on port 3000
- `npm run build` – Creates an optimized production build
- `npm test` – Launches Jest test runner in watch mode

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
