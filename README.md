# 🎵 Spotify Playlist Clone

A fully functional web-based music player inspired by Spotify's sleek interface and user experience. This project replicates the look and feel of Spotify's web player, featuring the complete **Aashiqui 2 (2013)** album with custom audio controls, a responsive UI, and smooth playback functionality.

![Project Banner](images/aashiqui2.png)

---

Deployment Link: https://spotify-playlist-clone-iota.vercel.app/

## 📖 Overview

The **Spotify Playlist Clone** is a front-end web application that demonstrates modern web development techniques to create an interactive music player. Built entirely with vanilla HTML, CSS, and JavaScript, this project showcases the ability to design and implement a professional-grade user interface without relying on frameworks or libraries.

The player features the iconic Aashiqui 2 album, allowing users to:
- Play, pause, and skip songs
- Navigate between tracks with next/previous controls
- View song details including artist names and duration
- Experience a visually appealing, Spotify-inspired design
- Interact with intuitive controls that mimic real music streaming platforms

This project serves as an excellent portfolio piece demonstrating proficiency in front-end development, DOM manipulation, audio API usage, and responsive design principles.

---

## ✨ Features

### 🎧 Core Functionality
- **Audio Playback**: Seamless audio streaming using the HTML5 Audio API
- **Track Navigation**: Next/Previous buttons for easy playlist navigation
- **Play/Pause Controls**: Toggle playback with a single click
- **Progress Bar**: Visual representation of song progress with real-time updates
- **Volume Control**: Adjustable volume slider for personalized listening experience

### 🎨 User Interface
- **Spotify-Inspired Design**: Authentic recreation of Spotify's dark theme and layout
- **Album Cover Display**: Prominent album artwork with artist information
- **Song List**: Structured table displaying all tracks with titles, artists, and durations
- **Hover Effects**: Interactive elements that respond to user actions
- **Responsive Navigation**: Clean navigation bar with branding and user account section

### 🎼 Music Collection
- **Complete Aashiqui 2 Album**: All 11 tracks from the acclaimed 2013 soundtrack
  - Tum Hi Ho (Arijit Singh)
  - Sunn Raha Hai (Ankit Tiwari)
  - Chahun Main Ya Naa (Arijit Singh, Palak Muchhal)
  - Hum Mar Jayenge (Arijit Singh, Tulsi Kumar)
  - Meri Aashiqui (Arijit Singh, Palak Muchhal)
  - Piya Aaye Na (K.K., Tulsi Kumar)
  - Bhula Dena (Mustafa Zahid)
  - Aasan Nahin Yahan (Arijit Singh)
  - Sun Raha Hai-Female (Shreya Ghoshal)
  - Milne Hai Mujhse Aayi (Arijit Singh)
  - Aashiqui-The Love Theme (Instrumental)

---

## 🚀 Installation & Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Node.js and npm (for running a local development server)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/lovemishra28/Spotify-Playlist-Clone.git
   cd Spotify-Playlist-Clone
   ```

2. **Open the project**
   - **Option 1 (Simple)**: Open `index.html` directly in your browser
   - **Option 2 (Recommended)**: Use a local development server
     ```bash
     # Using npx (no installation required)
     npx http-server -p 8080 -o
     
     # Or using live-server
     npx live-server --port=8080 --open=index.html
     ```

3. **Start listening!**
   - The music player will open in your default browser
   - Click on any song or use the play button to start playback

### Environment Configuration

While this project doesn't require environment variables for basic functionality, an `.env.example` file is included to demonstrate best practices for future enhancements:
- Copy `.env.example` to `.env` if you plan to add API integrations
- Configure server ports or feature flags as needed

---

## 📁 Project Structure

```
Spotify-Playlist-Clone/
│
├── index.html              # Main HTML structure
├── style.css               # Custom CSS styling
├── script.js               # JavaScript logic for player functionality
│
├── Aashiqui 2 (2013)/      # Audio files folder
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ...                 # Additional MP3 files
│
├── images/                 # UI assets and icons
│   ├── spotify_logo.png
│   ├── aashiqui2.png
│   ├── play.png
│   ├── pause.png
│   ├── next.png
│   ├── previous.png
│   └── ...                 # Additional image assets
│
├── README.md               # Project documentation (this file)
├── package.json            # Project metadata and scripts
├── .gitignore              # Git ignore rules
└── .env.example            # Environment variables template
```

### Supporting Files

This project includes essential development files that showcase professional coding practices:

- **`README.md`**: Comprehensive project documentation with setup instructions, features, and usage guidelines
- **`package.json`**: Defines project metadata, dependencies, and convenient npm scripts for local development
- **`.gitignore`**: Prevents sensitive files and build artifacts from being tracked by version control
- **`.env.example`**: Template for environment variables, demonstrating scalable configuration management

These files ensure the project is maintainable, shareable, and ready for collaboration or deployment.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript (ES6+)** | Audio control, DOM manipulation, event handling |
| **HTML5 Audio API** | Native audio playback functionality |

---

## 💡 Key Technical Highlights

- **Vanilla JavaScript**: No external libraries or frameworks—pure JavaScript implementation
- **Event-Driven Architecture**: Efficient event listeners for user interactions
- **Dynamic UI Updates**: Real-time updates to song information and progress indicators
- **Audio State Management**: Proper handling of audio playback states and transitions
- **Responsive Design**: Fluid layout that adapts to different screen sizes
- **Modular Code**: Clean separation of concerns with organized functions

---

## 🎯 Purpose & Importance

This project serves multiple purposes:

1. **Learning & Skill Development**: Demonstrates mastery of fundamental web technologies without framework dependencies
2. **Portfolio Showcase**: A visually impressive project that highlights design and development capabilities
3. **Real-World Application**: Simulates actual music player functionality found in popular streaming services
4. **Code Quality**: Exhibits clean, maintainable code with proper structure and documentation
5. **Best Practices**: Incorporates industry-standard development practices including version control configuration and environment management

The project is ideal for:
- Beginners learning front-end development
- Developers practicing DOM manipulation and audio APIs
- Creating a foundation for more complex music applications
- Demonstrating technical skills to potential employers or collaborators

---

## 🔮 Future Enhancements

Potential improvements and features for future versions:
- [ ] Integration with Spotify Web API for live music data
- [ ] Playlist creation and management
- [ ] Search functionality for songs and artists
- [ ] User authentication and personalized playlists
- [ ] Lyrics display synchronized with playback
- [ ] Shuffle and repeat modes
- [ ] Responsive mobile design optimization
- [ ] Cross-browser audio format support
- [ ] Keyboard shortcuts for controls

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/lovemishra28/Spotify-Playlist-Clone/issues) if you want to contribute.

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Love Mishra**
- GitHub: [@lovemishra28](https://github.com/lovemishra28)
- Project Link: [Spotify-Playlist-Clone](https://github.com/lovemishra28/Spotify-Playlist-Clone)

---

## 🙏 Acknowledgments

- Inspired by [Spotify's Web Player](https://open.spotify.com/)
- Album: Aashiqui 2 (2013) - Music by Mithoon, Jeet Ganguli, and Ankit Tiwari
- Icons and UI elements designed to match Spotify's aesthetic

---

## ⭐ Show Your Support

If you found this project helpful or interesting, please consider giving it a star on GitHub! It helps others discover the project and motivates further development.

---

**Happy Listening! 🎶**
