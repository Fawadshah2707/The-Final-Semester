
# 🎓 The Final Semester

### A Narrative-Driven Serious Game on Mental Health & Academic Ethics

[![Unity](https://img.shields.io/badge/Unity-6-black?logo=unity&logoColor=white)](https://unity.com/)
[![C#](https://img.shields.io/badge/C%23-purple?logo=csharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![URP](https://img.shields.io/badge/Render%20Pipeline-URP-blue)](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@latest)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![FYP](https://img.shields.io/badge/FYP-AWKUM%202025-orange)](https://awkum.edu.pk/)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?logo=windows)](https://unity.com/download)

<br/>

> *"You have one semester left. Every choice you make defines who you are."*

<br/>

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/bebf2fc7-26fc-4814-8e18-76ff56c3c14f" /><div align="center">




</div>

---

## 📖 About

**The Final Semester** is a serious game developed as a Final Year Project at **Abdul Wali Khan University Mardan (AWKUM)**, Department of Computer Science.

The game places the player in the role of a final-year CS student navigating the pressures of university life — deadlines, academic ethics, and mental well-being — across 8 story-driven scenes with branching narrative choices. Every decision carries consequences that ripple through the story, designed to raise awareness about student mental health and academic integrity.

This is not just a game. It's a reflection of real struggles faced by students across Pakistan and beyond.

---

## 🎮 Gameplay Overview

| Feature | Details |
|---|---|
| **Genre** | Serious Game / Narrative Adventure |
| **Perspective** | isometric/Orthogonal/2.5D |
| **Scenes** | 8 Story-Driven Chapters |
| **Core Mechanic** | Branching Dialogue & Ethical Choices |
| **Save System** | JSON-based State Persistence |
| **Target Audience** | University Students & Educators |

### 🌿 Themes
- 🧠 **Mental Health Awareness** — stress, burnout, anxiety, and coping mechanisms
- 📚 **Academic Ethics** — plagiarism, cheating, peer pressure, and integrity
- 🤝 **Social Relationships** — friendships, faculty interactions, family expectations
- ⚖️ **Consequence-Driven Storytelling** — your choices shape the ending

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **Unity 6** | Game Engine |
| **C#** | Game Logic & Scripting |
| **Universal Render Pipeline (URP)** | Lighting & Visual Quality |
| **Cinemachine** | Dynamic Camera System |
| **TextMesh Pro** | High-Quality UI Text |
| **JSON** | Save/Load State Persistence |
| **Unity Animator** | Character & Scene Animations |

---

## 🗂️ Project Structure

```
TheFinalsemester/
├── Assets/
│   ├── Scenes/             # 8 game scenes
│   ├── Scripts/            # All C# scripts
│   │   ├── Core/           # Game manager, state machine
│   │   ├── Dialogue/       # Narrative & branching system
│   │   ├── UI/             # HUD, menus, overlays
│   │   └── Save/           # JSON save/load system
│   ├── Prefabs/            # Reusable game objects
│   ├── Audio/              # Music & SFX
│   ├── Materials/          # URP materials
│   └── Resources/          # Runtime-loaded assets
├── ProjectSettings/
├── Packages/
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Unity Hub](https://unity.com/download) installed
- Unity **6.x** (LTS recommended)
- Windows 10/11 (primary target platform)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/the-final-semester.git
   ```

2. **Open with Unity Hub**
   - Launch Unity Hub
   - Click **Open** → select the cloned folder
   - Make sure Unity 6 is selected as the editor version

3. **Open the Main Scene**
   - Navigate to `Assets/Scenes/`
   - Open `MainMenu.unity` to start from the beginning

4. **Press Play** ▶️

> ⚠️ If prompted about URP asset missing, go to `Edit → Project Settings → Graphics` and assign the included URP asset from `Assets/Settings/`.

---

## 📸 Screenshots

<!-- Add actual screenshots below -->

| Scene | Preview |
|---|---|
| Main Menu | (<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/e5c64df0-8208-4167-9b89-659117bc8591" />
 )|
| Dialogue System | (<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/70988c63-13a2-4907-bcde-ca119ae6b4f7" />
) |
| Decision Moment |(<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/a9163711-1c72-49d6-8fe5-c1a5cf68d2fa" />
)|

---

## 🧩 Core Systems

### 🗣️ Dialogue & Branching Narrative
The dialogue system supports multi-branch conversations driven by player choices. Each choice updates the game state and can unlock or lock future scenes and dialogue paths.

### 💾 Save System
Game progress is stored as structured JSON files, tracking:
- Scene progress
- Player decisions made
- Moral/ethical score
- NPC relationship states

### 🎥 Cinemachine Camera
Dynamic cameras react to story events — close-ups during emotional moments, wide shots for exploration — all managed through Cinemachine Virtual Cameras.

---

## 📊 Academic Context

| Field | Details |
|---|---|
| **Project Type** | Final Year Project (FYP) |
| **University** | Abdul Wali Khan University Mardan (AWKUM) |
| **Department** | Computer Science |
| **Degree** | BS Computer Science |
| **Year** | 2025–2026 |
| **Supervisor** | *[Mr. Shahzad Khan]* |

---

## 🧑‍💻 Developer

**Fawad** — BS Computer Science, AWKUM
- GitHub: [@Fawadshah2707](https://github.com/Fawadshah2707)
- LinkedIn: [Fawad-Shah](https://linkedin.com/in/fawad-shah-840bbb26b)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — you are free to use, modify, and distribute it with attribution.

---

## 🙏 Acknowledgements

- **AWKUM Department of Computer Science** — for academic support
- **Unity Technologies** — for the game engine and documentation
- **Cinemachine & TextMesh Pro teams** — for their powerful Unity packages
- All students whose real experiences inspired the story

---

<div align="center">

*Made with ❤️ and a lot of deadlines — just like the game itself.*

</div>
