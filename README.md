# Video Frame Extraction Notebook

## Overview
This Jupyter Notebook provides a simple and efficient workflow for downloading a video, saving it to Google Drive, and extracting frames from each quartile of the video. The project leverages Google Colab and Google Drive integration for seamless operation.

## Features
- **Video Downloading**: Downloads a video file from a specified URL using wget tool
- **Google Drive Integration**: Save the downloaded video directly into your Google Drive for easy access.
- **Frame Extraction**: Process the video to extract frames at the 25%, 50%, 75%, and 100% marks.

## Requirements
- Google Account
- Google Drive
- Google Colab
- Python libraries: `opencv-python`, `google.colab.patches`, `os`, `datetime`, and `random`

## Usage
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Follow the instructions in the notebook to:
   - Authenticate your Google Drive.
   - Provide the video URL for download.
   - Specify the output location in your Drive.
3. Run the frame extraction process to save the key frames from the video.

## Installation
No installation is required for Google Colab.

## How It Works
1. **Download Video**: The notebook downloads a video from the provided URL using wget.
2. **Save to Google Drive**: The video file is moved to your Google Drive using the Colab Drive integration.
3. **Extract Frames**: Using OpenCV, the notebook calculates the frame positions for each quartile and some of them as images in your Drive.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

