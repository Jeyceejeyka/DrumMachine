# Drum Machine

A React-based Drum Machine app built with Vite. This app allows users to play different drum sounds by clicking on buttons or pressing corresponding keyboard keys. It also displays the name of the sound being played.

---

## Features

- **Responsive Design**: Works on both desktop and mobile devices.
- **Interactive UI**: Users can trigger sounds via mouse clicks or keyboard input.
- **Real-time Display**: Displays the name of the sound being played.

---

## Live Demo

The app is deployed on GitHub Pages:
[Drum Machine](https://Jeyceejeyka.github.io/DrumMachine)

---

## User Stories

1. I should see an outer container with `id="drum-machine"` that contains all other elements.
2. Within `#drum-machine`, I can see an element with `id="display"`.
3. I can see 9 clickable drum pad elements with a class of `drum-pad`.
   - Each has a unique `id` that describes the audio clip it triggers.
   - Each drum pad contains text corresponding to a specific keyboard key (Q, W, E, A, S, D, Z, X, C).
4. Each `.drum-pad` contains an `<audio>` element with:
   - A `src` attribute pointing to an audio file.
   - A class of `clip`.
   - An `id` matching the parent `.drum-pad` text.
5. Clicking a `.drum-pad` plays the associated sound.
6. Pressing the corresponding key on the keyboard plays the associated sound.
7. Triggering a sound updates the `#display` with the name of the sound.

---

## Installation

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Jeyceejeyka/DrumMachine.git
   cd DrumMachine
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and go to:
   ```
   http://localhost:5173
   ```

---

## Deployment

The app is deployed to GitHub Pages. To deploy:

1. Install the `gh-pages` package:
   ```bash
   npm install --save-dev gh-pages
   ```

2. Add the following to `package.json`:
   ```json
   "homepage": "https://Jeyceejeyka.github.io/DrumMachine",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

3. Build and deploy the app:
   ```bash
   npm run deploy
   ```

4. Enable GitHub Pages in the repository settings, and set the source to the `gh-pages` branch.

---

## Project Structure

```
DrumMachine/
├── public/             # Static assets
├── src/                # Source code
│   ├── components/     # Reusable components
│   ├── App.css         # Styles
│   ├── App.jsx         # Main app component
│   └── index.jsx       # Entry point
├── package.json        # Project metadata and scripts
└── vite.config.js      # Vite configuration
```

---

## Technologies Used

- **Frontend**: React, Vite
- **Styling**: CSS
- **Deployment**: GitHub Pages

---

## Future Improvements

- Add volume control.
- Implement a visual indicator when a drum pad is pressed.
- Add more drum sounds and pads.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Author

Developed by [Jeyceejeyka](https://github.com/Jeyceejeyka).

