# 🎯 Ultimate Tic-Tac-Toe

> A modern, feature-rich tic-tac-toe game with AI opponents, tournament mode, custom themes, and complete save/load functionality - all in a single HTML file!


## ✨ Features

### 🎮 **Game Modes**
- **👥 Two Player Mode**: Classic human vs human gameplay
- **🤖 AI Opponent**: Challenge yourself against advanced AI with 4 difficulty levels
  - 😊 **Easy AI**: Random moves for casual play
  - 🤔 **Medium AI**: 70% strategic, 30% random moves
  - 😈 **Hard AI**: Advanced minimax algorithm (depth 6)
  - 💀 **Impossible AI**: Full-depth minimax - nearly unbeatable!
- **🏆 Tournament Mode**: Organize tournaments with 4 or 8 players

### 🎨 **Visual Experience**
- **4 Stunning Themes**: Ocean 🌊, Space 🌌, Sunset 🌅, Forest 🌲
- **Animated Background**: Floating particles with smooth animations
- **Enhanced Animations**: Move trails, confetti celebrations, board shakes
- **3D Effects**: Hover animations with realistic depth
- **Glassmorphism Design**: Modern frosted glass aesthetic
- **AI Visual Indicators**: Spinning robot icons and move previews
- **Responsive Layout**: Perfect on desktop, tablet, and mobile

### 🏆 **Tournament System**
- **Bracket Visualization**: See the complete tournament structure
- **Automatic Progression**: Seamless match transitions
- **Draw Handling**: Replays matches that end in draws
- **Champion Celebration**: Special announcements for winners
- **Progress Tracking**: Visual indicators for current and completed matches

### 👤 **Customization**
- **Custom Player Names**: Personalize your gaming experience
- **Real-time Updates**: Names update instantly across the interface
- **Persistent Identity**: Names carry through tournaments and saves

### 💾 **Save & Load System**
- **Local Storage**: Automatic saving to browser storage
- **Multiple Saves**: Create and manage multiple save files
- **Complete State**: Preserves scores, names, tournament progress
- **Export/Import**: Backup and share your game data
- **Save Management**: Organize and delete saves with timestamps

### 🎵 **Audio & Feedback**
- **Victory Sounds**: Enhanced Web Audio API with chord progressions
- **Visual Feedback**: Winning combinations highlight with golden glow
- **Smart Notifications**: Beautiful slide-in notifications system
- **Move Analytics**: Track moves and display winning combinations
- **Enhanced Animations**: Move trails, confetti rain, score pulsing
- **Interactive Effects**: Board shake on errors, AI thinking indicators

## 🚀 Quick Start

### Option 1: Direct Download
1. Download `tic-tac-toe.html`
2. Open in any modern web browser
3. Start playing immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/ultimate-tic-tac-toe.git
cd ultimate-tic-tac-toe
open tic-tac-toe.html
```

### Option 3: Live Demo
Open the file directly in your browser - no server required!

## 🎯 How to Play

### **Basic Gameplay**
1. **Choose Mode**: Select between 2-Player, AI, or Tournament
2. **Set Names**: Enter custom player names (optional)
3. **Pick Theme**: Choose your favorite visual theme
4. **Make Moves**: Click cells or type numbers 1-9 + Enter
5. **Win**: Get three in a row (horizontal, vertical, or diagonal)

### **AI Mode**
- Switch to "🤖 vs AI" mode
- Choose difficulty: Easy (random), Medium (70% strategic, 30% random), Hard (advanced minimax), Impossible (full-depth minimax)
- Play as X, AI plays as O
- Watch the "🤔 AI is thinking..." animation

### **Tournament Mode**
1. Click "🏆 Tournament" mode
2. Select 4 or 8 players
3. Click "🚀 Start" to begin
4. Play through the bracket system
5. Crown a champion!

### **Save & Load**
- **Save**: Enter name → Click "Save"
- **Load**: Select from dropdown → Auto-loads
- **Export**: Download JSON backup file
- **Import**: Upload JSON file to restore saves

## 🎨 Themes Gallery

| Theme | Description | Best For |
|-------|-------------|----------|
| 🌊 **Ocean** | Blue gradient with flowing particles | Default, calming gameplay |
| 🌌 **Space** | Dark cosmic theme with stars | Night gaming, focus mode |
| 🌅 **Sunset** | Warm pink/purple gradients | Relaxed, artistic feel |
| 🌲 **Forest** | Green nature-inspired colors | Fresh, natural atmosphere |

## 🤖 AI Strategy

The AI now features **4 distinct difficulty levels** using advanced algorithms:

### **😊 Easy Mode**
- **Random Moves**: Completely random selection for beginners
- **No Strategy**: Perfect for learning the game

### **🤔 Medium Mode** 
- **Hybrid Approach**: 70% strategic minimax, 30% random
- **Shallow Analysis**: Minimax with depth 3
- **Balanced Challenge**: Strategic but beatable

### **😈 Hard Mode**
- **Advanced Minimax**: Full minimax algorithm with depth 6
- **Alpha-Beta Pruning**: Optimized for speed and efficiency
- **Position Evaluation**: Sophisticated board scoring system
- **Strategic Depth**: Looks 6 moves ahead

### **💀 Impossible Mode**
- **Perfect Play**: Full-depth minimax (depth 9)
- **Optimal Strategy**: Mathematically perfect moves
- **Unbeatable**: Will force draws in most scenarios
- **Ultimate Challenge**: For expert players only

### **Core AI Features:**
1. **🎯 Win Detection**: Prioritizes immediate winning moves
2. **🛡️ Threat Blocking**: Prevents opponent victories
3. **🎲 Position Scoring**: 
   - Center position: +3 points
   - Corner positions: +2 points  
   - Side positions: +1 point
4. **🧠 Future Analysis**: Evaluates all possible game continuations
5. **⚡ Alpha-Beta Pruning**: Eliminates unnecessary calculations
6. **🎭 Realistic Timing**: Difficulty-based thinking delays

The **Hard** and **Impossible** modes use genuine game theory and will challenge even experienced players!

## ✨ Enhanced Animations & Effects

### **Interactive Animations**
- **🎯 Move Trails**: Golden ripple effects appear when clicking cells
- **🤖 AI Thinking Indicators**: Spinning robot icons appear in random cells during AI turns
- **📱 Move Previews**: AI moves show preview animation before committing
- **🌟 Board Shake**: Error feedback with shake animation for invalid moves
- **💫 Cell Shimmer**: Hover effects with light sweep animations

### **Celebration Effects**
- **🎊 Confetti Rain**: 50 colorful particles fall from the sky on wins
- **📊 Score Animations**: Numbers scale up and glow when scores update
- **🏆 Extended Celebrations**: 3-second celebration pause in tournaments
- **🎵 Enhanced Audio**: Multi-tone chord progressions for victory sounds

### **Visual Feedback**
- **✨ Winning Glow**: Victory cells pulse with golden light
- **🔄 Button Effects**: Difficulty buttons have sweeping light animations
- **💓 Player Pulse**: Current player indicator pulses rhythmically
- **🎨 Theme Transitions**: Smooth color transitions when switching themes

All animations are **hardware-accelerated** and **mobile-optimized** for smooth performance!

## 🏆 Tournament Features

### **Bracket System**
- Visual representation of all matches
- Color-coded status (current, completed, upcoming)
- Round-by-round progression
- Automatic advancement

### **Match Handling**
- **Wins**: Advance winner to next round
- **Draws**: Automatic match replay
- **Finals**: Special champion announcement

### **Player Management**
- Random seeding for fairness
- Custom or generated player names
- Progress tracking through rounds

## 💾 Save System Details

### **What Gets Saved**
```json
{
  "scores": { "x": 5, "o": 3, "draw": 1 },
  "playerNames": { "x": "Alice", "o": "Bob" },
  "gameMode": "tournament",
  "aiDifficulty": "hard",
  "tournamentData": {
    "tournamentSize": 8,
    "currentRound": 2,
    "matches": [...],
    "players": [...]
  },
  "timestamp": "2024-01-15T10:30:00.000Z"
}
```

### **Save Management**
- Multiple named saves with timestamps
- One-click save/load operations
- Export for backup or sharing
- Import to restore or transfer data
- Delete unwanted saves

## 🎮 Controls & Shortcuts

### **Mouse Controls**
- **Click Cells**: Make moves directly
- **Hover Effects**: Preview moves with animations
- **Button Clicks**: Navigate menus and options

### **Keyboard Shortcuts**
- **Numbers 1-9**: Select cell positions
- **Enter**: Confirm move after typing number
- **Tab**: Navigate between input fields

### **Touch Controls** (Mobile)
- **Tap Cells**: Make moves on touch devices
- **Swipe**: Smooth scrolling on mobile
- **Responsive Design**: Optimized for all screen sizes

## 🛠️ Technical Details

### **Built With**
- **HTML5**: Modern semantic structure
- **CSS3**: Advanced animations and effects
  - CSS Grid for game board
  - Flexbox for layouts
  - CSS animations and transitions
  - Glassmorphism effects
- **Vanilla JavaScript**: No dependencies
  - ES6+ features
  - Web Audio API for sounds
  - LocalStorage for persistence
  - Async/await for smooth AI

### **Browser Compatibility**
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers

### **Performance**
- **Lightweight**: Single file, ~50KB
- **Fast Loading**: No external dependencies
- **Smooth Animations**: Hardware-accelerated CSS
- **Efficient Storage**: Compressed JSON saves

## 📱 Mobile Experience

### **Responsive Design**
- Adaptive board sizing
- Touch-friendly controls
- Optimized typography
- Portrait/landscape support

### **Mobile Features**
- Touch gestures for moves
- Reduced animation intensity for battery
- Optimized particle count
- Thumb-friendly button sizing

## 🎨 Customization Guide

### **Easy Color Changes**
Modify CSS custom properties in the theme sections:
```css
.theme-ocean {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### **Adding New Themes**
1. Create new CSS class following pattern
2. Add theme button in HTML
3. Update `setTheme()` function

### **Particle Customization**
Adjust particle count and behavior in `createParticles()`:
```javascript
for (let i = 0; i < 50; i++) { // Change particle count
    // Modify animation properties
}
```

## 🐛 Troubleshooting

### **Common Issues**

**AI Not Moving**
- Ensure you're in AI mode
- Check that it's AI's turn (O player)
- Higher difficulties take longer to "think"
- Refresh page if issue persists

**Saves Not Loading**
- Check browser localStorage is enabled
- Ensure save name is selected in dropdown
- Try importing/exporting as backup

**Mobile Display Issues**
- Enable responsive mode in browser
- Check orientation (portrait recommended)
- Clear browser cache if needed

**Sound Not Playing**
- Check browser audio permissions
- Some browsers require user interaction first
- Mute/unmute browser tab

### **Browser-Specific Notes**
- **Safari**: May require user gesture for audio
- **Firefox**: LocalStorage has domain restrictions
- **Chrome**: Best overall compatibility
- **Mobile**: Reduced particle effects for performance

## 📈 Future Enhancements

### **Planned Features**
- 🎵 Background music with volume controls
- 🏅 Achievement system with unlockables
- 📊 Statistics dashboard with charts
- 🌐 Online multiplayer capability
- 🎨 Custom theme builder
- 📱 Progressive Web App (PWA) support

### **Advanced AI**
- Multiple difficulty levels
- Personality-based AI players
- Learning AI that adapts to your style
- AI vs AI demonstration mode

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### **Ways to Contribute**
1. **🐛 Bug Reports**: Report issues on GitHub
2. **💡 Feature Requests**: Suggest new features
3. **🎨 Design**: Improve UI/UX
4. **📝 Documentation**: Enhance this README
5. **🔧 Code**: Submit pull requests

### **Development Setup**
```bash
# Clone the repository
git clone https://github.com/yourusername/ultimate-tic-tac-toe.git

# No build process needed!
# Just open tic-tac-toe.html in your browser
```

### **Coding Standards**
- Use modern ES6+ JavaScript
- Follow existing code style
- Add comments for complex logic
- Test across multiple browsers

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Ultimate Tic-Tac-Toe

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

- **Design Inspiration**: Modern glassmorphism trends
- **AI Algorithm**: Minimax game theory implementation
- **Animation Ideas**: CSS animation communities
- **Testing**: Browser compatibility testing tools

<div align="center">

### 🎮 Ready to Play?

**[Download Now](./tic-tac-toe.html)**

Made with ❤️ by Mike who love great games

**Star ⭐ this repo if you enjoyed playing!**

</div>

---

> **Pro Tip**: Try the 💀 Impossible AI mode for the ultimate challenge, then organize a tournament with friends using custom names and themes! The AI uses advanced minimax algorithm that's nearly unbeatable! 🏆 