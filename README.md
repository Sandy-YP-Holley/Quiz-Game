Quiz Game

A simple and interactive browser-based Quiz Game built using HTML, CSS, and Vanilla JavaScript. Test your knowledge by answering multiple-choice questions, track your score in real time, and receive feedback based on your final results.

Features

- Interactive multiple-choice quiz
- Real-time score tracking
- Progress bar showing quiz completion
- Automatic question progression
- Result screen with personalized feedback
- Restart quiz functionality
- Responsive design for desktop and mobile devices

Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

Project Structure

quiz-game/
│
├── index.html      # Main HTML structure
├── style.css       # Styling and responsive design
├── script.js       # Quiz logic and interactivity
└── README.md       # Project documentation

How It Works

1. The user clicks Start Quiz.
2. Questions are displayed one at a time.
3. The user selects an answer.
4. Correct answers increase the score.
5. The correct answer is highlighted after each selection.
6. The quiz automatically moves to the next question.
7. After the final question, the result screen displays:
   - Final score
   - Percentage achieved
   - Performance message
8. The user can restart the quiz and try again.

Quiz Topics

The current version includes questions about:

- Geography
- Astronomy
- Oceans
- Programming
- Chemistry

Questions can easily be modified by editing the "quizQuestions" array inside "script.js".

Installation

1. Clone the repository:

git clone https://github.com/Sandy-YP-Holley/Quiz-Game.git

2. Navigate to the project folder:

cd quiz-game

3. Open "index.html" in your web browser.

No additional dependencies or installations are required.

Future Improvements

- Add a timer for each question
- Shuffle questions randomly
- Load questions from an API or JSON file
- Add difficulty levels
- Save high scores using Local Storage
- Add categories and custom quiz packs
- Include sound effects and animations

Author

Created by Sandy Yoga Prakasa Holley as a JavaScript learning project.
