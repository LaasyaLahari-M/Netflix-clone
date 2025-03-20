# Netflix Clone

This project is a Netflix clone built with HTML, CSS, and JavaScript. It includes user authentication using Firebase and dynamic movie fetching from the TMDb API.

## Features

- 🔐 **User Authentication**: Sign in with Google or email/password via Firebase
- 🎬 **Movie Listings**: Fetches popular and trending movies from TMDb API
- 🔍 **Search Functionality**: Users can search for specific movies
- 🚀 **Firebase Hosting**: Fully deployed on Firebase

## Setup Instructions

### 1️⃣ Install Firebase CLI (if not installed)

```sh
npm install -g firebase-tools
```

### 2️⃣ Clone this repository

```sh
git clone https://github.com/yourusername/netflix-clone.git
cd netflix-clone
```

### 3️⃣ Configure Firebase

1. Create a **Firebase Project** at [Firebase Console](https://console.firebase.google.com/).
2. Enable **Authentication (Google & Email/Password)**.
3. Enable **Firestore Database**.
4. Enable **Hosting**.
5. Copy your Firebase credentials into `script.js`:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_FIREBASE_API_KEY",
  authDomain: "YOUR_FIREBASE_AUTH_DOMAIN",
  projectId: "YOUR_FIREBASE_PROJECT_ID",
  storageBucket: "YOUR_FIREBASE_STORAGE_BUCKET",
  messagingSenderId: "YOUR_FIREBASE_MESSAGING_SENDER_ID",
  appId: "YOUR_FIREBASE_APP_ID"
};
```

### 4️⃣ Get a TMDb API Key

1. Go to [TMDb API](https://www.themoviedb.org/documentation/api).
2. Sign up and get an API key.
3. Replace `YOUR_TMDB_API_KEY` in `script.js`:

```javascript
const TMDB_API_KEY = "YOUR_TMDB_API_KEY";
```

### 5️⃣ Deploy on Firebase Hosting

```sh
firebase login
firebase init hosting
firebase deploy
```

Your site will be live at: `https://your-app-name.web.app`

## Usage

- **Sign in to access movie search**
- **Use the search bar to find movies**
- **Movies will be dynamically displayed**

## Technologies Used

- HTML, CSS, JavaScript
- Firebase Authentication & Firestore
- Firebase Hosting
- TMDb API

## License

This project is for educational purposes only. Netflix and TMDb trademarks and content belong to their respective owners.

---

🔧 Need help? Feel free to ask! 🚀 Contact : 21eg105j22\@anurag.edu.in
