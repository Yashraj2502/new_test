# YouTube Download Manager

A self-hosted YouTube video downloader and library manager with a web interface.

## Features
- Download individual videos or entire playlists
- Automatic detection of YouTube Shorts
- Organized storage by uploader
- Web-based interface for browsing and playback
- SQLite database for metadata
- Tag support for organization

## Setup

1. Install dependencies:
```bash
pip install fastapi uvicorn yt-dlp pydantic
```

2. Run the server:
```bash
uvicorn web_interface:app --reload --host 0.0.0.0 --port 8000
```

3. Open browser: `http://localhost:8000`

## Requirements
- Python 3.8+
- ffmpeg (for video processing)

## Configuration
Edit `youtube_manager.py` to customize:
- Download quality
- Storage paths
- Rate limiting

## License
MIT
