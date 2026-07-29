# 🤖 BOTLEAGUE | India's Ultimate Robotics Arena

[![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5.1.4-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

**BotLeague** is a highly responsive, premium sci-fi themed landing page for India's premier robotics sports and professional tournament league. Designed to serve as a national ecosystem for robotics, the platform showcases competitive disciplines, player leaderboards, event schedules, team brackets, and career opportunities for engineers and makers.

---

## 🚀 Key Features

*   **🎮 Competition Disciplines & Arena:** Visual grids detailing various esports-style robotics categories:
    *   *Robo Race* & *Robo War*
    *   *Line Follower*
    *   *RC Racing*
    *   *FPV Drone Racing & Aeromodelling*
    *   *Robo Hockey*
*   **⚔️ Real-time Bracket & Live Events:** Interactive tournament grids highlighting active regional status, upcoming regional registrations (e.g. Mumbai, Delhi), and past event results.
*   **🏆 National Leaderboard Mockup:** Gamified player profile display showcasing scores, rank badges, and user engagement metrics.
*   **📂 Structured Career Pathway & Benefits:** Modules highlighting why robotics engineers should register, tracking digital identities, and bridging the gap between victory in the arena and real-world tech opportunities.
*   **⏳ User Journey Roadmap:** Steps guiding users from team construction to active league participation.

---

## 🛠️ Tech Stack & Design System

The application is built on modern web technologies ensuring rapid development, robust performance, and responsiveness:

*   **Framework:** [React 18](https://react.dev/) (Functional Components with TypeScript)
*   **Build Tool:** [Vite](https://vitejs.dev/) for extremely fast hot module replacement (HMR) and optimized assets packaging.
*   **Styling:** [Tailwind CSS v3](https://tailwindcss.com/) paired with [PostCSS](https://postcss.org/) and [Autoprefixer](https://github.com/postcss/autoprefixer).
*   **Typography:** Hosted Google Fonts featuring:
    *   `Orbitron` - Sci-fi high-tech headers
    *   `Rajdhani` - Secondary labels
    *   `Inter` - Clean and readable body text
*   **Icons:** [Lucide React](https://lucide.dev/) for sleek, modern SVG icons.

---

## 📂 Project Structure

Below is the directory map of the codebase to help you find your way around:

```text
BotLeague-main/
├── public/                 # Static public assets (e.g., favicon)
├── src/
│   ├── assets/             # Images and background illustration resources
│   ├── components/         # Reusable React UI blocks and sections
│   │   ├── About.tsx       # Core features overview & node diagram
│   │   ├── Categories.tsx  # Maker & Engineer category segments
│   │   ├── Competitions.tsx# Tournaments status, brackets, and registrations
│   │   ├── Disciplines.tsx # Robotics sports cards with custom SVGs
│   │   ├── Footer.tsx      # Standard links & contact details
│   │   ├── Hero.tsx        # Hero banner with glowing actions & headlines
│   │   ├── JoinSection.tsx # Final registration CTA block
│   │   ├── Navbar.tsx      # Sticky tech navbar with auto-scrolling anchors
│   │   ├── Sponsors.tsx    # Partners and brand logos list
│   │   ├── Timeline.tsx    # Interactive step-by-step user journey
│   │   └── WhyRegister.tsx # League advantage list & Leaderboard card
│   ├── App.tsx             # Root component stitching sections together
│   ├── index.css           # Global custom CSS rules (scrollbar & glow effects)
│   ├── main.tsx            # Application entry point mounting the React tree
│   └── vite-env.d.ts       # TypeScript type declarations for Vite env variables
├── index.html              # Main HTML skeleton containing external Google Fonts
├── package.json            # Scripts & project dependencies configurations
├── tailwind.config.js      # Tailored Tailwind theme parameters & gradients
├── tsconfig.json           # Compiler rules for TypeScript
└── vite.config.ts          # Build options for Vite
```

---

## 🏁 Getting Started

### 📋 Prerequisites
Ensure you have [Node.js](https://nodejs.org/) (v18 or higher recommended) and `npm` installed.

### 📥 Installation
1. Clone the project and navigate to the project directory:
   ```bash
   cd BotLeague-main
   ```
2. Install all development and production dependencies:
   ```bash
   npm install
   ```

### ⚙️ Available Scripts

Run these scripts from the project root using npm:

| Script | Description | Command |
| :--- | :--- | :--- |
| `dev` | Starts the local dev server at `http://localhost:5173` | `npm run dev` |
| `build` | Compiles TypeScript and runs Vite build to generate production files | `npm run build` |
| `lint` | Analyzes source code for ESLint style and programmatic warnings | `npm run lint` |
| `preview` | Serves the production build folder locally for review | `npm run preview` |

---

## 🎨 Customizing Design & Accents

Custom neon borders, glow text shadows, and specialized backgrounds are defined inside:
*   [index.css](file:///c:/Users/Mohit%20Khairnar/Downloads/BotLeague-main/BotLeague-main/src/index.css): Modify `.glow-text-red`, `.shadow-red-glow`, or scrollbars.
*   [tailwind.config.js](file:///c:/Users/Mohit%20Khairnar/Downloads/BotLeague-main/BotLeague-main/tailwind.config.js): Customize Tailwind's theme extensions, fonts, gradients, or colors (e.g. key accent color `#FF3B5C`).