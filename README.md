# 🚗 Moving Car — Web Edition (Version 3)

> **Version 3** of the Moving Car project — now fully playable in the browser!  
> Originally written in **Turbo C++ (v1)**, rewritten in **Modern C++ with SFML (v2)**, and now converted to **HTML5 Canvas + JavaScript (v3)** and deployed on Vercel.

🌐 **Live Demo:** [https://moving-car-using-html-5-version.vercel.app/](https://moving-car-using-html-5-version.vercel.app/)

---

## 🎮 Play Now

Just open the link above — no installation needed. Runs directly in your browser!

---

## 📋 About the Project

A browser-based animated car game featuring a player-controlled car you can drive left and right, multiple NPC cars moving on their own across two lanes, animated rain falling from the sky with puddle splashes, a night city skyline in the background, engine and rain sound effects, and a score system that increases as you drive.

---

## 🔄 Version History

| Version | Platform | Language / Tech | Graphics |
|---------|----------|----------------|----------|
| v1 | DOS / Turbo C++ 3.0 | Turbo C++ | BGI `graphics.h` |
| v2 | Windows / Linux / macOS | Modern C++ (C++17) | SFML |
| v3 | 🌐 Browser (Vercel) | HTML5 + JavaScript | Canvas API |

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `◀` Left Arrow | Move car left |
| `▶` Right Arrow | Move car right |
| `▲` Up Arrow | Increase game speed |
| `▼` Down Arrow | Decrease game speed |
| `SPACE` | Add a new car (max 8) |
| `M` | Mute / Unmute sound |

---

## ✨ Features

- 🚗 **Player car** with smooth acceleration and deceleration
- 🚙 **Multiple NPC cars** moving independently on two lanes
- 🌧️ **Animated rain** with diagonal falling drops and puddle splash effects
- 🎨 **Random car color changes** every few frames
- 🌃 **Night city background** with twinkling stars and glowing building windows
- 💡 **Headlights and taillights** glowing on each car
- 🔊 **Web Audio engine hum + rain ambience** (toggleable)
- 🏎️ **Animated spinning wheels** with rim spokes
- 📊 **HUD** showing score, car count, and speed

---

## 🚀 How to Deploy on Vercel

**Step 1 — Push to GitHub**
1. Create a new GitHub repo (e.g., `moving-car-web`)
2. Upload `index.html` to the repo
3. Commit and push

**Step 2 — Deploy on Vercel**
1. Go to [vercel.com](https://vercel.com)
2. Click **"New Project"**
3. Import your GitHub repo
4. Click **"Deploy"**
5. Done! Your live URL is ready 🎉

---

## 🗂️ Project Structure

```
moving-car-web/
├── index.html       # Full game — HTML5 Canvas + JavaScript
└── README.md        # This file
```

> No dependencies, no build tools, no frameworks needed.  
> Pure vanilla HTML + JavaScript — just one file!

---

## 🔧 Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 Canvas API | Drawing cars, rain, road, background |
| Vanilla JavaScript | Game loop, physics, controls |
| Web Audio API | Engine hum and rain sound effects |
| Google Fonts (Orbitron) | UI typography |
| Vercel | Hosting and deployment |

---

## 💡 What I Learned

- How to convert **Turbo C++ BGI graphics** to modern equivalents
- How to use **SFML** for desktop C++ graphics (v2)
- How to use **HTML5 Canvas** for browser-based graphics (v3)
- How to set up **GitHub Actions CI/CD** for C++ projects
- How to deploy a static web app on **Vercel**

---

## 👩‍💻 Author

**WinonaLaher2002**  
GitHub: [github.com/WinonaLaher2002](https://github.com/WinonaLaher2002)

---

## 📝 License

This project is for educational purposes.
