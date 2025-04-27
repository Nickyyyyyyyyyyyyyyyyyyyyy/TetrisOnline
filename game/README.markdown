# Modern Tetris

A modern implementation of the classic Tetris game built with HTML, CSS (TailwindCSS), and JavaScript. Features include touch controls, sound effects, and a responsive design.

## Demo

Play the game live at: [Insert GitHub Pages URL after deployment, e.g., https://your-username.github.io/tetris-game]

## Features

- Classic Tetris gameplay with modern UI
- Keyboard and touch controls (swipe gestures)
- Sound effects (toggleable)
- Hold piece, next piece preview, and ghost piece
- Score, level, and lines tracking
- Responsive design for mobile and desktop

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/tetris-game.git
   cd tetris-game
   ```

2. **Run Locally**:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox).
   - Alternatively, use a local server for better performance:
     ```bash
     npx http-server
     ```
     Then navigate to `http://localhost:8080`.

## Deployment on GitHub Pages

1. Push the repository to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to your repository on GitHub.
   - Navigate to **Settings** > **Pages**.
   - Set the source to the `main` branch and root directory.
   - Save, and GitHub will provide a URL (e.g., `https://your-username.github.io/tetris-game`).

## Controls

- **Keyboard**:
  - Left Arrow / A: Move left
  - Right Arrow / D: Move right
  - Down Arrow / S: Soft drop
  - Up Arrow / W: Rotate
  - Space: Hard drop
  - Shift / C: Hold piece
  - P / Esc: Pause
- **Touch**:
  - Swipe left/right/down: Move
  - Swipe up / Tap: Rotate

## Dependencies

- [TailwindCSS](https://tailwindcss.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) (via CDN)
- Audio files from [Mixkit](https://mixkit.co/)

## License

[MIT License](LICENSE)

## Contributing

Feel free to submit issues or pull requests to improve the game!