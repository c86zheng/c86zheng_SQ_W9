# Week 9 Example 3 - Higher or Lower

**Controls:**

- Start Game: Click anywhere on the start screen
- Choose Higher: Click the **HIGHER ▲** button
- Choose Lower: Click the **LOWER ▼** button
- Restart Game: Click after the win or game over screen
- Toggle Debug Panel: Press the **D** key
- Debug Shortcuts: Press **1**, **2**, or **3** to jump to a level; press **S** for the start screen, **W** for the win screen, and **O** for the lose screen

Players play a three-level Higher or Lower card guessing game against a shuffled deck. A card is shown face up, and the player guesses whether the next hidden card will be higher or lower. After each guess, the game reveals whether the choice was correct. Equal card values count as wrong because the player must choose one direction.

Each level uses a different JSON card list and target score. The player advances to the next level by reaching the target score for the current level. A wrong guess ends the game, and completing all three levels shows the win screen.

Press **D** to open the debug panel. The debug keys can be used to test different levels and screens while the sketch is running.

## Assets

No external assets used. All visuals are generated with p5.js.

## References

N/A
