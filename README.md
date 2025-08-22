SkillCraft Technology Web Development Internship – Project Portfolio

This repository contains all the projects I completed during my internship at SkillCraft Technology.
The internship was focused on building practical frontend applications using HTML, CSS, and JavaScript.

I documented each task with:

What I built

Errors or challenges faced

How I solved them

Key learnings

Task 01 – Responsive Landing Page

What I built:
A responsive landing page with a navigation bar that changes style on hover and scroll.

Errors/Challenges:

Initially, the navbar was not sticking properly when scrolling.

Responsive layout was breaking on small screen devices.

How I solved it:

Used CSS position: fixed and media queries to handle responsiveness.

Debugged layout issues step by step using browser dev tools.

Learning:
Improved my understanding of responsive design and the importance of testing layouts on different screen sizes.

Task 02 – Stopwatch Web Application

What I built:
A stopwatch with start, pause, reset, and lap features.

Errors/Challenges:

Timer was running too fast because I used multiple setInterval calls.

Reset button was not clearing lap times properly.

How I solved it:

Added a condition to ensure only one setInterval runs at a time.

Cleared laps by resetting the innerHTML of the lap list before adding new ones.

Learning:
Got better at handling JavaScript timing functions and DOM updates.

Task 03 – Tic Tac Toe Game

What I built:
A simple Tic Tac Toe game for two players with winning animations.

Errors/Challenges:

Win detection logic was not working in some cases (like diagonals).

Game board was not resetting fully after a replay.

How I solved it:

Wrote a dedicated function to check all winning combinations (rows, columns, diagonals).

Added a clearBoard function to reset the game state properly.

Learning:
Learned how to break down logic problems into smaller parts and how to debug event-driven applications.

Task 04 – To-Do List with Reminders

What I built:
A pink-themed To-Do List application with default tasks (Drink Water, Exercise, Study) and a reminder section.

Errors/Challenges:

Tasks were not saving correctly after editing.

Reminder section was overlapping with tasks on smaller screens.

How I solved it:

Used array indexing properly to update tasks during editing.

Adjusted CSS grid layout and media queries to fix overlapping issues.

Learning:
This project helped me improve UI design skills and write cleaner JavaScript code for task management.

Overall Learnings

Gained hands-on practice in JavaScript DOM manipulation and event handling.

Understood the importance of debugging tools and breaking problems into smaller parts.

Learned to combine functionality with design to make applications both useful and visually appealing.

Faced real-world coding errors and figured out how to fix them systematically.

Acknowledgment

I am thankful to SkillCraft Technology for giving me this internship opportunity. These tasks allowed me to grow step by step and improve as a frontend developer.
