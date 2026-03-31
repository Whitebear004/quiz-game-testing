# 🐉 Dragon Quiz Runner 🌸

*An interactive 2D runner game that combines high-speed obstacle dodging with real-time HTML5 quiz challenges!*

---

## 📋 Project Description

**Dragon Quiz Runner** is an engaging, single-player web-based game that merges educational content with interactive gameplay. Players control a magical pink dragon that must dodge cacti while answering HTML5 quiz questions to progress. The game features a dynamic scoring system, responsive design, and immersive sound effects powered by the Web Audio API.

Each correct answer rewards the player with a jump animation and points, while incorrect answers trigger a game-over state. The ultimate goal is to reach 50 points to achieve victory and trigger a celebratory winner screen with confetti animations.

---

## ⭐ Key Features

| Feature | Description |
|---------|-------------|
| 🎮 **Interactive Quiz System** | Real-time HTML5 questions trigger when the dragon approaches obstacles |
| 📊 **Dynamic Score Tracking** | Visual progress bar and real-time score updates with instant feedback |
| 🎨 **Glassmorphism UI** | Modern, frost-glass effect panels with blur and transparency effects |
| 🔊 **Web Audio API Integration** | Soft, non-annoying sound effects with sine wave synthesis |
| 🎪 **Responsive Design** | Flexbox-based layout that adapts seamlessly to all screen sizes |
| 🐉 **Smooth Animations** | CSS keyframe animations for dragon flight, wing beats, and smooth jumping |
| 🌸 **Georgian Language Support** | Full localization in Georgian (ქართული) for immersive experience |
| 💾 **Player Persistence** | Name entry at game start stored during session |
| 🏆 **Victory Mechanics** | Reach 50 points to unlock winner screen with celebratory sounds |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic structure, SVG sprites, form handling |
| **CSS3** | Glassmorphism effects, Flexbox layout, CSS animations & keyframes |
| **Vanilla JavaScript (ES6+)** | Game loop, collision detection, quiz logic, state management |
| **Web Audio API** | Procedural sound generation, tone synthesis, gain control |
| **SVG Graphics** | Scalable vector illustrations for dragon and cactus sprites |

### Browser Support
- ✅ Chrome/Chromium (v60+)
- ✅ Firefox (v55+)
- ✅ Safari (v14+)
- ✅ Edge (v79+)

---

## 🎮 How to Play

### Quick Start

1. **Enter Your Name** 📝
   - Navigate to the game page
   - Type your player name in the input field
   - Click **"თამაშის დაწყება"** (Start Game)

2. **Avoid the Cactus** 🌵
   - The dragon automatically runs forward
   - Watch for approaching cacti obstacles
   - When a quiz question appears, you must answer correctly to jump

3. **Answer Quiz Questions** ❓
   - A question appears with 4 multiple-choice answers
   - Select the **correct answer** to make the dragon jump over the cactus
   - **Correct answer** = +2 points 🌸
   - **Wrong answer** = Game Over 💔

4. **Reach Victory** 🏆
   - Score 50 points to win the game
   - Unlock the winner screen with celebratory animations and sound effects

### Controls

| Action | Input |
|--------|-------|
| Enter Name | Type in input box |
| Start Game | Click "თამაშის დაწყება" button |
| Answer Question | Click any of the 4 choice buttons |
| Restart Game | Click "▶ კვლავ ცდა" (Try Again) button |
| New Game | Click "🔄 ახალი თამაში" (New Game) button |

---

## 🎯 Gameplay Mechanics

### Scoring System
- **Base Points**: 2 points per correct answer
- **Win Condition**: 50 total points
- **Progression**: Visual progress bar shows distance to victory
- **Real-time Updates**: Score updates instantly with each correct answer

### Difficulty Elements
- 25 unique HTML5 quiz questions
- Random question selection
- One strike rule: Single wrong answer ends the game
- Progressive question variety

### Visual Feedback
- ✅ Correct answer: Dragon jumps, green status message, +2 points
- ❌ Wrong answer: Dragon crash animation, red status message, "Game Over" overlay
- 🏆 Victory: Winner screen with crown emoji, confetti animation, celebratory chime

---

## 🔊 Sound Features

### Audio Design
All sound effects use the **Web Audio API** with procedural generation:

| Sound | Trigger | Wave Type | Volume |
|-------|---------|-----------|--------|
| Jump Tone | Player jumps | Triangle | 0.05-0.06 |
| Correct Answer | Right answer selected | Sine | 0.06-0.07 |
| Wrong Answer | Incorrect answer | Sawtooth | 0.08 |
| Crash/Death | Hit obstacle or wrong answer | Triangle/Sine | 0.06-0.08 |
| Victory Chime | Reach 50 points | Sine | 0.05 |

**Soft Volume Design**: All sounds use reduced gain levels (0.05-0.08) for a pleasant, non-jarring experience.

---

## 📁 Project Structure

```
quiz-game/
├── index.html                 # Main game file (HTML + CSS + JS)
├── README.md                  # Project documentation
└── assets/                    # (Optional) For future enhancements
```

---

## 🚀 Installation & Deployment

### Local Setup
1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. No build tools or dependencies required!

### Live Deployment Options
- **GitHub Pages**: Push to a public GitHub repo and enable Pages
- **Netlify**: Drag-and-drop `index.html` to Netlify
- **Vercel**: Import repository for automatic deployment
- **Simple HTTP Server**: `python -m http.server 8000` (then visit `localhost:8000`)

### No Server Required
This is a fully client-side application. No backend, database, or external APIs required.

---

## ✅ Testing Checklist

- [x] Quiz questions display correctly
- [x] Correct answers trigger jump and +2 points
- [x] Wrong answers trigger Game Over
- [x] Score tracking works in real-time
- [x] Progress bar fills accurately
- [x] Victory screen appears at 50 points
- [x] Sound effects trigger appropriately
- [x] Responsive design on mobile/tablet
- [x] No console errors on startup
- [x] Collision detection accurate
- [x] Dragon animations smooth

---

## 🚀 Future Enhancements

- [ ] Background music with mute toggle
- [ ] Difficulty levels (Easy, Medium, Hard)
- [ ] Question categories (HTML, CSS, JavaScript)
- [ ] Achievement badges and medals
- [ ] Power-ups (shield, slow-motion)
- [ ] Mobile touch controls (swipe to jump)
- [ ] Dark/Light theme toggle
- [ ] Persistent high score storage with localStorage
- [ ] Animated particles and visual effects
- [ ] Multiplayer competitive mode

---

## 📝 Credits

**Created by**: Lana 👩‍💻

### Acknowledgments
- **Google Fonts**: Fredoka One & Nunito typography
- **Web Audio API**: Procedural sound generation
- Educational focus: HTML5 quiz content

### Special Thanks
To everyone who plays and provides feedback on Dragon Quiz Runner! Your insights help make this game better. 🌸

---

## 📄 License

This project is open-source and available for educational and personal use. Feel free to fork, modify, and share!

---

## 💬 Feedback & Support

Have suggestions or want to share your experience? Feel free to reach out through comments or issues!

**Happy quizzing and jumping!** 🐉✨