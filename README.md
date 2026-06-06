# 🎵 YAMI - Rhythm Game

YAMI is a rhythm-based music game built with Python, Pygame, Librosa, and OpenCV. The game analyzes a user-selected MP3 file, detects its beats automatically, and generates falling notes that players must hit in sync with the music.

## Features

- 🎵 Automatic beat detection from any MP3 file
- 🎮 Three-lane rhythm gameplay
- 🎥 Selectable animated video backgrounds
- 🏆 Real-time scoring system
- 📂 Custom song support
- 🔄 Restart functionality
- 🎯 Beat filtering and smoothing for better synchronization

## Technologies Used

- Python
- Pygame
- Librosa
- OpenCV
- NumPy
- Tkinter

## Installation

Install the required dependencies:

```bash
pip install pygame librosa opencv-python numpy
```

## Running the Game

Clone the repository and run:

```bash
python main.py
```

When the game starts:

1. Select an MP3 file from your computer.
2. Choose a background video.
3. Wait for the song analysis to complete.
4. Play along with the generated beats.

## Controls

| Key | Action |
|------|---------|
| A | Hit left lane |
| S | Hit middle lane |
| D | Hit right lane |
| Close Window | Exit game |

## How It Works

The game uses Librosa to analyze the selected audio file and detect beat timings. These beats are filtered and smoothed before being converted into falling notes. Players earn points by pressing the correct key when a note reaches the hit line.

### Scoring

- ✅ Successful hit: **+10 points**
- ❌ Missed hit: **-5 points**

## Project Structure

```text
YAMI/
├── main.py
├── mainbg.mov
├── bg2.mov
├── bg3.mp4
├── bg4.mov
├── music6.png
└── README.md
```

## Future Improvements

- Combo and multiplier system
- Accuracy ratings (Perfect, Great, Good, Miss)
- Difficulty levels
- Leaderboards
- Additional note patterns
- Improved beat detection
- Pause and settings menu

## License

This project is licensed under the MIT License.
