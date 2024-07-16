# Exposio

Welcome to Exposio, a modern social media platform designed to enhance your social experience. With a sleek interface and powerful features, Exposio offers a seamless way to connect and share with others.

## 📋 Table of Contents

- [Introduction](#introduction)
- [Live Demo](#live-demo)
- [Testing User Credentials](#testing-user-credentials)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Quick Start](#quick-start)
- [Acknowledgements](#acknowledgements)

## 🤖 Introduction

Exposio is built to provide an intuitive and engaging social media experience. Whether you're exploring new content or sharing your own, Exposio's robust authentication system and efficient data fetching ensure a smooth user journey.

## 🌐 Live Demo

Check out the live demo of Exposio: [Exposio Live Demo](https://exposio.vercel.app)

## 🛠️ Testing User Credentials

To explore the features of Exposio without creating an account, use the following test credentials:

- **Username**: test@test.com
- **Password**: test123456

## ⚙️ Tech Stack

- **React.js**: A JavaScript library for building user interfaces
- **Appwrite**: Backend as a Service for authentication, database, and file storage
- **React Query**: Efficient data fetching and caching
- **TypeScript**: Typed JavaScript for better development experience
- **Shadcn**: Component library
- **Tailwind CSS**: Utility-first CSS framework

## 🔋 Features

- **Authentication System**: Secure and private user authentication
- **Explore Page**: Discover new posts and featured creators
- **Like and Save Functionality**: Manage your liked and saved posts
- **Detailed Post Page**: Immersive post viewing with related content suggestions
- **Profile Page**: View and edit your profile and liked posts
- **Browse Other Users**: Explore other users' profiles and posts
- **Create Post Page**: User-friendly post creation with drag-drop functionality
- **Edit Post Functionality**: Edit your posts at any time
- **Responsive UI with Bottom Bar**: Mobile-friendly navigation
- **React Query Integration**: Auto caching, parallel queries, first-class mutations
- **Appwrite Integration**: Streamlined backend with authentication, database, and storage

## 🤸 Quick Start

Follow these steps to set up Exposio locally on your machine.

### Prerequisites

Ensure you have the following installed:

- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/yourusername/exposio.git
cd exposio
```

### Installation

Install the project dependencies using npm:

```bash
npm install
```

### Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io).

### Running the Project

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 🎓 Acknowledgements

This project was created with guidance from the [JavaScript Mastery](https://www.youtube.com/c/JavaScriptMastery) tutorial.
