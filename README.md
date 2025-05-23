# 🌟 Mojitown

<div align="center">
  <img src="./client/src/assets/HomePage/Landing_page.png" alt="Mojitown Banner" width="700px" />
  <br/>
  <em>"Tiny friends, big emotions."</em>
</div>

## 📱 About Mojitown

**Mojitown** is an emotionally intelligent AI village where users create customizable characters ("Mojis") with unique personalities. These Mojis live, interact, and grow in a cozy virtual world, offering emotional support through playful, therapeutic conversations and rich social simulation.

<div align="center">
  <img src="https://img.shields.io/badge/Status-In_Development-blue?style=for-the-badge" alt="Status: In Development" />
  <img src="https://img.shields.io/badge/Release-Stage_1-orange?style=for-the-badge" alt="Release: Stage 1" />
</div>

## 📌 Project Scope

This project explores how emotionally aware AI companions can support wellness and everyday reflection in a calming, character-driven environment.

### Stage 1 Focus (April–June 2025)

- Creating custom characters with distinct personalities and roles
- Building a visual simulation where Mojis interact with one another
- Allowing users to engage in AI conversations with Mojis based on their traits

## 👨‍👩‍👧‍👦 Target Users

- **Young adults (18–35)** looking for emotional support in a low-pressure environment
- **Neurodiverse individuals** who benefit from consistent and calming digital routines
- **Cozy game lovers** and creatives who enjoy customizable character-based experiences
- **Users seeking** light, emotionally intelligent AI companions for daily interaction

## ✨ Features

### ✅ Stage 1 (Due by June 6, 2025)

#### Character Creation
- Define personality traits (e.g., MBTI)
- Assign professions and backstories
- Customize appearance via emoji selection
- **New:** Choose character color, birthday, and zodiac sign
- **New:** Persistent character data across sessions
- **New:** Create and manage multiple Moji characters in your village.

#### AI Conversations
- Personality-driven dialogue
- Responsive to topic-based user prompts
- Emotionally supportive interactions

#### Village Simulation
- Watch Mojis interact organically (future goal, current implementation focuses on individual Moji presence)
- Observe daily routines and special events (future goal)
- Dynamic relationships between characters (future goal)
- **New: Dynamic Moji Presence & Movement:**
    - Mojis now have an animated entry sequence (dropping, posing, then walking).
    - Each Moji walks independently with a randomized initial direction (left/right).
    - Mojis select one of four distinct vertical tracks in the grass area for each walking "round."
    - Characters walk completely off-screen before turning around and re-entering on a new track.
    - An "Add Another Moji" button allows for easy expansion of the village population.
    - Overall character walk speed has been refined for a more natural pace.

### 🔮 Future Implementation (Post-June 6, 2025)

#### Learning Companion Mode
- Choose a Moji to follow your reading
- Moji learns from the content you read
- Provides summaries, answers questions, and reinforces learning

#### Advanced Social Features
- Multi-user village sharing
- Character development over time
- Seasonal events and celebrations

## 🧰 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **State Management**: Zustand with persistence
- **Character AI**: Custom AI models for personality-driven dialogue
- **Deployment**: [Platform to be determined]

## 🗓️ Timeline (Stage 1 – Until June 6, 2025)

| Phase | Description | Timeframe |
|-------|-------------|-----------|
| 🔧 Feature Planning & Mindmap | Define features, prioritize scope | April Week 2 |
| 🧠 AI + UI Prototype | Build character creation + interaction | April Week 3–4 |
| 🏘️ Village Simulation | Characters interacting in a shared world | May Week 1–3 |
| 🧪 Testing & Polish | Test flows, refine UI, finalize logic | May Week 4 – June Week 1 |
| 🚀 Final Delivery | Submit and demo Stage 1 | **June 6, 2025** |

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/xanx66/mojitown.git
   cd mojitown
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 🧑‍🤝‍🧑 Team Contact

- **Fiona Wu** — itzsyboo@uw.edu
- **Annika An** — xanx5@uw.edu

---

<div align="center">
  <p>University of Washington Project • 2025</p>
  <p>Made with 💙 by Team Mojitown</p>
</div>