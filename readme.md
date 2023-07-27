# Massive youtube links downloader

This script downloads as many links as you provide

you need to have the following dependencies installed:

```
pip install -r requirements.txt
```

you need to add the links in the links.xls file from line 2 and add the path to the folder where you want the videos to be downloaded.

```
path = "your_path_here"
```

example with my path:

```
path = "E:/Trabajo/Trailers"
```

you can control the quality of the video with the following variable(720p default), for example to download at full hd you would set it to 1080p:

```
video_quality = "1080p"
```

finally you can choose the maximum number of minutes you want to download, by default 28 mins, remember to leave the value in the format "00.00":

```
path = "min_video_size = 28.00"
```

enjoy.
