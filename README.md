# Universal Converter & Player

## Overview
Universal Converter & Player is a powerful tool that allows users to convert and play various media file formats. This application supports video, audio, and document formats while providing an intuitive and user-friendly interface built with `Tkinter` and `CustomTkinter`.

## Features
- **File Conversion**: Convert files to different formats including MP4, AVI, MOV, MP3, WAV, FLAC, MKV, JPG, PNG, PDF, DOCX, and TXT.
- **Video Quality Selection**: Convert videos to 480p, 720p, or 1080p.
- **Media Player**: Play videos and audio files with playback controls.
- **Progress Tracking**: Real-time conversion and playback progress bars.
- **FFmpeg Auto-Installation**: Automatically downloads and installs FFmpeg if missing.
- **Responsive UI**: CustomTkinter-based modern and adaptive interface.
- **Seek & Skip**: Jump forward or backward while playing media.
- **Full-Screen Mode**: Toggle full-screen for video playback.

## Installation

### Prerequisites
Ensure you have Python installed on your system. The application requires `FFmpeg` and the following dependencies:

### Install Dependencies
```sh
pip install pillow opencv-python requests pygame customtkinter
```

### Run the Application
```sh
python main.py
```

## Usage
1. **Select a File**: Click on `📂 Select File` to choose a media file.
2. **Choose Output Format**: Select a desired conversion format from the dropdown menu.
3. **Set Quality (for videos)**: Choose between 480p, 720p, or 1080p.
4. **Convert File**: Click `🔄 Convert` to begin file conversion.
5. **Play Media**: Use the built-in player to watch videos or listen to audio.
6. **Control Playback**:
   - ▶ Play / ⏸ Pause / ⏹ Stop
   - ⏪ -10s / ⏩ +10s for video skipping
   - 🔳 Full-Screen Mode

## FFmpeg Installation
The program will attempt to install `FFmpeg` automatically. If it fails, install it manually:
- **Windows**: [Download FFmpeg](https://www.gyan.dev/ffmpeg/builds/)
- **MacOS**: `brew install ffmpeg`
- **Linux**: `sudo apt-get install ffmpeg`

## Future Improvements
- Support for batch file conversion
- More document format conversions
- Enhanced UI themes and customization

## Contributing
Feel free to submit issues or pull requests to improve the application!

## License
This project is licensed under the MIT License.

