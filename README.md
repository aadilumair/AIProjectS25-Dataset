# AIProjectS25-Dataset

This repository contains sensor log datasets collected for training and evaluating AI agents. The datasets are organized into different categories based on their collection method and purpose.

## File Format

The sensor log files are in CSV format and contain the following columns:

### Basic Information
- `timestamp` - Time of the sensor reading
- `angle` - Car's angle relative to the track axis
- `curLapTime` - Current lap time
- `lastLapTime` - Time of the previous lap
- `racePos` - Current position in the race

### Car State
- `damage` - Current damage level
- `distFromStart` - Distance from the start line
- `distRaced` - Total distance raced
- `fuel` - Current fuel level
- `gear` - Current gear
- `rpm` - Engine RPM
- `speedX`, `speedY`, `speedZ` - Speed components in 3D space
- `trackPos` - Position relative to the track center
- `z` - Height of the car

### Sensor Readings
- `focus_0` to `focus_4` - Focus sensor readings
- `opponent_0` to `opponent_35` - Opponent sensor readings
- `track_0` to `track_18` - Track sensor readings
- `wheelSpinVel_0` to `wheelSpinVel_3` - Wheel spin velocity for each wheel

### Control Inputs
- `accel` - Acceleration input
- `brake` - Brake input
- `clutch` - Clutch input
- `steer` - Steering input
- `keypresses` - Keyboard inputs

## Contributing

If you have additional sensor logs or improvements to suggest, please submit a PR.
