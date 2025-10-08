# 🐑 Shepherdy - The Ultimate Trivia Game

A stunning, interactive Jeopardy-style trivia game inspired by the Good Shepherd Sisters, featuring a cosmic theme with metallic 3D text effects and immersive audio.

## ✨ Features

### 🎮 Game Features
- **6 Categories**: Provinces, Dates, Foundress's Quotations, Scripture, Songs & Baseball Team, and Sheep
- **30 Questions**: 5 questions per category with values from $200 to $1000
- **3-Player Support**: Track scores for up to 3 players/teams
- **Interactive Scoring**: Correct, Incorrect, and Pass options with sound effects
- **Audio Support**: Built-in audio with fallback beep sounds
- **Responsive Design**: Works on desktop, tablet, and mobile devices

### 🎨 Visual Design
- **Cosmic Background**: Multi-layered gradient with animated stars
- **Metallic 3D Title**: Animated "SHEPHERDY" with chrome-like effects
- **Grid Overlay**: Futuristic grid pattern matching PowerPoint design
- **Smooth Animations**: Hover effects, transitions, and modal animations
- **Professional Styling**: Game show-quality visual effects

### 🔊 Audio Features
- **Question Audio**: Each question can have associated audio files
- **Sound Effects**: Different tones for correct, incorrect, and pass answers
- **Audio Toggle**: Enable/disable audio with a single click
- **Fallback Sounds**: Web Audio API-generated sounds when files aren't available

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required - runs entirely in the browser

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. Start playing immediately!

### File Structure
```
shepherdy/
├── index.html          # Main game page
├── script.js           # Game logic and functionality
├── styles.css          # Styling and animations
├── score-tracker.html  # Standalone score tracking page
├── pastoral-sheep-bg.svg # Background SVG asset
└── README.md           # This file
```

## 🎯 How to Play

### Basic Gameplay
1. **Choose a Question**: Click on any dollar amount in the game board
2. **Read the Question**: The question will appear in a modal window
3. **Show Answer**: Click "Show Answer" to reveal the correct answer
4. **Score the Answer**: Choose from:
   - **Correct (+$X)**: Player gets the points
   - **Incorrect (-$X)**: Player loses the points
   - **Pass (No Change)**: No points awarded or deducted
5. **Next Player**: The game automatically moves to the next player

### Game Controls
- **🔊 Audio Toggle**: Enable/disable sound effects
- **🔄 Reset Game**: Clear all scores and reset the board
- **Keyboard Shortcuts**:
  - `Enter`: Show answer or close modal
  - `Escape`: Close modal

### Scoring System
- **Correct Answer**: +$X points (where X is the question value)
- **Incorrect Answer**: -$X points
- **Pass**: No change in score
- **Minimum Score**: Scores cannot go below $0

## 📋 Categories & Questions

### 🏛️ Provinces
Questions about Good Shepherd Sisters province leaders and organizational history.

### 📅 Dates
Historical dates related to the Good Shepherd Sisters' establishment and milestones.

### 📖 Foundress's Quotations
Biblical quotes and scripture passages related to shepherding themes.

### ✝️ Scripture
Religious and spiritual content including feast days and mission statements.

### ⚾ Songs & Baseball Team
Baseball team identification questions (fun category for variety).

### 🐑 Sheep
Facts about sheep, including breeds, anatomy, and characteristics.

## 🛠️ Customization

### Adding Audio Files
1. Create an `audio/` folder in your project directory
2. Add MP3 files with the naming convention: `[category]_[value].mp3`
3. Example: `provinces_200.mp3`, `scripture_1000.mp3`

### Modifying Questions
Edit the `gameData` object in `script.js` to:
- Change question text
- Update answers
- Modify point values
- Add new categories

### Styling Changes
Modify `styles.css` to:
- Change color schemes
- Adjust animations
- Update fonts
- Modify layout

## 🎨 Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with gradients, animations, and transforms
- **JavaScript (ES6+)**: Modern JavaScript with Web Audio API
- **Web Audio API**: Dynamic sound generation
- **CSS Grid**: Responsive layout system

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance Features
- Optimized animations with CSS transforms
- Efficient event handling
- Minimal DOM manipulation
- Responsive design with mobile-first approach

## 🎵 Audio System

The game includes a sophisticated audio system:

### Audio Files
- Place MP3 files in the `audio/` directory
- Use the naming convention: `[category]_[value].mp3`
- Supported categories: provinces, dates, quotations, scripture, baseball, sheep

### Fallback Audio
When audio files are not available, the game generates sounds using the Web Audio API:
- **Question Sound**: 800Hz sine wave
- **Correct Answer**: Rising chord (C-E-G)
- **Incorrect Answer**: Low sawtooth wave
- **Pass**: Triangle wave

## 📱 Mobile Support

The game is fully responsive and includes:
- Touch-friendly interface
- Optimized button sizes
- Responsive grid layout
- Mobile-specific styling adjustments

## 🤝 Contributing

Feel free to contribute to the Shepherdy game by:
- Adding new questions and categories
- Improving the visual design
- Enhancing audio features
- Optimizing performance
- Adding new game modes

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Inspired by the Good Shepherd Sisters and their mission
- Based on the classic Jeopardy! game format
- Designed with accessibility and inclusivity in mind

---

**Enjoy playing Shepherdy! 🐑✨**

For questions or support, please refer to the game's built-in help or contact the development team.