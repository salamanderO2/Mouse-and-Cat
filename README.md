Project Submission
Project Name
Mouse and Cat Game

Group Name
Caloyloy Rodrigo

Purpose
This project is developed for academic purposes as part of BSCS 4F to demonstrate skills in Flutter app development, UI design, animation, and state management.

Requirements Submitted
Complete Flutter project code implementing the Mouse and Cat game with:

Random backgrounds

Cat chasing mouse

Speed increase every 10 seconds

Pause, resume, and exit options

Timer tracking survival time

Screenshots demonstrating gameplay, pause screen, caught screen, and main menu

Code comments inside Dart files explaining structure and main logic

Repository link: https://github.com/salamanderO2/Mouse-and-Cat/edit/main/README.md


Names and Roles
Developer: Caloyloy Rodrigo — solo developer, coder, designer, tester

Screenshots & Explanation
Main Menu: Entry point where the user starts the game.

Instructions Screen: Brief guide on how to play.

Gameplay Screen: Mouse controlled by cursor; cat chases mouse.

Pause Screen: Allows pause, resume, or exit.

Caught Screen: Displays survival time when caught, with options to restart or exit.

All UI components use Flutter widgets like Scaffold, Stack, Positioned, Timer, and GestureDetector for interaction.

Explanation of the Mouse and Cat Game Code
Phase 2: Basic Layout and UI Design
Uses Scaffold for basic app structure (AppBar, body, floating buttons)

Container, Row, and Column used for instruction and pause screen layouts

Stack widget layers background, mouse, cat, and UI elements on game screen

Instructions displayed with Column inside Center with padding (scrollable if extended)

Buttons and AppBar follow Material Design guidelines

Phase 3: Interactivity and Navigation
Routes via Navigator.push and Navigator.pop for menu, instructions, and game screens

MouseRegion tracks mouse cursor position for desktop/web gameplay

Buttons with onPressed callbacks control starting, pausing, resuming, restarting, exiting

Pause disables cat movement and timer via boolean flags

Phase 4: Animation Enhancements
Cat position updates smoothly every 30ms, moving fractionally toward mouse position

Cat speed increases every 10 seconds for progressive challenge

“Caught!” overlay appears with restart and exit options

Pause overlay dims screen with resume and exit buttons

Potential to extend animations with Flutter’s AnimatedContainer, AnimatedOpacity, or AnimationController
