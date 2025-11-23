# ICE2025_MastermindGame

================================================================================
MASTERMIND GAME
================================================================================

A web-based implementation of the classic Mastermind code-breaking game with
a modern, tech-inspired interface.

================================================================================
OVERVIEW
================================================================================

Mastermind is a code-breaking game where you try to guess a secret code
composed of colored pegs. After each guess, you receive feedback:
- Black pegs: correct color in the correct position
- White pegs: correct color in the wrong position

This implementation features three difficulty levels, score tracking, and
accessibility options.

================================================================================
HOW TO PLAY
================================================================================

1. Select a difficulty level:
   - Easy: 4-digit code, 10 attempts
   - Hard: 6-digit code, 12 attempts
   - Impossible: 8-digit code, 15 attempts

2. Click on the colored pegs (0-9) to build your guess. The colors will
   appear in the guess slots from left to right.

3. Once all slots are filled, click "Submit Guess" to see your feedback.

4. Use the feedback to refine your next guess:
   - Black pegs show correct positions
   - White pegs show correct colors in wrong positions

5. Try to crack the code before running out of attempts!

================================================================================
FEATURES
================================================================================

Difficulty Modes
- Easy: 4-digit code with 10 attempts
- Hard: 6-digit code with 12 attempts
- Impossible: 8-digit code with 15 attempts

Score Tracking
- Tracks your highest score (lowest attempts to win)
- Displays total games played
- Shows your last 5 game results

Theme Options
- Dark mode (default): Cyberpunk-inspired dark theme with neon accents
- Light mode: Clean light theme for daytime play
- Toggle between themes using the "Dark Mode" / "Light Mode" button

Accessibility
- Toggle number labels (0-9) on all color elements
- Helps players who have difficulty distinguishing colors
- Numbers appear consistently on color pegs, guess slots, and history

Game Controls
- Submit Guess: Submit your current guess for evaluation
- Clear: Remove all colors from your current guess
- New Game: Start a fresh game with a new secret code

Guess History
- View all your previous guesses with feedback
- See both your guess and the black/white peg feedback
- History scrolls automatically as you make more guesses

================================================================================
TECHNICAL DETAILS
================================================================================

Files:
- index.html: Main HTML structure
- style.css: Styling and theme definitions
- script.js: Game logic and functionality

Browser Compatibility:
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Uses standard web technologies (HTML5, CSS3, JavaScript)

No Dependencies:
- Pure vanilla JavaScript (no frameworks required)
- Google Fonts loaded from CDN (Orbitron, Rajdhani)
- No external libraries needed

================================================================================
USAGE
================================================================================

Simply open index.html in any modern web browser. No installation or setup
required. The game runs entirely in the browser.

To play offline, ensure all three files (index.html, style.css, script.js) are
in the same directory.

================================================================================
NOTES
================================================================================

- The secret code is randomly generated each game
- Colors can repeat in the code
- Your score is tracked per session (resets on page refresh)
- Difficulty can be changed at any time (starts a new game)

================================================================================

