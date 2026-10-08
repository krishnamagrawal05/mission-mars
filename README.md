# 🚀 MISSION: MARS — Interactive Mission

A cinematic, interactive single-page experience that takes you from Earth to Mars. Launch the mission, watch live telemetry, inspect a rover, search for signs of life, and build the first human outpost on the Red Planet.

**🔴 Live demo:** [krishnamagrawal05.github.io/mission-mars](https://krishnamagrawal05.github.io/mission-mars/)

> This is a fictional, educational sci-fi experience. All telemetry, crew, rover data and analysis results are simulated and are not real mission data. It is not affiliated with or endorsed by NASA.

---

## Overview

MISSION: MARS is a scroll-driven, dark-themed web experience. Each section is a small interactive piece of the mission, from the countdown at Launch Complex 39A to the final "Welcome to Mars" mission summary. Along the way you earn badges and raise your mission readiness score.

## Features

| # | Section | What you can do |
|---|---------|-----------------|
| 00 | **Intro / Loader** | Mission systems initialize with a loading percentage and optional sound toggle |
| 01 | **The Journey** | Step through six phases: Earth Launch, Moon Gravity Assist, Deep Space Cruise, Mars Orbit Insertion, Descent and Surface |
| 02 | **Launch Window** | Start a T−10 second countdown synchronized with a cinematic launch sequence |
| 03 | **Mission Control** | Watch simulated live telemetry: velocity, fuel, signal, radiation, hull temperature, solar and power, comms and life-support status |
| 04 | **Meet ATLAS** | Tap the hotspot markers to inspect the autonomous rover's systems |
| 05 | **Martian Landscapes** | Explore Olympus Mons, Valles Marineris and Jezero Crater |
| 06 | **Martian Weather** | Switch between Clear, Dust, Global Storm and Cold Night conditions |
| 07 | **Search for Life** | Run a fictional field analysis on a Martian sample |
| 08 | **Message Delay** | Simulate the Earth to Mars communication light-time delay |
| 09 | **Human Factor** | Meet the four-person crew: Commander, Pilot, Engineer and Scientist |
| 10 | **Build Mars** | Activate Power, Habitat, Lab, Greenhouse and Comms to raise mission readiness |
| 11 | **Martian Time** | Follow a live Sol clock (Sol 184) |
| 12 | **The Next Chapter** | A long-term timeline for human presence: 2026, 2035, 2050+ |
| 12 | **The Road to Mars** | Track the mission across the solar system |
| 13 | **Mars Archive** | Browse a gallery of postcards from Mars with a lightbox view |
| 14 | **Survival Systems** | Monitor oxygen, water, radiation shield, power reserve and thermal control |
| 15 | **Navigation** | Move your pointer around an interactive compass to scan mission targets |
| 16 | **Mission Badges** | Earn five badges: First Contact, Mars Explorer, Base Builder, Life Detective, Mission Commander |
| 17 | **Photo of the Sol** | A Jezero-region view with visibility, wind and status readouts |
| — | **Mission Complete** | Calculate your final mission readiness score |

### Badges

| Badge | How to earn it |
|-------|----------------|
| 🛰️ First Contact | Transmit your first interplanetary message |
| 🤖 Mars Explorer | Inspect a rover system |
| 🏗️ Base Builder | Activate every habitat module |
| 🔬 Life Detective | Run a complete sample analysis |
| 🎖️ Mission Commander | Reach 90% mission readiness |

## Key Facts Shown in the Experience

- **Average distance:** about 225 million km
- **Transit time:** about 7 months
- **Average surface temperature:** about −63°C
- **Mission location:** Jezero Crater region

## Getting Started

Clone the repository and open it locally:

```bash
git clone https://github.com/krishnamagrawal05/mission-mars.git
cd mission-mars
```

Open `index.html` in your browser, or serve the folder with a local static server:

```bash
# Python
python3 -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000`.

## Deployment

The site is a static frontend hosted on **GitHub Pages**:

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the root folder.
4. Save. Your site will be live at `https://<your-username>.github.io/mission-mars/`.

## Project Structure

```
mission-mars/
├── index.html      # Main page
├── ...             # Styles, scripts and assets
└── README.md
```

> Update this tree to match your actual files and folders.

## Browser Support

Works best in modern browsers (Chrome, Edge, Firefox, Safari) on desktop and mobile.

## Disclaimer

All data in this project, including telemetry, crew roles, rover systems, sample analysis and mission timelines, is fictional and for entertainment and educational purposes only.

## Author

Made by [@krishnamagrawal05](https://github.com/krishnamagrawal05)

---

© 2026 MISSION: MARS — An Interactive Sci-Fi Experience
