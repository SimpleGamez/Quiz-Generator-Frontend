<div align="center">
<img src="" alt="Logo" width="120" />
<h1>PDF Quiz Generator</h1>
<p>
<strong>Turn any PDF document into an interactive quiz in seconds. 🚀</strong>
</p>
<p>
A sleek frontend application that extracts text from your PDFs and uses an AI backend to generate engaging quizzes automatically.
</p>

<p>
<a href="">
<img src="" alt="License">
</a>
<img src="" alt="Vanilla JS">
<img src="" alt="Tailwind CSS">
<a href="">
<img src="" alt="Issues">
</a>
</p>

<p>
<strong><a href="">View Live Demo</a></strong>
·
<a href="">Report a Bug</a>
·
<a href="">Request a Feature</a>
</p>
</div>

<div align="center">


<img width="1917" height="867" alt="image" src="https://github.com/user-attachments/assets/39ed3bca-1dfa-4434-91ef-0de8427fcbac" />


</div>

## ✨ Core Features
📄 Client-Side PDF Parsing: Uses PDF.js to extract text directly in the browser. No server upload is needed for the document itself, ensuring user privacy and speed.

🪄 AI-Powered Quiz Generation: Leverages a smart backend to create relevant multiple-choice questions from the source text.

🎨 Sleek & Modern UI: A clean, responsive interface built with Tailwind CSS, featuring a drag-and-drop file zone and smooth transitions between states.

⚙️ Customizable Quizzes: Allows users to specify the desired number of questions to generate.

💯 Instant Scoring & Feedback: Provides immediate results upon completion, highlighting correct and incorrect answers to aid learning.

🌍 Zero Installation: Runs directly in any modern web browser with no setup required.

## ⚙️ How It Works
The application follows a simple yet effective workflow:

⬆️ Upload: The user drags and drops or selects a PDF file.

🔍 Extract: The browser's JavaScript engine uses PDF.js to read the file and extract its text content.

🧠 Generate: The extracted text is sent to a backend API, which uses it as context to generate quiz questions.

🎓 Play: The questions are rendered dynamically, allowing the user to take the quiz.

✅ Score: The app calculates the score and displays a detailed results page.

## 🛠️ Tech Stack
This project is built with a focus on simplicity and performance, using only web-native technologies.

HTML5 & CSS3

 for utility-first styling

 for client-side PDF processing

## 🚀 Getting Started
No complex build steps are needed to run this project.

Clone the repository:

Open index.html in your browser.

## 🔌 Backend Dependency
⚠️ Important: This frontend is designed to work with a specific backend service for quiz generation.

API Endpoint: The app sends a POST request to https://quiz-generator-backend-891c.onrender.com/generate-quiz.

Request Body Format:

To use this frontend with your own backend, you must update the fetch URL in the JavaScript code and ensure your API handles the request and response in the same format.

## 📄 License
This project is distributed under the MIT License. See the LICENSE file for more information.
