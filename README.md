# Tech Quiz Game

An interactive quiz game to test your programming and technology knowledge.

## Features

- 🎮 15 programming and tech trivia questions
- ⏱️ 15-second timer per question
- 🎯 Score tracking with high score persistence
- ✅ Visual feedback (green for correct, red shake for wrong)
- 📊 Detailed results with grade and breakdown
- 🏆 High score system using localStorage
- 📱 Fully responsive design
- 🎨 Vibrant purple gradient theme

## How to Play

1. Open `index.html` in your browser
2. Click "Start Quiz"
3. Select an answer within 15 seconds
4. Watch the score and see immediate feedback
5. View your results and grade at the end
6. Try to beat your high score!

## Scoring

- **90%+**: 🏆 Excellent! (Tech Genius)
- **70-89%**: 🎉 Great Job!
- **50-69%**: 👍 Good Effort!
- **Below 50%**: 📚 Keep Learning!

## Technologies

- HTML5
- CSS3 (with gradients, animations, and transitions)
- Vanilla JavaScript
- LocalStorage API for high score persistence

## Customization

To add your own questions, edit the `questions` array in `quiz.js`:

```javascript
{
  question: "Your question here?",
  options: ["Option 1", "Option 2", "Option 3", "Option 4"],
  correct: 0 // Index of correct answer (0-3)
}
```

Created by Soham Gore
