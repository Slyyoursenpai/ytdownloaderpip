# YouTube Video Downloader

Paste a link, choose quality, download. No manual FFmpeg setup needed.

## Install

```bash
pip install ytdownloaderpip
```

## Usage

```bash
ytdl
```

Or as a Python module if ytdl isn't recognized (common on windows due to path variable mismatch):

```bash
python -m ytdownloaderpip
```

Then paste a YouTube link and choose your format.

## Features

- 1080p, 720p, 480p video, or MP3 audio
- Auto-downloads FFmpeg on first run (~100 MB, cached in app data dir)
- Live progress bars with speed and ETA
- No manual dependencies — pip handles everything

## Requirements

- Python 3.7+
- Internet connection (first run downloads FFmpeg binaries)
