# Tic-Tac-Toe-Project
CS20

---

Steps in Creating a Tic Tac Toe Processing-Java Game
- Play the Game, see Google
- Review some analysis videos of the game no get ideas about algorithms and code
- Design GUI & Data Structures
- Code a Two-player version or Super Tic Tac Toe
- Prototype 1-Player Algorithms
- Assemble the whole game

---

# Play the Game
- See Google Chrome: search Tic Tac Toe
- Use any other app or paper and pencil
- Notice,
  - 1 or 2 player modes
  - Levels for 1 Player
  - Restart Button
  - Scoreboard and method to show whose turn it is

---


---

# To Include

Review of Videos and Introduction to Tic Tac Toe Algorithms
- Shapes of Double Threats
- Relative Positions of 3-in-a-row, 2-in-a-row
- Blocking: what does it mean
- Coding: how to pick an Algorithm and use it to inform choices
- First Algorithm: randomly placing a token anywhere

**Reminder**: Super Tic Tac Toe
- 1-Player in Tic Tac Toe can be difficult to plan and code
- Creating a Super Tic Tac Toe game with Quit-Button and "Do you want to play again? YES-No"
- Super Tic Tac Toe has game play rules that need to be followed in 2-player (this will be were algorithms are)

GUI Design & Data Structure Design
- Ratios and Symmetry (paper folding and generalizing 1/3 to percepts when populating variables based on display geometry)
- Restart Button: clear specific variables, clear playing board
- Scoreboard (X & O)
  - Traditionally, X goes first but this is not always Player One (if names are not entered)
  - Requires some though into how a two-play game will be controlled and scored
- Quit Button
- 2-Player and 1-Player Button
- If 1-Player chosen, levels are mandatory
  - Levels: must code first 2 to earn 50% here, other levels increase grade
  - Note: these levels create an
    1. Random: randomly put O-Token anywhere that is not filled
      - Note: traditionally computer is O-Token
      - Optional: computer goes first but correct score is still tracked
    2. Easy: multiple options
      - Strict Random: first move is always random
      - Loose Random: some tokens will have choice of locations but not all locations will lead to 3-in-a-row
      - 3-in-a-row random: pick a location "randomly" planning 3 in a row
      - first move in always in side-location
      - first move is usually in side-location
    3. Medium: definitions here are up to developer, options include
      - blocking 3-in-a-row
      - blocking 2-in-a-row (note: this is different, no consideration if 3-in-a-row is possible)
      - first move is never in side-location (very small percentage of winning)
      - first move is always center or corner, then other algorithms take over
    4. Hard or Impossible: developer defines what these mean
      - Blocking "double threat" setup
      - Blocking "double threat" setup while setting up own double threat
- Quit Button
- Optional: game clock and total time clock
  - leads to digital health options

Coding: Creating Game Space and Laying out where buttons will be
- Includes hover-over, colours, menus, and any other special effects
- Example Special Effects: CATS Evaluation and TIE Score Counter
  - "Do you want to play again? (after max score reached)"
  - File IO: if game is quit before max score, option to pause and start again

Coding: Create a 2-Player Version
- CAUTION: this version needs to have 1 player available to be taken over

Coding: Algorithms Prototyping

Coding: Assembling the full game
