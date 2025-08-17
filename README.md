Capstone Project – Quiz App
1. Project Idea
Quiz App – A responsive and interactive quiz application built with React and styled using Tailwind CSS. This app fetches trivia questions from the Open Trivia Database API and allows users to test their knowledge across various topics and difficulty levels. 

2. Features
Dynamically fetch trivia questions from the Open Trivia Database API.


Allow users to customize quiz options such as category, difficulty, and question type.


Support multiple-choice questions.


Provide real-time scoring and feedback during the quiz.


Offer a fully responsive design, optimized for both desktop and mobile devices.



3. Technologies Used
Frontend: React (JavaScript)


Styling: Tailwind CSS


API: Open Trivia Database API



4. API Details
API Name: Open Trivia Database API

Reason for Choice:
Free and public API with no authentication required.


Offers multiple categories, difficulty levels, and question formats.



5. Project Structure Plan
Pages & Components:
Home Page: Introduction and quiz setup form (category, difficulty, question type, start button).


Quiz Page: Displays questions one by one, answer options, feedback, and score tracker.


Results Page: Shows final score and replay option.


Navbar Component: Branding and navigation links.


Footer Component: Credits and resources.


QuestionCard Component: Renders question text and answer buttons.


Score Component: Shows live score.


App Flow:
User selects quiz settings on Home Page → clicks "Start Quiz".


App fetches questions from API.


Questions are shown sequentially with answer options.


Score updates in real time.


Results page shows total score and restart option.



6. Timeline
Week
Task
Week 1
Set up React + Tailwind environment, create basic components (Navbar, Footer, Home).
Week 2
Integrate API, fetch and display questions, handle user answers.
Week 3
Implement scoring system, create Results page, add responsiveness.
Week 4
Testing, bug fixes, and deployment on Netlify or Vercel.


