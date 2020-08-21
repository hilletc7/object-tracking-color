# object_tracking_color

Basic opencv object tracker that tracks objects based on their color:
shittycompytervisioncolors.py -v -b
-v: path to the video file (if no path is specified it will default to the webcam)
-b: max buffer size (default buffer size is 10)

Colors supported: green, red, and yellow (feel free to add more)

Make sure to install the required libraries:
pip install collections
pip install copy
pip install numpy
pip install argparse
pip install imutils
pip install cv2
pip install operator

Also, to make your life easier when filtering colors in HSV space, use:
shittycolordetector.py -f -i -w -p
-f: filter range (HSV or RGB)
-i: path to to image
-w: use webcam
-p: preview (default=TRUE)

