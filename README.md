<div align="center">

# 🧠 ⚡ MathMental
### *Fast-Paced Mental Arithmetic & Brain Agility Challenge* 🎯 ⏱️

<br/>

<p align="center">
  <img src="art/mathmental_banner.jpg" alt="MathMental 3D Banner" width="100%" style="border-radius: 16px; box-shadow: 0 10px 35px rgba(0,0,0,0.35);" />
</p>

[![Game Category](https://img.shields.io/badge/Genre-Brain%20Workout%20%F0%9F%A7%A0-00E5FF?style=for-the-badge)](https://github.com/rajabbov/MathMental)
[![Speed](https://img.shields.io/badge/Mode-Beat%20the%20Clock%20%E2%8F%B1%EF%B8%8F-FF3D00?style=for-the-badge)](https://github.com/rajabbov/MathMental)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin%20Native-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Platform](https://img.shields.io/badge/Platform-Android%2015-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)

> ⚡ *"Calculators make us lazy. MathMental makes you sharp. 10 rapid-fire questions, a shrinking timer, and pure cognitive reflex — can your brain beat the clock?"* 🚀 🔥

</div>

---

## 🎮 The Mental Workout: Train Your Neural Speed

In a world reliant on screens and automated calculations, mental math is the ultimate cognitive superpower. 

**MathMental** is an adrenaline-fueled Android brain trainer designed to sharpen numeric intuition, boost calculation speed, and improve focus under pressure. With dynamic countdown timers and progressive difficulty tiers, every round is a test of sharp reflexes and mental endurance.

---

## 🏆 3 Battle Arenas (Difficulty Modes)

Tailor your cognitive training session according to your skill level:

```text
  🟢 EASY (Apprentice)      🟡 MEDIUM (Challenger)     🔴 HARD (Grandmaster)
  ─────────────────────     ──────────────────────     ─────────────────────
  Foundational arithmetic   Multi-operation problems   High-pressure calculations
  Generous thinking time    Accelerated countdown      Rapid-fire timer ticks
  Ideal for warming up      Builds rapid recall        Zero room for hesitation
```

---

## ⚡ Core Gameplay Mechanics

### 1. ⏱️ The Ticking Pressure Gauge
Every question is backed by an active `CountDownTimer` linked to a synchronized horizontal progress bar. Watch time drain in real-time as your mind races for the correct answer.

### 2. 🎯 Rapid 4-Option Grid
Four high-contrast answer buttons deliver instant feedback. Tap your answer and immediately advance to the next challenge without tedious transition delays.

### 3. 📊 Post-Match Tactical Review
Finished your 10 rounds? The game doesn't just display a score — it launches a detailed performance review:
- **Total Accuracy Rating:** Clear score breakdown (e.g. `8/10`).
- **Answer Audit (`QuestionAdapter`):** Scroll through every equation, view what you selected, and study the correct answer for continuous improvement.

---

## 🔄 Cognitive Game Loop (State Pipeline)

```text
       [ Select Arena Mode ] ──► (Easy / Medium / Hard)
                 │
                 ▼
       ┌────────────────────────────────────────────────────────┐
       │             Active Round Loop (10 Rounds)              │
       │                                                        │
       │   Equation Display  ──►  Synchronized Countdown Timer  │
       │          │                          │                  │
       │          ▼                          ▼                  │
       │   Instant 4-Choice Tap  ──►  Auto-Advance Next Round   │
       └─────────────────────────┬──────────────────────────────┘
                                 │
                                 ▼
       ┌────────────────────────────────────────────────────────┐
       │             Performance Analytics Screen               │
       │                                                        │
       │   • Overall Score Counter (X / 10)                     │
       │   • Full Match History & Question Audit Feed           │
       │   • Instant Rematch Option                             │
       └────────────────────────────────────────────────────────┘
```

---

## 🛠 Engineering & Technical Specifications

- **Language:** Kotlin 100% (JVM Target 1.8)
- **Minimum SDK:** Android 7.0 (API 24)
- **Target SDK:** Android 15 (API 35)
- **Architecture Pattern:** Clean Activity-based modular separation with dedicated data providers
- **Concurrency & Timing:** Native Android `CountDownTimer` with smooth progress interpolation
- **Data Presentation:** RecyclerView with custom `QuestionAdapter` for post-game answer diagnosis
- **UI Framework:** Material 3, ViewBinding, and custom color-coded drawable states

---

## 🚀 Quick Setup & Play

```bash
# 1. Clone the repository
git clone https://github.com/rajabbov/MathMental.git

# 2. Open in Android Studio
# Launch Android Studio -> Open -> Select "MathMental" directory

# 3. Hit Run (Shift + F10)
# Choose your difficulty and start testing your brain speed! 🧠 ⚡
```

---

## 👨‍💻 Created By

**Ibrohimjon Rajabboyev**  
*Mobile App Developer • Android • Kotlin • Flutter • UI/UX*  
🔗 [GitHub Profile](https://github.com/rajabbov) • *Train your brain every day!* ⚡
