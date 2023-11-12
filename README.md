# YouTube Audio/Video Downloader

This project is a simple YouTube audio/video downloader with a user-friendly interface. It allows you to download audio, video, or both from a YouTube link and provides details such as total file size, received size, time left, and a progress bar.

## Usage

1. Paste the URL of the YouTube video from which you want to download audio/video/both (MP3 and MP4).
2. Save the file in your preferred folder.
3. Wait until the status changes from "downloading..." to "downloaded."
4. Once it shows "downloaded," check the folder you chose for the saved file.

## Steps to Use

1. Enter the URL of the YouTube video.
2. Click the "Enter Url and Click" button to fetch available download options.
3. Select the desired download option from the list.
4. Click the "Download" button to initiate the download process.

## Instructions

- The program utilizes the `pafy` library for fetching YouTube video details.
- It provides a list of available download options, including quality, extension, media type, and file size.
- The download progress is displayed with details such as total size, received size, time left, and a progress bar.

## Requirements

- Python 3
- Tkinter
- Pafy library

## Note

Make sure to have Python installed on your machine. You can install the required libraries using the following command:

```bash
pip install pafy
```

Feel free to explore and modify the code to suit your needs. Happy downloading! 🎉
