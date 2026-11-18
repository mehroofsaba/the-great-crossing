# The Great Crossing

_A river-crossing puzzle adventure where every move matters._

**The Great Crossing** is a browser-based puzzle game inspired by the classic Missionaries and Cannibals problem. Your task is to guide six travellers — three missionaries and three cannibals - safely across a river using a small boat, while making sure that nobody is left in danger.

It sounds simple. The challenge is making every crossing count.

---

## About the Game

A group of three missionaries and three cannibals needs to cross a river. They have only one boat, and it can carry a maximum of two passengers at a time.

There is one important condition: whenever missionaries are present on either riverbank, they must never be outnumbered by cannibals.

Plan your crossings carefully, choose your passengers wisely, and get everyone safely to the other side.

## Game Rules

- There are **3 missionaries** and **3 cannibals**.
- Everyone begins on the starting riverbank.
- The boat can carry a maximum of **2 passengers**.
- The boat cannot cross the river empty.
- The boat must be operated from the bank where it is currently located.
- Cannibals must never outnumber missionaries on either bank when missionaries are present.
- The objective is to transport all six travellers safely to the opposite bank.

Breaking the safety condition results in an invalid game state.

## Features

- **Interactive River-Crossing Gameplay** — Move passengers between two riverbanks using the boat.
- **Classic Puzzle Mechanics** - Experience the traditional Missionaries and Cannibals challenge.
- **Rule Validation** - Keep track of passenger combinations and maintain safe conditions on both banks.
- **Visual Game Environment** - A side-view river-crossing scene brings the puzzle to life.
- **Standalone Browser Experience** - Play directly in a modern web browser without installing dependencies.
- **Responsive Presentation** - Designed to be accessible through a browser on different screen sizes.

## Visual Direction

The game uses an illustrated storybook-inspired visual direction rather than a conventional arcade aesthetic.

Its visual identity focuses on:

- Warm, natural colours and earthy tones.
- Illustrated landscapes and river scenery.
- A wooden boat and two visible riverbanks.
- Expressive character illustrations.
- A calm, adventure-book atmosphere.

The intention is to make a classic logic puzzle feel like a small interactive adventure.

## Technology Stack

| Technology             | Purpose                                  |
| ---------------------- | ---------------------------------------- |
| HTML5                  | Game structure and content               |
| CSS3                   | Styling, layout, and visual presentation |
| JavaScript             | Game interactions and puzzle logic       |
| SVG / Browser graphics | Visual elements, where used              |
| Google Fonts           | Typography                               |

The project is designed as a lightweight, standalone browser experience without requiring a backend, database, or framework installation.

## Run Locally

You can run The Great Crossing directly on your computer.

### Option 1: Open in a browser

1. Clone the repository:

   ```bash
   git clone https://github.com/mehroofsaba/the-great-crossing.git
   ```

2. Navigate into the project directory:

   ```bash
   cd the-great-crossing
   ```

3. Open `index.html` in any modern web browser.

That's it! No package installation or build process is required.

### Option 2: Use VS Code

1. Open the cloned project folder in VS Code.
2. Open `index.html`.
3. Run it using the Live Server extension, or open the file directly in your browser.

### Browser Compatibility

The game is intended for modern browsers such as:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

Google Fonts are loaded when an internet connection is available. If offline, the browser uses fallback system serif fonts.

## Project Structure

```text
the-great-crossing/
│
├── index.html
├── README.md
└── .git/
```

The game is currently organised as a standalone HTML experience, with its implementation contained in `index.html`.

## Live Demo

The project is deployed and available to play online:

<p align="center">
  <a href="https://the-great-crossing.onrender.com">
    <strong>Play The Great Crossing</strong>
  </a>
</p>

---

_One river. Six travellers. One boat. Every move counts._

Built as an exploration of interactive browser-based game development, visual storytelling, and classic logic puzzles.
