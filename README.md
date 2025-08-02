# WhaleArena

**WhaleArena** is a visually stunning, competitive learning platform built to enhance the experience of students participating in webathons and other technology-driven competitions. This project features a custom UI/UX with animated cursors, glowing gradients, smooth transitions, and a personalized dashboard, all designed to make competitive learning more engaging.

---

## Features

- **Custom Animated Cursor**  
  Unique cursor design with trailing effects, click ripples, and glowing highlights for an immersive experience.

- **Multi-Page SPA Architecture**  
  Seamless navigation between Login, Loading, Dashboard, Progress, Explore, Profile, Social, and Discover/Creation pages.

- **Student Dashboard**  
  Personalized dashboard displaying webathon stats, teams, progress, streaks, rank, and more.

- **Modern UI Components**  
  Stylish cards, buttons, badges, and navigation bars with gradient backgrounds and hover animations.

- **Background Effects**  
  Floating particles, animated radial gradients, and smooth transitions for a lively background.

- **Responsive Design**  
  Mobile-friendly layouts with adaptive typography and spacing.

- **Dark Mode Support**  
  Dynamic theming via CSS custom properties and variants.

- **Intuitive Keyboard Shortcuts**  
  Quickly switch between pages using `Ctrl`/`Cmd` + number keys.

---

## Tech Stack

- **Frontend:**  
  - HTML, CSS (custom properties, Tailwind, oklch color model)
  - TypeScript + React (with motion/animation libraries)
  - Vanilla JS for cursor and animation logic

- **Styling:**  
  - Custom CSS variables and variants for dark/light mode
  - TailwindCSS for utility classes and rapid prototyping

- **Animation:**  
  - Framer Motion (for React TSX version)
  - Vanilla JS transitions and effects

---

## Structure

```
WhaleArena/
├── HTML               # Main HTML layout and structure
├── CSS_WhaleArena     # Custom CSS variables, theming, typography, and animation utilities
├── JS                 # Main app logic, cursor, navigation, background effects
├── TSX_WhaleArena     # React/TypeScript SPA implementation (for advanced UI & animation)
├── README.md          # You're reading it!
```

---

## Quick Start

### Static Demo

1. Clone the repo:
    ```bash
    git clone https://github.com/Crimson-rain-flower/WhaleArena.git
    cd WhaleArena
    ```

2. Open the `HTML` file in your browser  
   (Make sure the referenced CSS and JS files are available in your project folder.)

### React/TSX Version

1. Install dependencies (if using the React/TSX version):
    ```bash
    npm install
    ```

2. Run the development server:
    ```bash
    npm start
    ```

3. Open [http://localhost:3000](http://localhost:3000) to view in the browser.

---

## Customization

- **Branding:**  
  Change images, colors, and logos in the HTML/CSS files to match your institution or competition.

- **Student Data:**  
  The demo uses mock data for students. Integrate with your backend or database for real authentication and dynamic stats.

- **Add New Pages:**  
  Expand the navigation and add new components for features like leaderboards, resources, or announcements.

---

## Keyboard Shortcuts

- `Ctrl`/`Cmd` + `1`: Dashboard
- `Ctrl`/`Cmd` + `2`: Progress
- `Ctrl`/`Cmd` + `3`: Explore
- `Ctrl`/`Cmd` + `4`: Profile
- `Ctrl`/`Cmd` + `5`: Social
- `Ctrl`/`Cmd` + `6`: Discover/Create
- `Escape`: Go to Dashboard/Main (if logged in)

---

## Credits

- **Design & Development:**  
  Ananya and Sabina

- **Images:**  
  Unsplash (whale images), Google Fonts (Inter), Pinterest, Canva

- **Animation:**  
  Framer Motion, TailwindCSS, custom JS, Pinterest, Figma

---

## License

This project is for educational and demonstration purposes.  
Feel free to fork, modify, or contribute!

---

## Contributions

Pull requests and feedback are welcome!  
If you build something cool with WhaleArena, let us know.
