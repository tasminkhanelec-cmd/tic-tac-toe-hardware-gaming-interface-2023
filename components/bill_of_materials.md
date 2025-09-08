# Bill of Materials - Tic Tac Toe Digital Logic Game

## Component Summary

| Component | Per Unit Price (BDT) | Quantity | Total Cost (BDT) | Description |
|-----------|---------------------|----------|------------------|-------------|
| 74HC86N | 25 | 6 | 150 | Quad 2-Input XOR Gate |
| 74HC08N | 25 | 4 | 100 | Quad 2-Input AND Gate |
| 74HC32N | 25 | 1 | 25 | Quad 2-Input OR Gate |
| 74HC04N | 25 | 1 | 25 | Hex Inverter (NOT Gate) |
| 74HC11N | 25 | 8 | 200 | Triple 3-Input AND Gate |
| CD4072BE | 60 | 2 | 120 | Dual 4-Input OR Gate |
| CD4013B3 | 30 | 18 | 540 | Dual D-Type Flip-Flop |
| 14 PIN DIP IC SOCKETS | 5 | 45 | 225 | IC Socket for easy replacement |
| 220 OHM RESISTANCE | 1.5 | 2 | 3 | Current limiting resistors |
| Common Cathode LED | 6 | 10 | 60 | Bicolor LEDs for game positions |
| Single colored LED | 5 | 1 | 5 | Draw indicator LED |
| Jumper | 100 | - | 100 | Inter-board connections |
| PCB | 2000 | - | 2000 | Custom PCB fabrication |
| Soldering | 3200 | - | 3200 | Assembly service |
| **Total** | - | - | **6753** | **Project Cost** |

## Power Requirements
- **Operating Voltage**: 5V DC
- **Current Consumption**: Low power design (few microamperes per IC)
- **Total Power**: < 1W typical operation

## IC Function Summary

| IC Type | Function | Usage in Project |
|---------|----------|------------------|
| 74HC86N | XOR Gate | Player turn identification |
| 74HC08N | AND Gate | Winning condition logic |
| 74HC32N | OR Gate | Game state logic |
| 74HC04N | NOT Gate | Signal inversion |
| 74HC11N | 3-Input AND | Winning combination detection |
| CD4072BE | 4-Input OR | Extended logic operations |
| CD4013B3 | D Flip-Flop | Move storage, anti-cheat mechanism |

## Notes
- All ICs are socketed for easy maintenance and replacement
- PCB cost includes fabrication for two separate boards
- Soldering cost includes professional assembly service
- Jumper wires provide flexible connection between boards
- Component prices are in Bangladeshi Taka (BDT) as of project date
