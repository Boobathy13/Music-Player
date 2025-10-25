# 🎧 HarmoniX – A Modern Web Music Player

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![FontAwesome](https://img.shields.io/badge/Icons-FontAwesome-blueviolet)

---

## 📌 Overview

**HarmoniX** is a sleek and responsive **web-based music player** built using HTML, CSS, and JavaScript.
It allows users to play, pause, and navigate through songs while visually tracking the playback progress.
Simple, elegant, and lightweight — designed to offer a smooth music-listening experience directly from your browser.

---

## ✨ Features

* 🎵 **Play / Pause Control** – Toggle playback with a single click
* ⏩ **Seek Bar** – Drag to skip to any point in the song
* 🎚️ **Real-Time Progress** – Progress bar updates dynamically as the music plays
* 🎨 **Responsive Design** – Works beautifully across devices
* 🖼️ **Custom Media Support** – Easily replace audio and image files in the `/media` folder

---

## 🧰 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Icons:** Font Awesome
* **Assets:** Local media (song and image files)

---

## 🗂️ Project Structure

```
HarmoniX/
├── index.html            # Main UI layout
├── styles.css            # Styling for the music player
├── script.js             # Functionality (play/pause, progress control)
├── media/
│   ├── Song.mp3          # Sample audio file (replace with your own song)
│   └── img.png           # Album art or cover image
└── README.md
```

---

## 🛠️ How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Boobathy13/HarmoniX.git
cd HarmoniX
```

### 2️⃣ Add Media Files

To make the music player work properly, add your **song** and **album image** to the `media` folder:

```
HarmoniX/
└── media/
    ├── Song.mp3   # your audio file (rename if needed)
    └── img.png    # album or song cover image
```

Ensure the file names in your `index.html` match exactly:

```html
<source src="media/Song.mp3" type="audio/mpeg">
<img src="media/img.png" class="song-img">
```

### 3️⃣ Open in Browser

Simply open the `index.html` file in any modern browser.
No server setup or dependencies required.

---

## 💡 How It Works

* The **JavaScript** dynamically updates the playback state and progress bar:

  * When the song metadata loads, the slider (`progress`) is synced with the total duration.
  * Clicking the **play/pause button** toggles the icon and controls playback.
  * The progress bar updates in real-time as the song plays.
  * Dragging the slider seeks to a new position instantly.

---

## 🚀 Future Enhancements

* 🔁 Add next / previous track functionality
* 🎧 Add playlist support
* 💫 Include volume control
* 🕒 Display current time & duration
* 🌈 Animate album art on play
* 📱 Add dark / light mode toggle

---

## 📝 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Boobathy R**
📧 [hungrylearner2002@gmail.com](mailto:hungrylearner2002@gmail.com)
