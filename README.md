# vimeo-downloader
This a script in NodeJs to download Vimeo videos

# Instrunctions

`npm install fs url https`

`node vimeo-downloader.j`

# Notes
The output are two files, one is MP4 file with video only and another is M4A audio file.

You should use ffmpeg to merge these two files

`ffmpeg -i video.mp4 -i audio.m4a -acodec copy -vcodec copy output.mp4`
