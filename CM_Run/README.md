# Kerala Election Run 🗳️🏃

A fun and interactive web-based game where players jump through all 140 Kerala Legislative Assembly constituencies!

## Features
- 🎮 Three political parties to choose from: LDF, UDF, BJP
- 🎵 Sound effects for jumps, scores, collisions, and victory
- 📍 All 140 Kerala assembly constituencies
- 🏆 Complete all seats to win the game!
- 🌐 Works on all modern browsers (no external dependencies)

## How to Play
1. Select your political party (LDF, UDF, or BJP)
2. Press **SPACEBAR** to jump over the constituencies
3. Successfully pass all 140 seats to win!
4. Click "Restart Game" to play again

## Files Included
- `index.html` - Complete game (single file, ready to deploy!)

## Deployment Instructions

### Option 1: webappbazaar.com
1. Log in to your webappbazaar.com account
2. Create a new application
3. Upload `index.html`
4. Set `index.html` as the entry point/main file
5. Deploy and share your game URL!

### Option 2: Other Web Hosting
1. Upload `index.html` to your web server
2. Set proper MIME types (HTML files as text/html)
3. Access via your domain/URL

### Option 3: Local Testing
- Simply open `index.html` in any modern browser
- No server needed!
- Works offline

## Browser Compatibility
- Chrome 14+
- Firefox 25+
- Safari 6+
- Edge (all versions)
- Opera 15+

## Technical Details
- Pure HTML5/CSS3/JavaScript
- Uses Web Audio API for sound effects
- Fully responsive design
- No backend/server required
- No external libraries

## Game Mechanics
- Jump height: 20 pixels per jump
- Gravity: 0.6 pixels/frame
- Obstacle speed: 4 pixels/frame
- Game loop: 16ms (60 FPS target)

## Customization
You can easily customize:
- Colors: Modify the party colors in the CSS
- Seat list: Edit the `seats` array in the JavaScript
- Game speed: Adjust the `moveInterval` timing
- Difficulty: Change `gravity` and `velocity` values

## License
Free to use and modify!

## Created
April 28, 2026

Enjoy the game! 🎮
