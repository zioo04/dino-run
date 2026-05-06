# 🦖 Dino Runner (3D Web Game)

A web-based runner game enhanced with 3D models and interactive mechanics.

---

## 🎮 Overview
This project started as a simple 2D game and was expanded into a 3D experience by applying 3D models to both the player and obstacles.

- Lane-based runner game with movement and jump mechanics
- Score tracking and local ranking system

---

## 🧩 Tech Stack
- HTML / CSS / JavaScript
- Three.js
- GLTFLoader (for loading 3D models)
- LocalStorage (for saving rankings)

---

## 🚧 Problem Solving & Improvements

### 1. Transition from 2D to 3D
The initial structure was designed in 2D, but was later upgraded to 3D to create a more immersive experience.

- Downloaded GLB models from Sketchfab
- Implemented model loading using Three.js GLTFLoader

👉 Result: Improved visual depth and immersion

---

### 2. Lack of Obstacle Variety
At first, the game only had a single obstacle type, which made gameplay repetitive.

- Expanded to three obstacle types (drone, fence, box)
- Implemented random spawning logic

👉 Result: Increased gameplay variety

❗ Limitation:
- Obstacle movement patterns are still simple and repetitive

---

### 3. Control System Improvement (User Feedback)
Initially, the player could only move left and right.

- Added jump functionality based on user feedback
- Implemented swipe and keyboard controls
- Applied gravity and velocity-based jump logic

👉 Result: More dynamic and engaging gameplay

---

### 4. Ranking System Implementation
Implemented a local ranking system using LocalStorage.

👉 Result:
- Players can track and compare their high scores

❗ Limitation:
- No real-time ranking comparison with other users

---

### 5. Collision Detection Limitation
Collision detection is currently based on a 3-lane system.

👉 Issue:
- Collisions depend on lane alignment
- In some cases, objects visually overlap without triggering a collision

❗ Improvement Plan:
- Upgrade to bounding box-based collision detection

---

## 📈 Future Improvements
- Implement physics-based collision detection
- Add more diverse obstacle patterns (speed, movement)
- Develop an online ranking system
- Add character animations

---

## 🔗 GitHub
[[Project Link](https://zioo04.github.io/dino-run/)]
