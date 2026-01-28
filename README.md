🐈 Cat Run - AI-Powered Infinite Runner

Cat Run is a lightweight, browser-based infinite runner game that demonstrates the power of integrating Generative AI into classic arcade mechanics. Built entirely with vanilla HTML5, CSS3, and JavaScript, this project serves as a case study for rapid game development and dynamic content generation.

🚀 Project Overview

The core game is a polished side-scroller where players guide a cat through an endless road of obstacles (cacti, rocks, boxes) and flying enemies. However, unlike traditional games with static assets, Cat Run features a "Magic Theme Generator" powered by the Google Gemini API.

🌟 Key Features

Dynamic Theming: Players can input any text prompt (e.g., "Cyberpunk", "Underwater", "Mars Colony"), and the game uses an LLM to hallucinate a complete visual overhaul in real-time—changing the player avatar, enemies, background gradients, and game title to match the requested theme.

AI Commentary System: Upon losing, the game sends the run data (score, cause of death, active theme) to Gemini, which generates a witty, context-aware "roast" or reaction, making every "Game Over" screen unique.

Cross-Platform Engine: The custom physics engine supports both desktop (Keyboard/WASD) and mobile (Touch/On-screen buttons) play with responsive canvas scaling.

Forgiveness Mechanics: Includes a 3-heart health system and invulnerability frames to balance difficulty.

🛠️ How It Was Built

This project highlights how AI tools can compress development cycles from weeks to hours. By leveraging AI for boilerplate code, physics logic, and asset selection, the focus shifted entirely to high-level feature implementation and API integration.

Tech Stack

Frontend: HTML5 Canvas API

Styling: CSS3 (Responsive Design)

Logic: Vanilla JavaScript (ES6+)

AI Integration: Google Gemini 2.5 Flash API (via direct HTTP calls)

📦 Quick Start

Clone the repo.

Open index.html in any modern web browser.

To enable AI features, click "Magic Theme" and paste your free Gemini API key when prompted.

Created as a demonstration of AI-assisted web development.
