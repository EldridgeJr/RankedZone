# RankedZone

A modern, animated gaming landing page built with React and cutting-edge web technologies. RankedZone delivers an immersive visual experience with smooth scroll-based animations, interactive video transitions, and a bold design language inspired by the gaming and Web3 universe.

## Preview

The site features a full-screen hero section with dynamic video playback, a bento-grid feature showcase, an interactive story section with 3D tilt effects, and a stylized contact area.

## Tech Stack

- **React 19** — UI framework
- **Vite** — Build tool with HMR
- **Tailwind CSS** — Utility-first styling
- **GSAP** — Scroll-triggered and timeline-based animations
- **React Icons** — Icon library

## Features

- Scroll-driven clip-path and border-radius animations on the hero section
- Interactive mini-video player with click-to-expand transitions
- Bento-grid layout with 3D tilt effect on mouse movement
- Animated titles with per-word reveal on scroll
- Responsive design optimized for mobile and desktop

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation
```bash
git clone https://github.com/your-username/rankedzone.git
cd rankedzone
npm install
```

### Development
```bash
npm run dev
```

Opens the app at `http://localhost:5173`.

### Production Build
```bash
npm run build
npm run preview
```

## Project Structure
```
src/
├── App.jsx              # Main app component
├── main.jsx             # Entry point
├── index.css            # Global styles & custom fonts
└── components/
    ├── Hero.jsx         # Hero section with video transitions
    ├── About.jsx        # About section
    ├── Features.jsx     # Bento-grid feature cards
    ├── Story.jsx        # Interactive story section with 3D tilt
    ├── Contact.jsx      # Contact CTA section
    ├── Navbar.jsx       # Navigation bar
    ├── Footer.jsx       # Footer
    ├── Button.jsx       # Reusable button component
    ├── AnimatedTitle.jsx# Scroll-animated title component
    └── RoundedCorners.jsx # SVG rounded corner helper
```

## License

This project is for personal/educational use.
