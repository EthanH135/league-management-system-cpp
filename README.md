# league-management-system-cpp
# League Management System (C++)

## Overview
Console-based application that manages teams and player data using file input.  
Allows users to view player/team information, update scores, and track wins/losses.

## Features
- Load team and player data from a file (`league.txt`)
- Display player information by team
- Display team statistics (total points, wins, losses)
- Display league-wide information
- Update individual player scores
- Record game results (update wins/losses)

## Skills Demonstrated
- File I/O (reading structured data from files)
- Structured data design (arrays and structs)
- Modular programming (multiple functions)
- Control flow (loops, conditionals, switch-case)
- Debugging and data validation
- User input handling

## How to Run
1. Compile:
   g++ main.cpp -o league
2. Ensure `league.txt` is in the same directory
3. Run:
   ./league
4. Use the menu to interact with the system

## File Format (league.txt)
Each team is defined as:
TeamName  
PlayerName PlayerNumber PlayerPoints (repeated 5 times)

Example:
TeamA  
John 1 10  
Mike 2 8  
...

## Notes
- Program assumes 5 teams with 5 players each
- Data is loaded at runtime from the file
- All updates occur during execution (no file write-back)
