# Whack-a-Mole Game

A simple browser-based Whack-a-Mole game implemented in a single HTML file using HTML, CSS, and JavaScript.

## How to Play

1.  **Open the Game:** To play, download the `index.html` file and open it directly in your web browser (e.g., Chrome, Firefox, Safari, Edge).
2.  **Objective:** The goal is to click on the "moles" (which will appear as gold circles) that pop up in the brown circular holes. Each successful whack earns you points.
3.  **Game Controls:**
    *   **Start Game button:** Press this button to begin the game. The timer will start, and moles will begin appearing.
    *   **Reset Game button:** Press this button at any time to stop the current game and reset the timer and score. You can use this to restart if you want to try again before the timer runs out.
4.  **Game Mechanics:**
    *   A timer will start counting down from 30 seconds as soon as you click "Start Game".
    *   Moles will appear in random holes for a short duration. Click them before they disappear!
    *   The game ends when the timer reaches zero. Your final score will be displayed in an alert.
    *   Try to achieve the highest score possible within the time limit!

## Technical Note

This game is built entirely within the `index.html` file, utilizing:
*   **HTML:** For the structure of the game (game area, score display, timer, buttons).
*   **CSS:** For styling the appearance of the game elements, including the mole holes, moles, and overall layout.
*   **JavaScript:** For all the game logic, including mole appearance/disappearance, click handling, scoring, timer functionality, and game state management.
