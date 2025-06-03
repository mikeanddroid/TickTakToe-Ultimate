# 🎯 Ultimate Tic-Tac-Toe

> A modern, feature-rich tic-tac-toe game with AI opponents, tournament mode, custom themes, and complete save/load functionality - all in a single HTML file!


## ✨ Features

### 🎮 **Game Modes**
- **👥 Two Player Mode**: Classic human vs human gameplay
- **🤖 AI Opponent**: Challenge yourself against smart AI
  - 😊 **Easy AI**: Random moves for casual play
  - 😈 **Hard AI**: Strategic AI using minimax algorithm
- **🏆 Tournament Mode**: Organize tournaments with 4 or 8 players

### 🎨 **Visual Experience**
- **4 Stunning Themes**: Ocean 🌊, Space 🌌, Sunset 🌅, Forest 🌲
- **Animated Background**: Floating particles with smooth animations
- **3D Effects**: Hover animations with realistic depth
- **Glassmorphism Design**: Modern frosted glass aesthetic
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
- **Victory Sounds**: Web Audio API generated celebration tones
- **Visual Feedback**: Winning combinations highlight with golden glow
- **Smart Notifications**: Beautiful slide-in notifications system
- **Move Analytics**: Track moves and display winning combinations

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
- Choose difficulty: Easy (random) or Hard (strategic)
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

The **Hard AI** uses advanced game theory:

1. **🎯 Win**: Take winning move if available
2. **🛡️ Block**: Prevent player wins
3. **🎲 Center**: Claim center position when possible
4. **🏰 Corners**: Prioritize corner positions strategically
5. **⚡ Random**: Fill remaining spaces intelligently

The AI provides genuine challenge while maintaining fair gameplay!

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

> **Pro Tip**: Try the Hard AI mode for a real challenge, then organize a tournament with friends using custom names and themes! 🏆 