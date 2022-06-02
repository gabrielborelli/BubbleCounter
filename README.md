# BubbleCounter
Simple algorithm using OpenCV for bubble counting

The jupyter-notebook file can be modified and applied directly. A Python script can be downloaded if preferred.

The code works for video files previously recorded. Some adjusts must be made for real time applications. 
Once the frames are processed and saved, one can create videos or gifs. An example using FFMEG is given below.

	$ ffmpeg -i frame_process-%04d.png out.mp4

The *%04d* corresponds to all the files with 4 digits suffix. This should be modified accordingly.
Note that the default fps is 25. All the options are given in help, by typing

	$ ffmpeg -h