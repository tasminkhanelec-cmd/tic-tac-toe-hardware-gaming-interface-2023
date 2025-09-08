# Digital Logic Tic Tac Toe

A hardware-based Tic Tac Toe game implemented using digital logic circuits, featuring flip-flops, logic gates, and bicolor LEDs. This project demonstrates fundamental digital logic design concepts through an interactive gaming experience.

## 🎮 Features

- **Hardware-Based Gameplay**: Physical buttons and LED indicators for interactive experience
- **Anti-Cheat Protection**: Flip-flop based memory prevents button re-pressing
- **Automatic Win Detection**: Logic circuits identify winning combinations instantly
- **Visual Player Indicators**: Bicolor LEDs show Player 1 (Red) and Player 2 (Yellow)
- **Draw Detection**: Separate LED indicates when game ends in a tie
- **Reset Functionality**: Single button to restart the game
- **Low Power Design**: Operates on 5V with minimal current consumption

## 🛠 Hardware Components

### Logic ICs
- **74HC86N** (6x): XOR gates for player identification
- **74HC08N** (4x): AND gates for winning logic
- **74HC32N** (1x): OR gate for game logic
- **74HC04N** (1x): NOT gates for signal inversion
- **74HC11N** (8x): 3-input AND gates for winning combinations
- **CD4072BE** (2x): 4-input OR gates for extended logic
- **CD4013B3** (18x): D-type flip-flops for move storage

### Other Components
- 14-pin DIP IC sockets (45x) for easy maintenance
- Bicolor LEDs (10x) for game position indicators
- Single-color LED (1x) for draw indication
- 220Ω resistors (2x) for current limiting
- Push buttons (9x) for player input
- Custom dual-PCB design

## 🎯 How to Play

1. **Power On**: Connect 5V power supply and press RESET
2. **Make Moves**: Players alternate pressing buttons (1-9)
   - Player 1: Red LEDs (goes first)
   - Player 2: Yellow LEDs (goes second)
3. **Win Condition**: Get three in a row (horizontal, vertical, or diagonal)
4. **Game End**: Win or Draw LED lights up, all buttons disabled
5. **New Game**: Press RESET to start over

## 🔌 Power Requirements

- **Input Voltage**: 5V DC
- **Current Draw**: Low power (few microamperes per IC)
- **Total Power**: <1W typical operation
- **Power Connector**: Standard DC jack or terminal block


## 📄 License

This project is open source and available for educational use. Please cite this work if used in academic or educational contexts.

## 🤝 Contributing

Contributions welcome! Please read the documentation and submit pull requests.

---

**⚡ Bringing digital logic to life through interactive gaming!**
