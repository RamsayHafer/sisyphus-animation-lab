# Sisyphus Animation Lab

Standalone static mobile animation comparison generated solely from `download.mp4`.

- Source: 5.000 s, 150 frames, 30 fps, 1080×1080 H.264
- Test display/assets: 300×300 CSS/render size
- Options: MP4, APNG, animated WebP, CSS horizontal strips, canvas strips, and canvas playback from 150 frames predecoded from the same five strips

Serve this directory over HTTPS. No production application dependencies are used.

| Option | Playback asset(s) | Dimensions | Total bytes |
| --- | --- | --- | ---: |
| Native MP4 | H.264 MP4 | 300×300 | 172,448 |
| Animated APNG | APNG, 150 frames | 300×300 | 10,822,485 |
| Animated WebP | Animated WebP, 150 frames | 300×300 | 1,106,250 |
| CSS sprite strips | 5 static WebP strips | 9000×300 each | 890,786 |
| Canvas sprite animation | 5 static WebP strips | 9000×300 each | 890,786 |
| Canvas predecoded frames | 5 static WebP strips decoded into 150 in-memory frames before playback | 9000×300 source strips; 300×300 decoded frames | 890,786 |
