
# Volumetric Video Loader

## Overview

This project allows users to load and visualize PLY files efficiently in Unity. It supports real-time playback, video recording, and folder browsing for an enhanced user experience.

## Features

- **PLY File Import**: Load 3D models from PLY files.
- **Playback Control**: Slider to navigate through frames.
- **Video Recording**: Record the rendered sequence and save it as a video.
- **Keyboard Shortcuts**:
  - `Space`: Start/Stop video recording.
  - **Slider**: Navigate frames.
- **Folder Selection (WebGL Support)**: Browse folders via a custom JavaScript integration for WebGL.

## How to Use (Standalone .exe)

### Installation

1. Download the latest `.zip` file from the release section.
2. Extract the contents to a folder of your choice.

### Running the Application

1. Open the extracted folder.
2. Double-click on `VolumetricVideoLoader.exe` to launch the application.

### Using the Application

1. Click **Browse Folder** to select the directory containing your PLY files.
2. Use the **slider** to navigate through the sequence.
3. Click **Start Recording** to record the sequence as a video.
4. Press `Space` to stop recording.
5. The video will be saved in a floder named VideoRecorder and the file name will be output.mp4.

## Known Issues

- **WebGL Folder Selection**: Requires JavaScript integration; may not work in all browsers.

## Future Improvements

- **GPU Acceleration**: Faster processing using Compute Shaders.
- **WEB version**: WEB version in progress
- Add support for more 3D formats (OBJ, STL, etc.).
- Improve rendering performance for larger datasets.



