# VirtualCanvasPython

This project helps in tracking the hand over the camera. Inputting the image frame by frame and tracking the finger to draw a line on the virtual canvas window. Then the window is merged over the image frames and shown as output on the video overlay itself, all in realtime.

Heavy usage of Deque techniques and numpy.

import numpy as np
import cv2
from collections import deque
