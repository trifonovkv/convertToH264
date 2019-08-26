# convertToH264
convertToH264 is a simply script wrapper around a ffmpeg for convert videos to h264 format compatible with iPad Air and later or iPhone 5s and later
## Installing
- make a bin dir in your home dir   `mkdir ~/bin`
- copy this script to the bin dir   `cp /path/to/convertToH264 ~/bin/`
- make this script executable       `chmod +x ~/bin/convertToH264`
## Using
- convert a video file  `convertToH264 source_video_file`  
- convert all files in current dir  `convertToH264 ./*`  
- convert a file with resize (e.g. 240, 360, 480, 720, 1080)  `convertToH264 -s 720 source_video_file`  
