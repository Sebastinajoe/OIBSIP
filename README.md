OIBSIP — Oasis Infobyte Internship Projects

<div align="center">
Web Development & Designing Internship — Level 2

📂 GitHub Repository · 🌐 Live Demo

</div>

👩‍💻 About Me

Name: Sebastina J
Domain: Web Development and Designing
Level: Level 2
Program: Oasis Infobyte Internship Program (OIBSIP)
Timeline: June 15 – July 15, 2026
GitHub: https://github.com/sebastinajoe


📌 About the Internship

Oasis Infobyte is a community-driven internship platform that creates opportunities for leadership development, learning, and student engagement. This internship focuses on building real-world web development projects using HTML, CSS, and JavaScript.

For the Web Development and Designing domain, interns must complete any one level (Level 1, 2, or 3). I have chosen Level 2, which consists of 4 tasks.


📁 Repository Structure

OIBSIP/
├── Task1_Calculator/
│   ├── index.html
│   └── README.md
├── Task2_TributePage/
│   ├── index.html
│   └── README.md
├── Task3_TodoApp/
│   ├── index.html
│   └── README.md
├── Task4_LoginAuth/
│   ├── index.html
│   └── README.md
└── README.md              ← This file


🗂️ Task Overview

Task 1 — Calculator

A modern, fully functional calculator application with a dark neon-purple theme.

Live Demo: https://sebastinajoe.github.io/OIBSIP/Task1_Calculator/index.html

Features:


Addition, subtraction, multiplication, division
Percentage and sign toggle
Collapsible calculation history (stores last 20)
Full keyboard support with visual flash feedback
Backspace key support
Division by zero error handling
Responsive design using clamp() and min()


Technologies: HTML5, CSS3, Vanilla JavaScript, Google Fonts (Share Tech Mono + Inter)


Task 2 — Tribute Page

A tribute page dedicated to Cristiano Ronaldo — the greatest footballer of all time.

Live Demo: https://sebastinajoe.github.io/OIBSIP/Task2_TributePage/index.html

Features:


Full-screen hero with ghost #7 watermark and career stats
Biography section with personal info card
Animated career timeline (2002 → 2023) using IntersectionObserver
Trophy cabinet with 8 major honours
Famous quote section
World records section with 6 cards
Fully responsive design
Smooth scroll behaviour


Technologies: HTML5, CSS3, JavaScript (IntersectionObserver), Google Fonts (Bebas Neue + Playfair Display + Inter)


Task 3 — To-Do Web App

A complete task management web app with pending and completed sections.

Live Demo: https://sebastinajoe.github.io/OIBSIP/Task3_TodoApp/index.html

Features:


Add, edit, delete tasks
Mark tasks as complete via checkbox
Separate Pending and Completed sections
Clear entire section at once
Live stats — Total, Pending, Completed count
Progress bar showing percentage of tasks done
Added and completed timestamps on each task
Slide-in animation on new tasks
Sticky top bar with live date
Keyboard support (Enter to add, Enter/Escape in edit modal)
XSS-safe rendering


Technologies: HTML5, CSS3, Vanilla JavaScript, Google Fonts (Plus Jakarta Sans + Space Mono)


Task 4 — Login Authentication

A complete register, login and secured dashboard system.

Live Demo: https://sebastinajoe.github.io/OIBSIP/Task4_LoginAuth/index.html

Features:


Register page with name, email, password, confirm password
Login page with email and password
Secured dashboard — accessible only after login
Real-time field-level validation with error messages
Password strength indicator (5 levels — Weak to Very Strong)
Show/hide password toggle
Toast notifications for success and error states
Duplicate email check on registration
Auto-generated avatar from user's first initial
Login time and date displayed on dashboard
Logout functionality
Enter key submits forms
Responsive design


Technologies: HTML5, CSS3, Vanilla JavaScript, Google Fonts (Plus Jakarta Sans + Space Mono)


🛠️ Technologies Used

TechnologyPurposeHTML5Page structure and semantic layoutCSS3Styling, animations, responsive designVanilla JavaScriptDOM manipulation, logic, interactivityGoogle FontsTypography across all tasksGitHub PagesLive deployment of all projects


🚀 How to Run Locally

bash# Clone the repository
git clone https://github.com/sebastinajoe/OIBSIP.git

# Open any task folder
cd OIBSIP/Task1_Calculator

# Open index.html in your browser
# Double-click the file or right-click → Open with browser

No installations, no dependencies, no build tools needed. Every task runs directly in the browser.


⌨️ Keyboard Shortcuts — Task 1 Calculator

KeyAction0 – 9Enter digits+ - * /Arithmetic operationsEnter or =Calculate resultBackspaceDelete last digitEscapeClear all%Percentage


📋 Internship Submission Checklist


 Task 1 — Calculator completed
 Task 2 — Tribute Page completed
 Task 3 — To-Do Web App completed
 Task 4 — Login Authentication completed
 All tasks pushed to GitHub OIBSIP repository
 All tasks deployed via GitHub Pages
 Demo videos created for all tasks
 Videos posted on LinkedIn with #oasisinfobyte
 README files written for all tasks
 Peer evaluation completed (watched and commented on 2 fellow intern videos)



🎯 Internship Details

FieldDetailsProgramOasis Infobyte Internship Program (OIBSIP)DomainWeb Development and DesigningLevelLevel 2Tasks CompletedTask 1, Task 2, Task 3, Task 4TimelineJune 15 – July 15, 2026


🔗 All Live Demos

TaskLinkTask 1 — Calculatorhttps://sebastinajoe.github.io/OIBSIP/Task1_Calculator/index.htmlTask 2 — Tribute Pagehttps://sebastinajoe.github.io/OIBSIP/Task2_TributePage/index.htmlTask 3 — To-Do Apphttps://sebastinajoe.github.io/OIBSIP/Task3_TodoApp/index.htmlTask 4 — Login Authhttps://sebastinajoe.github.io/OIBSIP/Task4_LoginAuth/index.html


👩‍💻 Author

Sebastina J

GitHub: https://github.com/sebastinajoe


<div align="center">
Made with ❤️ as part of the Oasis Infobyte AICTE Internship

⭐ If you found this helpful, consider starring the repo!

</div>ShareContentpdf<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Calculator | OIBSIP – Web Dev Task 1</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Inter:wght@300;400;60pasted
