# Advanced Quiz Game

A comprehensive, interactive quiz game built with HTML, CSS, and JavaScript that features multiple subjects, difficulty levels, and a rich set of features.

## Features

### Core Functionality
- **Multiple Subjects**: Science, History, Geography, Mathematics, and Literature
- **Three Difficulty Levels**: Easy, Medium, and Hard
- **Progressive Scoring System**: Points based on difficulty and speed
- **Timer System**: Configurable countdown timer for each question
- **Hint System**: Limited hints available per quiz session
- **Leaderboard**: Local storage-based high score tracking

### Advanced Features
- **Achievement System**: Unlock achievements for special accomplishments
- **Sound Effects**: Audio feedback for correct/incorrect answers
- **Settings Panel**: Customize sound, timer, and difficulty preferences
- **Responsive Design**: Works on desktop and mobile devices
- **Progress Tracking**: Visual progress bar and question counter
- **Detailed Statistics**: Accuracy, time spent, and performance metrics

## Technical Details

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (ES6+)**: Game logic, DOM manipulation, and local storage
- **Web Audio API**: Dynamic sound generation
- **Local Storage**: Persistent data for scores and settings

### Architecture
- **Modular Design**: Separated concerns for game state, UI, and data
- **Event-Driven**: User interactions handled through event listeners
- **State Management**: Centralized game state for easy maintenance
- **Data Structure**: Organized question bank with metadata

## How to Run

1. Download the `quiz-game.html` file
2. Open it in any modern web browser
3. No additional setup or dependencies required
4. Enjoy the game!

## Game Instructions

1. **Select a Subject**: Choose from Science, History, Geography, Mathematics, or Literature
2. **Choose Difficulty**: Pick Easy, Medium, or Hard
3. **Start the Quiz**: Click the Start button
4. **Answer Questions**: Select the correct answer before time runs out
5. **Use Hints**: Click "Get Hint" for help (limited uses)
6. **Complete the Quiz**: Answer all questions to see your score
7. **Save Your Score**: Enter your name for the leaderboard
8. **View Leaderboard**: See top 10 scores across all players

## Scoring System

- **Base Points**:
  - Easy: 10 points per correct answer
  - Medium: 20 points per correct answer
  - Hard: 30 points per correct answer
- **Time Bonus**: Up to 50% extra points based on speed
- **Hint Penalty**: -5 points per hint used
- **Achievements**: Special bonuses for streaks and quick answers

## Customization Options

### Settings Panel
- Toggle sound effects on/off
- Enable/disable timer
- Adjust timer duration (15, 30, or 60 seconds)
- Settings persist between sessions

### Achievement System
- "5 Correct Streak" - Answer 5 questions correctly in a row
- "Score Master" - Achieve 500+ points in a single game
- "Speed Demon" - Answer a hard question in under 5 seconds

## Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome for Android)

## Future Enhancements

Potential improvements:
- Online multiplayer mode
- Custom question creation
- Category filtering
- Social sharing features
- More achievement types
- Question explanations
- Progress tracking across sessions

## Credits

Created as a personal programming project for CS class demonstration.
Built with vanilla JavaScript - no external libraries required.

## License

This project is open source and available for educational purposes.
