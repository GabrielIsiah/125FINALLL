# CS125 Rhythm Game Project

A rhythm-based game developed as a CS125 project. The game features multiple songs, difficulty levels, and a pattern mode for practice. Players hit arrows in time with music while enjoying background videos and various game modes.

## System Requirements

- Python 3.8 or higher
- Windows 10/11 or macOS
- 4GB RAM minimum
- 500MB free disk space
- Audio output device
- Keyboard (for controls)

## Project Structure

- `CS125-RhythmGame/` - Main game directory containing all game files
  - `game/` - Core game logic and components
  - `assets/` - Game resources (songs, videos, sprites)
  - `Utility/` - Utility functions and managers
  - See the [game's README](CS125-RhythmGame/README.md) for detailed information

## Features

- Multiple songs with unique arrow patterns
- Three difficulty levels (Easy, Medium, Hard)
- Pattern mode for practice
- Background video support
- Gravity mode in Medium and Hard difficulties
- Pause/Resume functionality
- Score tracking and combo system
- Hit feedback system
- Combo multiplier system
- High score tracking
- Customizable arrow speed
- Visual and audio feedback

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/CS125-MP.git
cd CS125-MP
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Game

1. Ensure you're in the project root directory:
```bash
cd CS125-MP
```

2. Run the main script:
```bash
python CS125-RhythmGame/main.py
```

## Controls

- `D` - Left arrow
- `F` - Down arrow
- `J` - Up arrow
- `K` - Right arrow
- `ESC` - Pause/Resume game
- `SPACE` - Select/Confirm in menus

## Game Modes

### Normal Mode
- Play through songs with predefined arrow patterns
- Arrows spawn from the top and move downward
- Hit arrows when they reach the hit zone
- Score points based on timing accuracy

### Gravity Mode (Medium/Hard)
- Arrows change direction periodically
- Countdown before direction changes
- Adds challenge to timing and coordination
- Random duration between switches

## Troubleshooting

### Common Issues

1. **Audio not playing**
   - Check if your system's audio is working
   - Ensure the game's volume is not muted
   - Verify that the audio files are present in the assets folder

2. **Game runs slowly**
   - Close other resource-intensive applications
   - Lower the game's resolution in settings
   - Update your graphics drivers

3. **Missing dependencies**
   - Run `pip install -r requirements.txt` again
   - Ensure you're using the correct Python version
   - Try creating a new virtual environment
