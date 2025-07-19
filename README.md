# War Card Game

A simple web-based implementation of the classic card game "War" built with HTML, CSS, and JavaScript.

## 🎮 Game Overview

War is a simple card game typically played between two players. In this digital version, you play against the computer. Each round, both players draw a card, and the player with the higher card wins the round. The game continues until all cards are drawn, and whoever has won more rounds wins the game!

## 🚀 Features

- **Interactive Gameplay**: Click to draw cards and play against the computer
- **Real-time Scoring**: Track your score vs the computer's score
- **Card Counter**: See how many cards remain in the deck
- **Game End Detection**: Automatic winner determination when deck is empty
- **Responsive Design**: Clean, card table-inspired green background
- **New Game Option**: Start fresh with a new shuffled deck anytime

## 🎯 How to Play

1. Click **"New Deck"** to start a fresh game with a shuffled deck of 52 cards
2. Click **"Draw"** to draw two cards (one for you, one for the computer)
3. The player with the higher card wins the round and gets a point
4. If both cards have the same value, it's a "War!" (tie - no points awarded)
5. Continue drawing until all cards are used
6. The player with the most points at the end wins the game!

## 🏗️ Project Structure

```
├── WAR-CARD-GAME.html    # Main HTML structure
├── WAR-CARD-GAME.css     # Styling and layout
├── WAR-CARD-GAME.js      # Game logic and API interactions
└── README.md             # This file
```

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Game structure and layout
- **CSS3**: Styling with Flexbox layout and custom card styling
- **JavaScript (ES6+)**: Game logic, API calls, and DOM manipulation
- **Deck of Cards API**: External API for card deck management

### Key Components

#### HTML Structure
- Game header and score displays
- Two card slots for displaying drawn cards
- Control buttons (New Deck, Draw)
- Remaining cards counter

#### CSS Features
- Dark green felt-like background mimicking a card table
- Responsive card slots with proper aspect ratios
- Exo 2 Google Font for modern typography
- Hover effects and disabled button states

#### JavaScript Functionality
- Fetches new shuffled deck from API
- Handles card drawing and display
- Implements card value comparison logic
- Manages game state and scoring
- Determines winner when game ends

### Card Value Hierarchy
```
2 < 3 < 4 < 5 < 6 < 7 < 8 < 9 < 10 < JACK < QUEEN < KING < ACE
```

## 🌐 API Integration

This game uses the [Deck of Cards API](https://deckofcardsapi.com/) provided by Scrimba:
- **New Deck**: `https://apis.scrimba.com/deckofcards/api/deck/new/shuffle/`
- **Draw Cards**: `https://apis.scrimba.com/deckofcards/api/deck/{deck_id}/draw/?count=2`

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open** `WAR-CARD-GAME.html` in any modern web browser
3. **Click "New Deck"** to initialize the game
4. **Start playing** by clicking "Draw"!

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection (for API calls and Google Fonts)

## 🎨 Customization

### Styling
- Modify `WAR-CARD-GAME.css` to change colors, fonts, or layout
- Card slot dimensions can be adjusted via the `.card-slot` class
- Background color and theme can be modified in the `body` styles

### Game Logic
- Card values and hierarchy can be modified in the `valueOptions` array
- Scoring system can be customized in the `determineCardWinner` function
- Add additional game features like war resolution for tied cards


## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Acknowledgments

- [Deck of Cards API](https://deckofcardsapi.com/) for providing the card deck service
- [Google Fonts](https://fonts.google.com/) for the Exo 2 font family
- Inspired by the classic card game War

---

**Enjoy the game!** 🃏✨
