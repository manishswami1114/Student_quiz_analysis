# Student_quiz_analysis


## Project Overview
This project analyzes student quiz performance and generates personalized recommendations for improvement based on their current and historical data. The script evaluates quiz responses, identifies weak topics, and provides insights into accuracy and speed.

## Setup Instructions
1. Clone the repository:
```
git clone https://github.com/manishswami1114/student_quiz_analysis.git
```
2. Open in colab/Kaggle OR Local Machine and Run it 

## Approach Overview
# Data Collection:
The project fetches quiz data (including questions, topics, and correct answers) from an API (QUIZ_ENDPOINT) and submission data (user answers and timestamps) from another API (QUIZ_SUBMISSION_DATA).
# Data Analysis:
The data is analyzed to assess overall quiz performance, topic-wise accuracy, and historical performance trends.
Key metrics like accuracy and response speed are computed to generate insights into student strengths and weaknesses.
# Recommendations:
The system identifies weak topics from both current and historical data and generates actionable recommendations, including suggested topics for further study and practice questions.
# Student Persona:
The student is categorized into one of several personas (e.g., "Strategic Learner", "Speed-Focused", "Accuracy-Focused") based on their quiz accuracy and speed.
# Completion Check:
The project ensures that all tasks (questions) are completed by checking the student’s responses. It flags any missing answers and prompts the user to complete the quiz if necessary.

## Conclusion:
The Student Quiz  Analysis project helps educators or learners assess quiz performance comprehensively. By generating personalized insights and improvement recommendations, the system fosters targeted learning and enhances overall student performance.
