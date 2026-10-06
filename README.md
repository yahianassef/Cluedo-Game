# Cluedo Manor

Dr Black is dead. Find out who did it, with what, and where.

A Cluedo-style murder mystery board game that runs entirely in your browser. You play against 2 to 5 computer detectives. There's nothing to install and no sign-up.

**Play it:** open `index.html`, or visit the GitHub Pages link for this repository once Pages is turned on.

## Features

- Full 24×25 board with 9 rooms, doors and secret passages (Kitchen ↔ Study, Conservatory ↔ Lounge)
- 6 suspects, 6 weapons, 9 rooms. One of each is hidden in the case file.
- Dice, movement, suggestions, card showing and accusations, following the classic rules
- Computer opponents with two skill levels:
  - **Casual:** learns only from cards shown directly to it
  - **Sharp:** also works out clues from card swaps between other players
- Detective notepad that crosses off your own cards and cards shown to you

## How to play

1. Pick your character, the number of opponents, their skill and their speed, then press **Start game**.
2. On your turn, press **Roll dice**, then tap a green square or a highlighted room.
3. In a room, make a **suggestion**. Each other player in turn must show you one matching card if they hold one.
4. Use the notepad to track what you've ruled out.
5. When you're sure, press **Accuse**. If you're right, you win. If you're wrong, you're out.

## Tech

A single HTML file of plain HTML, CSS and JavaScript, with no build step. The only outside resource is Google Fonts.

*A fan-made game, not affiliated with Hasbro. Cluedo is a trademark of Hasbro.*
