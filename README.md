# convertToH264
convertToH264 is a simply script wrapper around a ffmpeg for convert videos to h264 format compatible with iPad Air and later or iPhone 5s and later
## Installing
<pre>
<ul>
  <li>make a bin dir in your home dir   <code>mkdir ~/bin</code></li>
  <li>copy this script to the bin dir   <code>cp /path/to/convertToH264 ~/bin/</code></li>
  <li>make this script executable       <code>chmod +x ~/bin/convertToH264</code></li>
</ul>
</pre>
## Using
convert a video file
<pre><code>convertToH264 source_video_file</code></pre>
convert all files in current dir
<pre><code>convertToH264 ./*</code></pre>
convert a file with resize (e.g. 240, 360, 480, 720, 1080)
<pre><code>convertToH264 -s 720 source_video_file</code></pre>
