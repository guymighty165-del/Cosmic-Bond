# Cosmic-Bond
Project created for hackathon
# ✨ Cosmic Bonds — Astrological Synastry & Compatibility Engine

[![Live App](https://img.shields.io/badge/Live-App-purple?style=for-the-badge)](https://cosmic-bonds-astrolive.web.app)
[![Firebase Hosting](https://img.shields.io/badge/Hosted-Firebase-orange?style=for-the-badge)](https://cosmic-bonds-astrolive.web.app)
[![Vite](https://img.shields.io/badge/Build-Vite-blue?style=for-the-badge)](https://vite.dev)
[![Tailwind CSS v4](https://img.shields.io/badge/Styles-Tailwind%20v4-pink?style=for-the-badge)](https://tailwindcss.com)

**Cosmic Bonds** is a high-aesthetic, mobile-responsive astrological synastry and compatibility engine designed to drive organic user acquisition and retention for AstroLive. By turning individual birth charts into interactive, shareable relationship profiles, it addresses the "single-player bottleneck" of traditional astrology super-apps using structural virality.

---

## 🚀 Key Features

* **🔮 Cosmic Identity Cards (`/card`):** Generate a personal zodiac identity passport showcasing elements, modalities, ruling planets, core personality traits, love style quotes, and shadow sides.
* **💕 Dynamic Compatibility Checker (`/check`):** Calculate detailed synastry metrics between two people. Features a live zodiac sign preview as birthdates are inputted.
* **📊 4-Dimensional Synastry Dashboard (`/results`):** Staggered progress indicators grading relationships across:
  - 💝 **Love & Romance:** Emotional sync and raw chemistry.
  - 💬 **Communication:** Mental alignment and dialogue flow.
  - ⚡ **Conflict Resolution:** Managing friction and balance.
  - 🔮 **Soul Connection:** Karmic synergy and longevity.
* **📥 One-Click Social Sharing:**
  - Export beautiful 9:16 aspect ratio cards as PNGs (powered by `html2canvas`).
  - Pre-formatted sharing links for WhatsApp and Twitter/X with deep links.
* **🌌 Twinkling Stars Background:** Custom canvas-free SVG particles with CSS-driven twinkling animations.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** React 18 (Functional Components, Hooks, Context, Router v6)
* **Build System:** Vite 8 (Ultra-fast Hot Module Replacement)
* **Styles:** Tailwind CSS v4 (Modern utility-first configurations)
* **Image Capture:** html2canvas (Dynamic client-side DOM-to-PNG rendering)
* **Hosting:** Firebase Hosting (Deployed using Firebase MCP tools, optimized caching)

---

## 📁 Repository Structure

```
cosmic-bonds/
├── index.html                    # HTML document entry with SEO meta tags & preloaded fonts
├── firebase.json                 # Firebase deployment configuration (rewrites for SPA routing)
├── .firebaserc                   # Firebase active project association
├── vite.config.js                # Vite configuration with React and Tailwind plugins
├── src/
│   ├── main.jsx                  # React application mount
│   ├── App.jsx                   # React Router route declarations
│   ├── index.css                 # Custom CSS variables, animations, and keyframes
│   ├── utils/
│   │   └── astrology.js          # Core math engine (element compatibility, aspects, name hashing)
│   ├── components/
│   │   ├── StarsBackground.jsx   # Twinkling particle field
│   │   ├── Navbar.jsx            # Sticky navigation bar with mobile support
│   │   ├── Footer.jsx            # Dynamic footer with social anchors
│   │   ├── ScoreCircle.jsx       # Animated circular SVG score dial
│   │   └── ScoreBar.jsx          # Animated horizontal score bar
│   └── pages/
│       ├── LandingPage.jsx       # Interactive sign grid and marketing landing
│       ├── CompatibilityChecker.jsx  # Double-input synastry form with live previews
│       ├── ResultsPage.jsx       # Compatibility analytics and bond generation
│       └── ZodiacCard.jsx        # Individual astral identity card builder
```

---

## 💻 Local Setup & Development

Ensure you have [Node.js](https://nodejs.org) installed on your system.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/cosmic-bonds.git
   cd cosmic-bonds
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to the address shown in your console (usually `http://localhost:5173`).

4. **Build for Production:**
   ```bash
   npm run build
   ```

5. **Deploy to Firebase Hosting:**
   ```bash
   npx firebase deploy --only hosting
   ```

---

## 📈 Strategic Analysis & Case Study

For an in-depth breakdown of the market research, problem statements, expected CAC/retention impact, success metrics, and mathematical formulas backing the synastry engine, read our full [Proposal & Case Study](PROPOSAL_AND_CASE_STUDY.md).

---

## 📜 Citations & References

All market valuations, demographic details, and growth projections are formally cited in [PROPOSAL_AND_CASE_STUDY.md#6-formal-citations--references](PROPOSAL_AND_CASE_STUDY.md#6-formal-citations--references).
No environment files, private credentials, or API keys are stored in this repository. All calculations are executed securely client-side.
