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
- Undo the last recorded hand
- Strategy helper that recommends a basic strategy move from the player's hand and the dealer's upcard
- Session statistics, such as how often each player followed the strategy chart
- Poker score tracking as a separate scoring module

## Tech Stack

- **Language:** Java (JDK 17 or newer)
- **Libraries:** Standard library only (`java.util`, `java.io`, `java.nio.file`)
- **Testing:** JUnit 5 (optional)
- **Build and run:** `javac` and `java` from the command line, or Maven
- **Data storage:** CSV save file with the columns `hand_number,player,result,points`
- **Data sources:** None. All data is entered in the terminal.

## Project Structure
<img width="987" height="407" alt="image" src="https://github.com/user-attachments/assets/6896dbeb-c5d8-40ee-b6e8-6c03a6fca65f" />


## Status
In development. See the commit history for progress against the build plan.

