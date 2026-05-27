# traffic-light-controller
An Arduino-based 3-way (T-shaped) intersection traffic light controller with pedestrian crossing system. Built from scratch as a first EE project before studying Electrical Engineering at NC State University.

## Project Goal
Simulate a real-world 3-way T-shaped intersection with:
- 9 LEDs (red, yellow, green × 3 directions)
- Pedestrian push button with walk/don't walk signals
- Safe state machine logic — no conflicting greens ever

## Build Progress
### Week 1 — Single direction wiring test
- Wired 9 LEDs across 3 signal groups on breadboard
- Wrote first Arduino C++ code using digitalWrite and delay
- Debugged typo errors (degitalWrite) and learned to read 
  compiler error messages
- Confirmed all LEDs light up sequentially

## What I Learned So Far
- How breadboards work (horizontal row connections)
- Why resistors protect LEDs (Ohm's Law)
- Why Arduino needs code to control pins
- How to read compiler errors and fix bugs

## Hardware
- ELEGOO UNO R3
- LEDs: 3 red, 3 yellow, 3 green
- 220Ω resistors
- Breadboard + jumper wires

## Upcoming
- Week 2: Button input and digitalRead
- Week 3: Full 3-way intersection logic
- Week 5: Replace delay() with millis()
- Week 7: Pedestrian state machine
