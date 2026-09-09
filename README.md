# Origins of Life – Interactive RFID Circuit Board

An educational RFID-based circuit board built for the **Palestine Institution of Biodiversity and Sustainability (PIBS)**, designed to teach kids about the history of life on Earth through hands-on, game-based learning.

## About the Project

This project turns the story of evolution into an interactive game. Starting from the very first organisms on Earth, players progress level by level through the timeline of life, learning how species emerged and evolved over time.

The board presents a hint describing an organism (e.g. *"I am a single-celled organism, one of the first forms of life on Earth"*). Students are given a set of RFID cards, each printed with a picture and name of an organism. They must choose the card they believe matches the hint, scan it using the RFID reader, and place it in the designated spot on the board.

If the answer is correct, the game advances to the next level/organism in the evolutionary timeline. If incorrect, the board signals the player to try again.

The system uses a single RFID tracker/reader that acts as a moving checkpoint — advancing through the sequence of organisms (e.g. Bacteria → ... → more complex life forms) as players answer correctly, reinforcing the correct order of evolutionary history.

## How It Works

1. The board displays/announces a hint about an organism.
2. The player selects the RFID card they believe is the correct answer.
3. The card is scanned at the designated spot connected to the RFID reader.
4. The system checks the scanned ID against the expected answer for the current level.
5. **Correct:** the game advances to the next organism/level and gives a new hint.
6. **Incorrect:** the game prompts the player to try again.
7. The cycle repeats until the full timeline of life has been completed.

## Hardware Components
List will be added soon...

## Software / Firmware

- Written in `[python]`
- Handles:
  - Reading RFID tag IDs
  - Comparing scanned tag to expected organism for current level
  - Level progression logic
  - Feedback output (LEDs, sound and display)

## Repository Structure

├── firmware/ # Microcontroller source code
├── hardware/ # Circuit board design files (schematics, PCB layout)
├── docs/ # Documentation, wiring diagrams, organism list
├── assets/ # RFID card designs, images, labels
└── README.md

## Educational Goal

This project aims to make the story of life's origins and evolution engaging and tangible for children, encouraging curiosity about biodiversity and natural history through interactive, hands-on learning.

## About PIBS

The Palestine Institute for Biodiversity and Sustainability (PIBS) and the Palestine Museum of Natural History (PMNH) were established to research, educate about, and conserve our natural world, culture and heritage. We use this knowledge to promote responsible human interactions with our environment.

## License

All rights reserved to PIBS

## Contributors

Samir Daoud
Georgeous Abu Ghattas
Atallah Abu Ghattas
