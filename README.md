# 🍸 Cocktail Bar Landing Page

A premium, interactive scrolling landing page built with React, Vite, and GSAP. This project serves as a highly immersive web experience featuring custom animations, scroll-triggered video playback, and modern responsive design.

## 🚀 Features

- **Immersive GSAP Animations**: Text splitting (`SplitText`) and scroll-driven animations (`ScrollTrigger`) seamlessly animate content as you scroll.
- **Scroll-Scrubbed Video Background**: Features a video element pinned and scrubbed on scroll, syncing video playback to the user's scroll position.
- **Modern UI & Aesthetic**: Built with Tailwind CSS v4, text gradients, noisy background textures, and a custom UI designed to feel premium.
- **Responsive Layouts**: Fully responsive experience optimized for both desktop and mobile devices using `react-responsive`.
- **Fast Development Experience**: Powered by React 19 and Vite for extremely fast Hot Module Replacement (HMR).

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations**: [GSAP](https://gsap.com/) & `@gsap/react` 
  - *Included Plugins*: `ScrollTrigger`, `SplitText`
- **Responsiveness**: `react-responsive`

## 📂 Project Structure

```text
src/
├── components/          # Reusable React components
│   ├── About.jsx        # About section
│   ├── Art.jsx          # Art / Story section
│   ├── Cocktails.jsx    # Showcase of cocktails
│   ├── Contact.jsx      # Contact information 
│   ├── Hero.jsx         # Hero section with animated titles and scroll-bound video
│   ├── Menu.jsx         # Menu section
│   └── Navbar.jsx       # Navigation bar
├── App.jsx              # Main application layout grouping the sections
├── index.css            # Global CSS styles including Tailwind imports and custom utilities
└── main.jsx             # React entry point
```

## 🏃‍♂️ Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (version 18+ recommended) installed on your machine.

### Installation

1. Clone this repository or download the project files.
2. Install the necessary dependencies:

```bash
npm install
```

*Note: This project imports premium GSAP plugins (`SplitText`). Ensure your environment has access to the GSAP Club plugins if rebuilding.*

### Running the Project

Start the Vite development server:

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the interactive application.

### Building for Production

To create an optimized production build:

```bash
npm run build
```

This will generate a `dist` directory with your compiled assets. You can preview the production build locally using:

```bash
npm run preview
```

## 🎨 Design & Animation Notes

- The project relies heavily on **GSAP ScrollTrigger** to create an engaging continuous narrative and animate UI elements into view as the user scrolls.
- **Video Scrubbing**: In the Hero section, a background video's playback (`currentTime`) is scrubbed directly according to the scroll percentage, syncing visual motion to the scroll wheel.
- Custom typography, CSS variables, and layout aesthetics are maintained in `index.css` working alongside standard Tailwind classes to produce the unique visual flavor.
