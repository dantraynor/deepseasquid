# 🌊 Deep Sea Discovery: Colossal Squid Presentation

An interactive HTML presentation about the groundbreaking 2025 colossal squid discovery. Built with pure HTML, CSS, and JavaScript for maximum compatibility and visual impact.

## 🎬 [View Live Presentation](https://yourusername.github.io/deep-sea-discovery-presentation)

![Presentation Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📖 About

This presentation covers the historic first live footage of a colossal squid captured in March 2025 near the South Sandwich Islands. The interactive slides feature:

- **Cinematic ocean descent visualization**
- **Animated depth gauges and zone transitions**
- **Professional submarine/ROV interface styling**
- **Responsive design for any screen size**
- **Optimized for Zoom presentations**

## 🚀 Quick Start

### Option 1: Online Presentation

1. Visit the [live presentation](https://yourusername.github.io/deep-sea-discovery-presentation)
2. Click on any slide to open in full-screen
3. Press `F11` for presentation mode

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/deep-sea-discovery-presentation.git

# Navigate to folder
cd deep-sea-discovery-presentation

# Open in browser
open index.html
# or
python -m http.server 8000  # For local server
```

## ⚠️ Troubleshooting

### Links Not Working?

If clicking the slide links doesn't work, you need to serve the files via HTTP:

1. **Option 1: Use Python:**

   ```bash
   python3 -m http.server 8000
   ```

   Then open `http://localhost:8000`

2. **Option 2: Use Live Server extension in VS Code**
   - Install "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

3. **Option 3: Open files individually**
   - Drag HTML files directly into browser window
   - Navigate manually between slides

4. **Option 4: GitHub Pages**
   - Deploy to GitHub Pages for permanent hosting
   - Access via `https://yourusername.github.io/repository-name`

### Common Issues

- **Animations not smooth:** Close other browser tabs, use Chrome/Firefox
- **Responsive issues:** Test on actual device, not just browser resize
- **Font loading:** Ensure internet connection for Google Fonts
- **File protocol warning:** Use local server instead of opening files directly

## 📱 Slides Overview

| Slide | Title | Description | Features |
|-------|-------|-------------|----------|
| **01** | 🔒 **Classified Intro** | Mission briefing with classified document styling | Animated particles, sonar effects, glowing text |
| **02** | 🌊 **Ocean Descent** | Interactive journey through ocean zones | Depth gauge, zone cards, marine snow animation |

## 🎯 Presentation Instructions

### For Zoom/Online Presentations

1. **Screen Share** → Select "Share Screen" (entire screen)
2. **Open slides** in separate browser tabs
3. **Press F11** on each slide for full-screen mode
4. **Use Alt+Tab** to switch between slides smoothly
5. **Click on descent slide** to advance through ocean zones

### Keyboard Controls

- `F11` - Full-screen mode
- `Alt+Tab` - Switch between slides
- `Click` - Advance through ocean zones (Slide 2)
- `Esc` - Exit full-screen

### Pro Tips

- **Test beforehand** with actual Zoom screen share
- **Close other applications** for better performance
- **Good internet connection** recommended for smooth animations
- **Chrome or Firefox** for best compatibility

## 🛠️ Technical Details

## 📁 File Structure

```
deep-sea-discovery-presentation/
├── 📄 index.html              # Main navigation page
├── 📄 figma_intro_slide.html  # Slide 1: Classified intro
├── 📄 figma_descent_slide.html # Slide 2: Ocean descent
├── 📄 README.md               # This file
└── 📄 LICENSE                 # MIT License
```

## 🎨 Design System

### Color Palette

```css
--deep-ocean: #0A0E27        /* Primary background */
--midnight-blue: #1A237E     /* Secondary background */
--bioluminescent: #00E5FF    /* Accent/highlights */
--ice-white: #E3F2FD         /* Primary text */
--seafoam: #81C784           /* Secondary text */
--danger-red: #FF4444        /* Alerts/classified */
```

### Typography

- **Headers:** Orbitron (Futuristic, tech feel)
- **Body:** Inter (Clean, readable)
- **Data/Code:** JetBrains Mono (Monospace, technical)

## 🔧 Customization

### Adding New Slides

1. Create new HTML file using existing slides as templates
2. Follow design system colors and fonts
3. Update navigation links in `index.html`

### Modifying Animations

- Animation duration: Adjust `animation-duration` in CSS
- Easing functions: Change `ease-in-out` to `linear`, `ease`, etc.
- Disable animations: Add `prefers-reduced-motion` media query
