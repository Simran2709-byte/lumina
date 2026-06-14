🌌 LUMINA — Your Learning Universe
StatusLicenseHTML5CSS3JavaScriptTailwind

Lumina is an immersive, AI-powered educational platform where learning feels like exploring infinite dimensions. Built with a production-level mindset, it moves beyond traditional static templates to deliver a living, breathing web experience that talks to you, tracks your progress, and adapts to your curiosity.

Built as a market-level project for the InAmigos Foundation Internship, demonstrating that educational platforms can be both functionally deep and visually stunning.

🚀 Live Demo
Experience it now: https://simran2709-byte.github.io/lumina/

📸 Project Overview:
Lumina isn't just a website; it's a complete learning ecosystem. From the neural network hero background that reacts to your cursor to the AI mentor that speaks back to you, every interaction is designed to make education feel alive.

✨ Mind-Blowing Features

🧠 Immersive UI & UX
Neural Network Hero: A living canvas of particles and connections that responds dynamically to mouse movement.
3D Tilt Cards: Learning paths physically tilt toward the user's cursor with realistic glare effects.
Glassmorphism Design: Deep space aesthetic with consistent blur, borders, and ambient glows.
Mouse Glow Follower: A subtle teal aura follows the user's cursor across the site.
Zero Inline Styles: 100% separation of concerns with CSS classes and custom properties.

📚 Complete Course System
6 Learning Dimensions: CodeCraft, DesignVerse, DataSphere, BizLogic, LifeSkills, AI Frontiers.
Real Educational Content: Modules and lessons with actual, digestible explanations.
Interactive Quizzes: Multiple-choice questions with instant correct/incorrect feedback and scoring.
Bookmarking: Save lessons for later. All bookmarks are saved in the user's profile.

🤖 AI Mentor (Web Speech API)
Conversational Chatbot: 20+ topic categories (Python, AI, Career, Motivation, etc.) with dynamic responses.
Voice Synthesis: Toggle voice mode, and the AI literally speaks its responses to you.
Context-Aware: Remembers the user's name and references it in conversations.
Proactive Companion: A floating orb that periodically shares tips and encouragement.

🎮 Gamification & Progression
XP System: Earn XP for reading lessons, taking quizzes, exploring tags, and studying.
Levels & Confetti: Level up triggers a screen-wide confetti celebration.
12 Real Achievements: "First Hello", "Quiz Ace", "3-Day Streak", "Certified", etc., all triggered by actual user actions.
Daily Streaks: Tracks consecutive days of learning via LocalStorage.

🗺️ Interactive Knowledge Graph
Canvas-Based Visualization: 14 nodes and 17 edges representing topic relationships.
Fully Interactive: Drag nodes to rearrange, scroll to zoom, click nodes to see connections and earn XP.

⏱️ Productivity Tools
Pomodoro Study Timer: Focus (25m), Short Break (5m), Long Break (15m) modes.
Visual Progress Ring: SVG ring animates as time counts down.
Certificate Generator: Complete a path to generate a downloadable, branded PNG certificate via Canvas API.

🛠️ Tech Stack & Architecture
This project prioritizes clean, native web technologies with zero framework dependencies.

Technology	Usage:
HTML5	Semantic structure, Canvas API, Form validation
CSS3	Custom Properties, Keyframes, Glassmorphism, Theme Classes, -webkit- prefixes for Safari
Vanilla JS	State management, Intersection Observer, Web Speech API, Canvas rendering, LocalStorage persistence
Tailwind CSS	Utility-first layout and spacing (via CDN)
Font Awesome	Iconography
Google Fonts	Space Grotesk (Display) + DM Sans (Body)

Architecture Highlights:
Strict Separation of Concerns: index.html (Structure), style.css (Design), script.js (Logic).
CSS Theme Classes: Replaced all JavaScript inline styles with .theme-teal, .theme-pink, etc., allowing dynamic color theming purely through CSS class toggling.
Persistent State: All user progress (XP, level, read lessons, quiz scores, bookmarks, achievements, streaks) survives page refreshes via localStorage.
