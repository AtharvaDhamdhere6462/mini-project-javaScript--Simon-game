#  Simon Says Game

A simple memory-based Simon Game built using **Pure HTML, CSS, and JavaScript**.

This game tests the player's memory by generating a random color sequence that must be repeated correctly. Each level increases the difficulty by adding a new color to the sequence.

---

##  Live Features

- Press any key to start the game
- Random color sequence generation
- Increasing difficulty level
- Real-time sequence validation
- Flash animation effects
- Game over screen with score display
- Instant restart functionality

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- DOM Manipulation
- Event Handling

---

##  How to Play

1. Press any key to start.
2. Watch carefully as a color button flashes.
3. Click the buttons in the exact same order.
4. Each level adds one new color to the sequence.
5. If you press the wrong button, the game ends.
6. Press any key to restart and try again.

---

##  Game Logic

- `gameSeq[]` → Stores the system-generated sequence.
- `userSeq[]` → Stores the user's selected sequence.
- `level` → Tracks current level.
- `levelUp()` → Generates a new random color and updates level.
- `checkAns()` → Validates user input.
- `reset()` → Resets the game state after failure.

---


