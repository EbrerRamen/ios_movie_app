# 🎬 Movie Explorer — iOS App

Movie Explorer is a sleek and modern iOS app built with **React Native**, **Expo**, and **Appwrite**, designed for movie lovers who want to stay up to date with the latest and trending films. The app fetches real-time movie data using the **TMDB (The Movie Database) API**, providing an intuitive experience to explore, search, and view detailed movie information.

---

## 📸 App Demo

<p align="center">
  <img src="./assets/demo1.jfif" width="200"/>
  <img src="./assets/demo2.png" width="200"/>
  <img src="./assets/demo3.png" width="200"/>
  <img src="./assets/demo4.png" width="200"/>
</p>

---
## 🚀 Features

### 🆕 Latest Movies
- Displays the **latest released movies** by default on the home screen.
- Automatically updates to show new releases fetched from TMDB.

### 🔍 Search Movies
- Search for any movie by title.
- Instantly view search results with smooth UI updates.

### 🔥 Trending Movies
- See what’s **trending inside the app** — movies that are most searched by users.
- Powered by **Appwrite** backend to track and rank popular searches.

### 🎥 Movie Details
Tap on any movie to view comprehensive details including:
- 🖼️ **Movie Poster**
- 🎬 **Title**
- 📅 **Release Year**
- ⏱️ **Duration**
- ⭐ **Rating**
- 📝 **Overview**
- 🎭 **Genre**
- 💰 **Budget & Revenue**
- 🏢 **Production Companies**

All information is dynamically fetched from the **TMDB API**.

---

## 🧰 Tech Stack

| Technology | Description |
|-------------|-------------|
| **React Native** | Framework for building native apps using React. |
| **Expo** | Toolchain for developing and deploying React Native apps easily. |
| **Appwrite** | Backend as a Service (BaaS) for managing trending search data. |
| **TMDB API** | Source for all movie data, posters, and metadata. |

---

## 🧑‍💻 Setup & Installation

### Prerequisites
- Node.js and npm/yarn installed
- Expo CLI installed (`npm install -g expo-cli`)
- TMDB API key
- Appwrite project setup

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ebrer/movie-explorer.git
   cd movie-explorer
   ```
2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Add environtment variables**
   Create a .env file in the project root:
   ```bash
   EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_appwrite_database_id
   EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```
4. **Run the app**
   ```bash
   npx expo start
   ```
   
---

## 📺 Demo Source
This project was inspired by and built following this YouTube tutorial:  
🎥 [Build a Movie App with React Native and TMDB API](https://youtu.be/f8Z9JyB2EIE?si=L7rAf63ULZ0H7FzQ)

---

## 🏗️ Future Improvements  
- Add "Add to Saved" feature.  
- Implement authentication with Appwrite.  
- Support for TV shows and multi-language content.  
- Profile management.  

---

## 💡 Credits
- **TMDB API** for movie data  
- **Appwrite** for backend and database management  
- **Expo** for rapid iOS development  
- **YouTube Tutorial by JavaScript Mastery**  



