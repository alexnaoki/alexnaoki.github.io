# Opencv Hydrometer
----------------------------------

**Project description:** A Python application able to read an analog guage (e.g. hydrometer) using [OpenCV](https://opencv.org/) and [Bokeh](https://bokeh.org/). With this tool you will be able to convert a continuous signal (Analog guage) to a discrete signal using a computer vision-type program.

The text below is a summary of the process utilize to achieve the final product. You can get the code utilize at [Github analog-gauge-reader](https://github.com/alexnaoki/analog-gauge-reader).

## 1. Picking a Video File
The first and most important step of utilizing this program will required a **decent** video file.

The factors that makes a **decent** video are the following:
- **No glare** where the analog guage is located.
<img src="../../images/opencv_hidrometro/glare.PNG"/>

- **Decent arrow contrast**.

- **No moving** video file.

## 2. Convert RGB to Gray scale
Even if your file appears to be in Gray scale, it is likely that the video is RGB.

<code>
# Importing OpenCV
import cv2 as cv

# img is a matrix (1048, 1200, 3), where 3 is RGB
img_gray = cv.cvtColor(img, cv.COLOR_BGR2GRAY)
</code>



fsdfs
'''

## 3. warpPerspective
