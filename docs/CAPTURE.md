ffmpeg to animated gif (via https://crates.io/crates/gifski):

```bash
ffmpeg -i "demo1.mov" -f yuv4mpegpipe - | gifski -o "demo1.gif" --height 480 -  
```
