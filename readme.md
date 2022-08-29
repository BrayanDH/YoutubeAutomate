---
title: YoutubeDownloaderAutomate
updated: 2022-08-29 05:13:35Z
created: 2022-08-29 05:00:11Z
latitude: 15.38434150
longitude: -87.80584020
altitude: 0.0000
---

**Massive youtube links downloader**

this script downloads as many links as you provide

you need to have the following dependencies installed:

openpyxl:

`pip install openpyxl`

pytube:

`pip install pytube`

hurry filesize:

`pip install hurry.filesize`

you need to add the links in the links.xls file from line 2 and add the path to the folder where you want the videos to be downloaded.

`path = "your_path_here"`

example with my path:
`path = "E:/Trabajo/Trailers"`

you can control the quality of the video with the following variable(720p default), for example to download at full hd you would set it to 1080p:

`video_quality = "1080p"`

finally you can choose the maximum number of minutes you want to download, by default 28 mins, remember to leave the value in the format "00.00":
`path = "min_video_size = 28.00"`

enjoy.
