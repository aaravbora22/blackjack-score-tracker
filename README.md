# Blackjack Score Tracker

A Java command-line tool that records the result of each blackjack hand for every player, shows a scoreboard with running totals, and saves the session to a file so it can be resumed later.

## Project Goal

Tracking scores by hand during a long blackjack session is tedious and error-prone. This tool handles the bookkeeping, including wins, losses, pushes, and blackjack payouts, so players can focus on the game.

## MVP Scope

- Add players to a session
- Record the result of each hand for every player: win, loss, push, or blackjack
- Calculate points for each result using the scoring rules
- Show a scoreboard with wins, losses, pushes, and net points per player
- Save the session to a CSV file and load it back
- Terminal menu for all actions

## Future Plans

- Input validation for unknown player names and invalid results
- Unit tests for the scoring rules, including blackjack payouts and pushes
- Undo the last recorded hand
- Strategy helper that recommends a basic strategy move from the player's hand and the dealer's upcard
- Session statistics, such as how often each player followed the strategy chart
- Design doc and README polish

## Tech Stack

- **Language:** Java (JDK 17 or newer)
- **Libraries:** Standard library only (`java.util`, `java.io`, `java.nio.file`)
- **Testing:** JUnit 5 (optional)
- **Build and run:** `javac` and `java` from the command line, or Maven
- **Data storage:** CSV save file with the columns `hand_number,player,result,points`
- **Data sources:** None. All data is entered in the terminal.

## Planning Documents

- [Design Doc](https://docs.google.com/document/d/1MOBPCkWn5Ah0N0Gck78ruwtPZ5Pc8ga9BSoAj6tw7t8/edit): problem statement, tech stack, build plan, and system diagram
- [Eisenhower Matrix](docs/Eisenhower_Matrix_Aarav_Bora_CS_193.pdf): feature prioritization and MVP scope
- [System Diagram](docs/Aarav_Bora_CS_193_System_Diagram.pdf): components and how they interact

## Project Structure

<img width="987" height="407" alt="image" src="https://github.com/user-attachments/assets/6896dbeb-c5d8-40ee-b6e8-6c03a6fca65f" />

## Status

In development. See the commit history for progress against the build plan.
