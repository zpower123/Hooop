# Hooop
This is a recreation of the board game "Hooop" made using Java. This project was created with a focus on utilizing Java Swing and Object Oriented Programming. The basic premise of the game is that each player is trying to move their team of 3 frogs into their opponents' home bases. The game board consists of 2 or 4 team bases depending on player count as well as a 5x5 grid of lily-pads all connected together through bridges. The players also have access to 4 special action cards that can be used to their advantage. The game includes 2 or 4 player options, save and load functionality and accommodates for color blindness.

# Rules
1. Each player has 3 frogs on their team as well as 4 one-time use action cards called "Parachute", "Extra Jump", "Extra Bridge" and "Bridge Removal".
2. The goal is to have your frogs hop across the lily pads in order to reach your opponents' bases.
3. Each turn the player has the option to either have a frog hop across one lily pad, rebuild a bridge that is missing from the board or use a action card.
4. Once a frog has hopped from one lily pad to another, the bridge connecting the lily pads is removed from the board.
5. You may decide to have your frog jump onto another frog, pushing the opponent frog on to any connected lily pad of your choosing.
6. If you use the "Parachute" action card, you are allowed to move your frog to an adjacent lily pad that is not connected by a bridge.
7. If you use the "Extra Jump" action card, you are given two turns and are allowed to move your frog twice in a row.
8. If you use the "Extra Bridge" action card, you are given two turns and are allowed to place two bridges in a row.
9. If you use the "Bridge Removal" action card, you are allowed to remove a bridge of your choosing from the board.
10. In 2 player mode, you must get all of your frogs into the opponent home base to win.
11. In 4 player mode, you must get one of your frogs into all three opponent home bases to win.

# How to Play a Game

1. Clone the repository by entering the following line into your terminal:
```
git clone https://github.com/zpower123/Hooop
```
2. Open the game by running the jar file ```Hooop.jar``` or entering the following lines into your terminal:
```
cd <filepath> # replace with installation directory
java -jar Hooop.jar
```
3. Start or load a game
<img width="1919" height="1079" alt="Start Screen" src="https://github.com/user-attachments/assets/6eb8e7b3-e53c-4675-a32f-302c6042b1e0" />
4. Read rules and select your mode, 2 player or 4 player
<img width="1919" height="1079" alt="Game Rule and Player Selection Screen" src="https://github.com/user-attachments/assets/0f1a7d9b-e503-4212-a030-9192ba96242f" />
5. Pick the names for each player and start the game
<img width="1919" height="1079" alt="Team Selection" src="https://github.com/user-attachments/assets/df1b71f2-ed30-45d9-9fc6-e1dd482f78fb" />
6. Play the game and enjoy!
<img width="1919" height="1079" alt="Gameplay Start" src="https://github.com/user-attachments/assets/72c0337f-1e8f-48f6-9d9b-efad0396f7f1" />
<img width="1919" height="1079" alt="Gameplay Shot" src="https://github.com/user-attachments/assets/2c9635e8-abb3-4796-8c62-6a664f45277f" />

# Known Bugs
- Extra Bridge Action Card doesn't allow a second bridge to be placed
- Winning scores are not yet properly visualized
- Display issues when not using a screen that uses 1920x1080 resolution
- You can choose to have AI opponents but the actual AI player functionality is not yet implemented
- Other minor gameplay bugs

# Contributions
My contributions to this project include but are not limited to:

- Implementation of "Extra Jump" action card
- Functionality for winning a game
- Logic for counting score
- Some of the logic for taking a turn and switching turns
- Testing and debugging

Other contributions were made by my classmates **Hamzeh Alhyari** and **Kiara Jenkins**

# Credits and Attributions
This project is a digital recreation using Java of the board game Hooop! and was completed in a group as part of the course COMP 2005 "Software Engineering" at Memorial University of Newfoundland. This project is not affiliated with or endorsed by the original designer, artist, or any publisher.

- Designer: Adam Kałuża
- Illustrator: Piotr Socha
