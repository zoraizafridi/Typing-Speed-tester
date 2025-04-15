Typing Speed Tester (C Project)

This is a simple C-based typing speed tester that helps you measure your words per minute (WPM) and accuracy. It randomly picks a sentence from a file, tracks the time you take to type it, compares your input with the original, and displays the results along with a leaderboard.

Features

- Random sentence selection from `sentences.txt`
- Calculates:
  - Time taken
  - Words per minute (WPM)
  - Accuracy (% of correct characters)
- Stores results in a `leaderboard.txt` file
- Displays leaderboard with previous scores

How It Works

1. Loads sentences from `sentences.txt`
2. Prompts the user to type one randomly chosen sentence
3. Measures time taken and calculates WPM
4. Compares typed text with the original and calculates accuracy
5. Prompts for your name and saves your score to the leaderboard
6. Displays the leaderboard
