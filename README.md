# YouTube Video Downloader

This Python script allows you to download videos from YouTube either through a command-line interface (CLI) or a graphical user interface (GUI).

## Features

- Download videos from YouTube in MP4 or WEBM format.
- CLI mode for direct usage from the command line.
- GUI mode for a user-friendly interface.

## Usage

### Command Line Interface (CLI)

To download a video using the CLI mode, run the following command:

```sh
python3 youtube_video_downloader.py --url "YOUTUBE_VIDEO_URL" --path "DESTINATION_FOLDER_PATH" --format "mp4" 
```

Replace "YOUTUBE_VIDEO_URL" with the URL of the YouTube video you want to download, "DESTINATION_FOLDER_PATH" with the path of the folder where you want to save the downloaded video, and "mp4" with the desired file format ("mp4" or "webm").

## Graphical User Interface (GUI)
To use the GUI mode, run the script without any command line arguments:

```sh
python3 youtube_video_downloader.py --gui
```

A graphical user interface will open where you can enter the YouTube video URL, select the destination folder, and choose the file format for the downloaded video.

## Requirements

* Python 3.x
* pytube3
* certifi



