# 🎮 Tower Blocks

A fun and addictive 3D tower-building game built with Three.js. Stack blocks as high as you can and challenge yourself to achieve the perfect placement!

## 🎯 Game Features

- **3D Graphics**: Beautiful 3D rendering using Three.js
- **Dynamic Difficulty**: Blocks move faster as you stack higher
- **Perfect Placement Bonus**: Get rewarded for precise block placement
- **Background Music**: Relaxing melody that plays during gameplay
- **Sound Effects**: Audio feedback for block placement, perfect placement, and game over
- **Mute/Unmute Control**: Toggle sound on/off with a convenient button
- **Responsive Design**: Works on desktop and mobile devices
- **Score Tracking**: Keep track of your highest tower
- **Smooth Animations**: Powered by GSAP for fluid transitions

## 🎮 How to Play

1. Click the **Start** button to begin
2. Click (or press **Spacebar**) to drop the moving block
3. Try to align each block perfectly with the one below
4. The game ends when you miss the platform completely
5. Click or press Spacebar to restart after game over

### Controls
- **Mouse Click** or **Spacebar**: Place block / Start game / Restart
- **🔊 Button** (top-right): Toggle sound on/off

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Running Locally

1. Clone this repository:
```bash
git clone https://github.com/ashurai1/tower-blocks.git
cd tower-blocks
```

2. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply drag and drop the `index.html` file into your browser.

### Hosting Online

You can host this game on any static web hosting service:
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Deploy with a single command
- **Any web server**: Upload all files to your server

## 🛠️ Technologies Used

- **Three.js** (r83) - 3D graphics library
- **GSAP (TweenMax)** - Animation library
- **Web Audio API** - Sound generation and playback
- **HTML5 & CSS3** - Structure and styling
- **JavaScript (ES6)** - Game logic
- **LocalStorage** - Persistent settings

## 📁 Project Structure

```
tower-blocks/
├── index.html      # Main HTML file
├── style.css       # Styling and layout
├── script.js       # Game logic and audio system
└── README.md       # This file
```

## 🎵 Audio Features

The game uses the **Web Audio API** to generate sounds programmatically:
- **Background Music**: A simple melodic pattern that loops during gameplay
- **Block Placement**: Short beep sound when placing a block
- **Perfect Placement**: Ascending tones for perfect alignment
- **Game Over**: Descending tones when the game ends

Your sound preference is saved automatically and persists across sessions.

## 🎨 Customization

Feel free to customize the game:
- **Colors**: Modify the color generation in the `Block` class
- **Speed**: Adjust the `speed` calculation in the `Block` constructor
- **Sounds**: Change frequencies and durations in the `playSound()` method
- **Music**: Modify the `notes` array in `startBackgroundMusic()`

## 📱 Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Ashwani Rai**
- GitHub: [@ashurai1](https://github.com/ashurai1)
- Email: raishwani151104@gmail.com

## 🙏 Acknowledgments

- Three.js community for the amazing 3D library
- GSAP for smooth animations
- Inspired by classic tower-building games

---

© 2025 Ashwani Rai. All rights reserved.

**Enjoy the game! 🎮🎉**
