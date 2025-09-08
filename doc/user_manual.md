# Tic Tac Toe Digital Logic Game - User Manual

## Getting Started

### Power Requirements
- **Input Voltage:** 5V DC
- **Power Consumption:** Low power design (few microamperes per IC)
- Connect the positive terminal to the **+5V** input on the PCB
- Connect the negative terminal to the **GND** (ground) input on the PCB

### Initial Setup
1. Ensure all ICs are properly seated in their sockets
2. Connect 5V power supply to the designated terminals
3. Press the **RESET** button to initialize the game
4. All LEDs should be off, indicating the game is ready to start

## How to Play

### Player Assignment
- **Player 1:** Red LED color (goes first)
- **Player 2:** Yellow LED color (goes second)
- Players alternate turns automatically

### Making Moves
1. Press any of the 9 pushbuttons to make your move
2. The corresponding bicolor LED will light up in your assigned color
3. **Anti-Cheat Protection:** Once a button is pressed, it cannot be pressed again
4. The game automatically switches to the next player after each valid move

### Game Rules
- Get three of your colors in a row (horizontal, vertical, or diagonal) to win
- If all 9 positions are filled without a winner, the game is a draw

## Game Status Indicators

### Playing Field
- **9 Bicolor LEDs:** Show the current state of each position
  - Red = Player 1's move
  - Yellow = Player 2's move
  - Off = Available position

### Game Result Indicators
- **Win LED (Bicolor):** 
  - Red = Player 1 wins
  - Yellow = Player 2 wins
- **Draw LED (Green Color):** Lights up when the game ends in a draw

## Game End Behavior

### When Game Ends
- Once a player wins OR the game is drawn, **all pushbuttons are disabled**
- No further moves can be made until reset
- The appropriate result LED will remain lit

### Resetting the Game
- Press the **RESET** button at any time to start a new game
- All LEDs will turn off
- Player 1 (Red) will go first in the new game

## Troubleshooting

### No Response from Buttons
- Check power supply connection (5V DC)
- Press RESET button to clear any stuck states
- Verify all ICs are properly seated in their sockets

### LED Not Lighting Up
- Check if that position was already played (anti-cheat protection)
- Verify power supply is connected
- If problem persists, the corresponding LED may need replacement

### IC Replacement
- **Safe Design:** All ICs are mounted in sockets for easy replacement
- Power off the device before replacing any IC
- Gently remove the faulty IC and insert the replacement
- Ensure correct orientation (notch alignment)

## Safety Notes
- Use only 5V DC power supply
- Do not exceed voltage ratings
- Handle ICs carefully when replacing
- Keep the PCB dry and away from conductive materials

## Technical Specifications
- **Operating Voltage:** 5V DC
- **IC Series:** 74HC and CD4000 series
- **PCB Design:** Dual board system (main logic + I/O interface)
- **Connectivity:** Connected via jumper wires

---

**Enjoy your hardware Tic Tac Toe game!**
