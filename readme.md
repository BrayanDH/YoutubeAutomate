# Massive YouTube Links Downloader

## Description

Massive YouTube Links Downloader is a powerful script that allows you to download as many YouTube videos as you provide. It simplifies the process of bulk video downloading from YouTube, making it easy and efficient.

## How to Use

1. Install Dependencies:

   Before using the script, ensure you have the required dependencies installed. Run the following command in your terminal:

   ```
   pip install -r requirements.txt
   ```

2. Prepare the Links:

   Add the YouTube links you want to download in the `links.xls` file, starting from line 2. Make sure to provide one link per row, starting from the second row.

3. Set the Download Folder:

   Specify the path to the folder where you want the downloaded videos to be saved. Modify the `path` variable in the script:

   ```python
   path = "your_path_here"
   ```

   For example, if you want to save the videos in the folder `E:/Trabajo/Trailers`, set the `path` as follows:

   ```python
   path = "E:/Trabajo/Trailers"
   ```

4. Choose Video Quality:

   You can control the quality of the downloaded videos using the `video_quality` variable. By default, it is set to download videos in 720p. To download videos in Full HD (1080p), set the `video_quality` as follows:

   ```python
   video_quality = "1080p"
   ```

5. Set Maximum Duration:

   You can also choose the maximum duration of the videos you want to download. By default, it is set to 28 minutes. Make sure to format the value in the `"00.00"` format:

   ```python
   max_duration = "28.00"
   ```

6. Run the Script:

   Execute the script, and it will start downloading the YouTube videos based on the provided links, saving them in the specified folder.

Enjoy downloading your YouTube videos effortlessly with Massive YouTube Links Downloader!
