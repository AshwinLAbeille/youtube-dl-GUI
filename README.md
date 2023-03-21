# youtube-dl-GUI
My personal colelction of scripts to run yt-dlp

[v1](https://github.com/AshwinLAbeille/youtube-dl-GUI/blob/main/.github/workflows/YT-DLP%20Downloader.hta) is the first prototype, I used ChatGPT

It can download videos+audio at the best quality then converts it into .mp4
It can download audio at the best quality, then converts it into .wav

CONS : Not flexible, file sizes after conversion are huge
should change : add numerous format in a drop-down menu, include one named "BEST" (for video and audio)
         add a subtitle case (check if you want to embed subtitles)
         add a pop-up windows at first, asking if you installed yt-dlp first, if not, redirects to website or installs yt-dlp
         add last box to be format, converts it into that format.

[v2](https://github.com/AshwinLAbeille/youtube-dl-GUI/blob/main/.github/workflows/YT-DLP%20Downloaderv2.hta) second prototype
added a button that installs yt-dlp and ffmpeg via winget automatically

should change : find a way to add '%LOCALAPPDATA%\Microsoft\winget\packages' to the path with a button
                
