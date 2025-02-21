

# File To Video

## Preparation

1. First, create the `results` directory:
   ```bash
   mkdir results
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. If you need to decode from YouTube, download `yt-dlp` from the official link:
   [yt-dlp GitHub Releases](https://github.com/yt-dlp/yt-dlp?tab=readme-ov-file#release-files)

## How to use

### Encode a File
To encode a file, use the following command:
```bash
python encoder.py -i /path/to/your/file.zip
```

### Decode a File
To decode a file, use the following command:
```bash
python decoder.py -i /path/to/your/file.avi
```

The encoded or decoded file will be saved in the `results` directory that you created earlier.

### Decode from YouTube
To decode a video from YouTube, use the following command:
```bash
python download_youtube.py
```

---

**Note:** Make sure to replace `/path/to/your/file.zip` or `/path/to/your/file.avi` with the actual path to your file.

