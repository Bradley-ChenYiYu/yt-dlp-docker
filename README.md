# yt-dlp-docker  

## Build Image  

```bash
docker build --network host -t yt-dlp-runtime .
```

## Usage  

```bash
docker run --rm -it --network host -v "$PWD:/work" -w /work yt-dlp-runtime -S "ext:mp4:m4a" -o "SEA_4.%(ext)s
" "https://youtu.be/GfJrqiBaLSE?si=bOWws8x113lCFi0K"
```

## Acknowledgment  

- [yt-dlp](https://github.com/yt-dlp/yt-dlp)  
