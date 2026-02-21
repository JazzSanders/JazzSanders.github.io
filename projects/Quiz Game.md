---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Quiz Game Web Application"
date: 2026
published: true
labels:
  - Web Development
  - Firebase
  - JavaScript
  - UI/UX Design
summary: "I developed a real-time, synchronized web-based trivia application that supports live, concurrent sessions using Firebase and JavaScript."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The Quiz Game Web Application is an interactive, real-time platform designed to facilitate trivia sessions for educational and casual/social purposes. Unlike traditional static quizzes, this application leverages modern web technologies to provide a synchronized experience where multiple participants can compete simultaneously. The system is built on a client-server architecture utilizing Firebase as a backend-as-a-service (BaaS) to handle real-time data synchronization. When a host creates a session, the system generates a unique 4-digit join code and establishes a listener that pushes questions to all connected player devices simultaneously.

As the developer, I was responsible for the full-stack implementation of the project within a strict five-week timeline. I designed a dynamic role-based interface that branches into distinct host and player workflows. Key features I implemented include a real-time live lobby, a visual feedback system for players, and a proprietary bar chart for hosts that updates instantly as players submit responses. To ensure a high standard of accessibility, I incorporated high color contrast and screen reader compatibility, following WCAG standards.

One of the most significant technical achievements was the development of a competitive scoring engine. This time-sensitive algorithm rewards both accuracy and speed to maintain a high level of engagement during live sessions.

Here is the JavaScript logic used to calculate the speed-sensitive score:

function calculateScore(timeRemaining) {
    // Competitive scoring engine rewards both accuracy and speed
    // Score = 50 base points + (time remaining * 100)
    const score = 50 + (timeRemaining * 100);
    return score;
}

You can learn more in the [Quiz Game Web Application Report](https://github.com/JazzSanders/JazzSanders.github.io/blob/main/projects/Jasmine%20Sanders_Report1.docx).
You can play the Quiz Game [here](https://jazzsanders.github.io/CSC272---Winter2026/index.html).
