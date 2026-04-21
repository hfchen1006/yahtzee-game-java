# Yahtzee Game (Java, Swing)

## Overview
This project is a turn-based Yahtzee game built in Java using a Swing-based graphical user interface. It supports both human and computer players, complete scoring logic, and end-of-game leaderboard tracking.

This repository is based on a team course project and is included here as part of my personal software portfolio.

---

## My Contribution
My individual contributions included:

- Implemented scoring logic in `Score.java` and score tracking in `Scoreboard.java`
- Developed the `Value` enum used for dice representation and game logic
- Contributed to the `View` class by adapting an AI-generated GUI framework and integrating it with backend game logic
- Implemented GUI interactions such as dice rolling, scoring actions, and turn-based updates
- Debugged and improved `GameBoard.java` to ensure correct turn handling and overall game flow
- Collaborated with teammates to integrate components and ensure system consistency

---

## Features
- Human and computer players (Easy and Hard AI)
- Turn-based dice rolling and reroll system (up to 3 rolls per turn)
- Full Yahtzee scoring system (all categories supported)
- Interactive GUI built with Java Swing
- Score tracking and leaderboard display
- Win/loss tracking across multiple games

---

## Technologies
- Java
- Swing (GUI)
- Object-Oriented Programming (OOP)
- MVC architecture (Model-View-Controller)
- Event-driven programming

---

## How to Run
1. Open the project in an IDE such as Eclipse or VS Code  
2. Compile the project  
3. Run the main class (`View.java`)  
4. Follow the prompts to start the game  

---

## Project Structure
- `Dice`, `Value` – dice logic and representation  
- `Cup` – manages dice rolling and selection  
- `Score`, `Scoreboard` – scoring logic and tracking  
- `Player`, `Computer` – player types and AI behavior  
- `GameBoard` – manages turn order and game state  
- `View`, `Controller` – GUI and user interaction  

---

## Detailed Design

### Core Classes
- **Dice.java** – Represents a single die with values from 1–6  
- **Value.java** – Enum representing die faces  
- **Cup.java** – Manages dice rolling, holding, and resetting  
- **Score.java** – Evaluates possible scores across Yahtzee categories  
- **Scoreboard.java** – Tracks assigned and remaining categories for each player  
- **Player.java** – Represents human or computer player  
- **Computer.java** – Implements AI strategies for gameplay  
- **PlayerLibrary.java** – Stores player records and history  
- **GameBoard.java** – Controls turn order and overall game flow  

### Design Concepts
- Object-oriented design with encapsulation and modular class structure  
- MVC architecture separating game logic and UI  
- Event-driven programming for user interactions  
- AI strategies with different difficulty levels  

---

## Team Project Note
This project was originally developed as part of a team assignment.

Contributors:
- Bryan Frank  
- Ethan Alter  
- Frank Chen  
- Muyang Chen  

This version is maintained as part of my personal portfolio, with emphasis on my individual contributions listed above.
