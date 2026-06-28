# 🎵 Spotify Clone

A modern, responsive, and feature-rich **Spotify Clone** built with **React.js** that recreates the core experience of Spotify's web player. This project demonstrates modern frontend development practices, reusable component architecture, audio playback management, and responsive UI design.

> **Disclaimer:** This project is developed solely for educational and portfolio purposes. It is not affiliated with or endorsed by Spotify.

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Demo](#-demo)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Application Workflow](#-application-workflow)
- [Key React Concepts](#-key-react-concepts)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Learning Outcomes](#-learning-outcomes)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

# 📌 Project Overview

The Spotify Clone is a frontend music streaming application inspired by Spotify's web interface. It provides users with a clean, interactive, and responsive platform to browse songs, play music, navigate between tracks, and monitor playback progress.

The project focuses on implementing React best practices, reusable UI components, global state management, and real-time audio handling while maintaining a modern and intuitive user experience.

---

# 🚀 Demo

### Live Demo

> Add your deployed project link here.

```
<img width="1920" height="1080" alt="Screenshot 2026-06-13 081452" src="https://github.com/user-attachments/assets/0529b811-d743-495f-8fe5-d171d0c99d90" />

```

---

# ✨ Features

### 🎵 Music Playback

- Play songs
- Pause songs
- Previous track
- Next track
- Automatic track switching
- Real-time playback

### 🎧 Audio Controls

- Interactive seek bar
- Current playback time
- Total song duration
- Smooth audio transitions

### 🎨 User Interface

- Spotify-inspired layout
- Responsive design
- Modern music player
- Dynamic song cards
- Album display
- Sidebar navigation

### ⚛ React Functionality

- Functional Components
- React Hooks
- Context API
- Component Reusability
- Dynamic Rendering
- State Management

---

# 🛠 Technology Stack

| Category | Technology |
|----------|------------|
| Frontend | React.js |
| Language | JavaScript (ES6+) |
| Styling | CSS3 |
| Markup | HTML5 |
| Build Tool | Vite |
| State Management | React Context API |
| Version Control | Git |
| Repository | GitHub |

---

# 📂 Project Structure

```
spotify-clone
│
├── public
│
├── src
│   │
│   ├── assets
│   │   ├── audio
│   │   ├── images
│   │   ├── icons
│   │   └── assets.js
│   │
│   ├── components
│   │   ├── Navbar
│   │   ├── Sidebar
│   │   ├── Player
│   │   ├── AlbumItem
│   │   ├── SongItem
│   │   └── Display
│   │
│   ├── context
│   │   └── PlayerContext.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

# ⚙ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/spotify-clone.git
```

### Navigate to the project

```bash
cd spotify-clone
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

### Open in Browser

```
http://localhost:5173
```

---

# ▶ Usage

1. Launch the application.
2. Browse available songs and albums.
3. Select any song to begin playback.
4. Use player controls to:
   - Play
   - Pause
   - Next
   - Previous
5. Drag the seek bar to change playback position.

---

# 🔄 Application Workflow

```
Application Starts
        │
        ▼
Load Song Data
        │
        ▼
Display Albums & Songs
        │
        ▼
User Selects Song
        │
        ▼
Update Current Track
        │
        ▼
Play Audio
        │
        ▼
Update Progress Bar
        │
        ▼
Track Ends
        │
        ▼
Play Next Song
```

---

# ⚛ Key React Concepts

## React Hooks

### useState

Used for:

- Current song
- Playback state
- Track information

### useEffect

Used for:

- Audio synchronization
- Progress updates
- Player initialization

### useRef

Used for:

- Audio element
- Progress bar
- Seek bar

### useContext

Used for:

- Global player state
- Music controls
- Current track information

---

# 🎵 Core Functionalities

## Music Player

✔ Play Song

✔ Pause Song

✔ Previous Song

✔ Next Song

✔ Seek Song

✔ Display Duration

✔ Playback Progress

---

## Global State Management

The project uses **React Context API** to avoid prop drilling and manage application-wide player state.

Managed data includes:

- Current track
- Audio reference
- Playback status
- Progress
- Duration
- Player controls

---

# 📱 Responsive Design

Optimized for:

- Desktop
- Laptop
- Tablet
- Mobile

---

# 📸 Screenshots

## Home Page

```
<img width="1920" height="1080" alt="Screenshot 2026-06-13 092126" src="https://github.com/user-attachments/assets/e78131f5-678d-4c2a-b4ea-9a4a4b0d640d" />

```

---

## Music Player

```
<img width="1920" height="1080" alt="Screenshot 2026-06-13 092126" src="https://github.com/user-attachments/assets/c9e9e61e-d6bb-49cb-beb7-de9ecc5af6cb" />

```

---

## Sidebar

```
<img width="1920" height="1080" alt="Screenshot 2026-06-13 081452" src="https://github.com/user-attachments/assets/b4524d9d-7e83-4761-a1a1-7a8d8ac649c7" />

```

---

# 🚀 Future Enhancements

- User Authentication
- Spotify API Integration
- Playlist Creation
- Search Functionality
- Favorites
- Recently Played
- Volume Control
- Shuffle Mode
- Repeat Mode
- Lyrics Support
- Backend Integration
- Database Support
- User Profiles

---

# 📚 Learning Outcomes

This project strengthened understanding of:

- React Component Architecture
- React Hooks
- Context API
- Audio Handling in React
- Responsive Design
- State Management
- Component Reusability
- JavaScript ES6+
- Git & GitHub Workflow

---

# 🤝 Contributing

Contributions are welcome.

### Steps

```bash
# Fork Repository

# Clone Repository
git clone https://github.com/your-username/spotify-clone.git

# Create Branch
git checkout -b feature/feature-name

# Commit Changes
git commit -m "Add new feature"

# Push Branch
git push origin feature/feature-name
```

Finally, create a Pull Request.

---

# 📄 License

This project is intended for **educational and portfolio purposes only**.

All product names, logos, trademarks, and music assets belong to their respective owners.

---

# 👩‍💻 Author

**Saloni Paswan**

**GitHub:** https://github.com/salonipaswan22



---

# 🙏 Acknowledgements

- React.js
- Vite
- Spotify (UI Inspiration)
- Open Source Community

---

<div align="center">

### ⭐ If you found this project helpful, please consider giving it a Star!

**Made with ❤️ using React.js**

</div>
