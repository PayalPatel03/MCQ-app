# MCQ-app

# JavaScript MCQ Web App Documentation

## Live Link
You can access the live application here: [MCQ Web App](https://mcq-app-alpha.vercel.app/)

## Overview
This web application is a simple multiple-choice question (MCQ) quiz designed for JavaScript students. It features a timer for each question, pagination for navigation, score tracking, and an animated UI for an engaging user experience.

## Features
- **Timed Questions**: Each question has a 15-second timer.
- **Pagination**: Users can navigate between questions using "Previous" and "Next" buttons.
- **Hover Effects**: Smooth animations for buttons.
- **Score Calculation**: The final score is displayed at the end.
- **Celebration Effects**: Emojis and animations appear when the quiz is completed.

## Technologies Used
- **HTML**: For structuring the web app.
- **CSS**: For styling and animations.
- **JavaScript**: For quiz logic, timer, and user interactions.

## How It Works
1. The app loads the first question from a predefined array.
2. Users select an answer, and the app automatically moves to the next question.
3. If time runs out, the app moves to the next question.
4. At the end, the final score is displayed with celebratory emojis.

## Code Breakdown
### HTML
- A container div holds the quiz elements: question, options, timer, and navigation buttons.

### CSS
- Styled buttons with hover effects.
- Animated fade-in effects for smooth transitions.
- Responsive design for various screen sizes.

### JavaScript
- An array of quiz questions with options and correct answers.
- Event listeners for button clicks to check answers.
- A timer function that resets for each question.
- A function to calculate and display the final score.

## Future Enhancements
- **More Questions**: Expand the question bank.
- **Leaderboard**: Track high scores.
- **Dark Mode**: Add a theme toggle option.

## Conclusion
This JavaScript MCQ web app is a fun and interactive way for students to test their knowledge. With a clean UI and engaging features, it enhances the learning experience.

