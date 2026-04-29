# Custom Sounds

<div align="center">

![Custom Sounds Logo](assets/logo.jpg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Appwrite](https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white)](https://appwrite.io/)

A professional music player and sound management platform built for creators.

[View Demo](https://soundibeat.netlify.app/) • [Report Bug](https://github.com/rajjitlaishram/custom-sounds/issues) • [Request Feature](https://github.com/rajjitlaishram/custom-sounds/issues)

</div>

---

## 🚀 Overview

**Custom Sounds** is a modern, high-performance music player application designed to provide a seamless audio experience. Originally developed for client use, it has been refined into a personal project showcasing a robust integration of React, WaveSurfer.js for audio visualization, and Appwrite as a comprehensive backend solution.

## ✨ Features

- 🔐 **Secure Authentication**: User registration and login systems powered by Appwrite Auth.
- 🎵 **Dynamic Waveforms**: Real-time audio visualization using WaveSurfer.js for an interactive playback experience.
- ☁️ **Cloud Storage**: Seamless audio file management and storage via Appwrite Storage.
- 📂 **Sound Management**: Easily upload, organize, and stream custom sounds.
- 📱 **Responsive Design**: Fully optimized for mobile, tablet, and desktop using Tailwind CSS and Material UI.
- ⚡ **Lightning Fast**: Built on Vite for a superior development experience and optimized production builds.

## 🛠️ Tech Stack

- **Frontend**: [React](https://reactjs.org/) (v18), [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/), [Material UI](https://mui.com/)
- **Backend**: [Appwrite](https://appwrite.io/) (Authentication, Database, Storage)
- **Audio Visualization**: [WaveSurfer.js](https://wavesurfer-js.org/)
- **Routing**: [React Router DOM](https://reactrouter.com/)
- **Deployment**: [Netlify](https://www.netlify.com/)

## ⚙️ Setup & Installation

### Prerequisites

- Node.js (v16.x or higher)
- Appwrite Instance (Cloud or Self-hosted)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rajjitlai/Custom_Sounds.git
   cd custom-sounds
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add your Appwrite credentials:
   ```env
   VITE_APPWRITE_ENDPOINT="your_appwrite_endpoint"
   VITE_APPWRITE_PROJECT_ID="your_project_id"
   VITE_APPWRITE_DATABASE="your_database_id"
   VITE_APPWRITE_COLLECTION="your_collection_id"
   VITE_APPWRITE_STORAGE_BUCKET="your_bucket_id"
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
Developed with ❤️ by <a href="https://github.com/rajjitlaishram">Rajjit Laishram</a>
</div>
