# Docker Image with Python 3 and OpenCV

[![Docker Automated buil](https://img.shields.io/docker/automated/jjanzic/docker-python3-opencv.svg)]()

Python version (`latest`): 3.7

OpenCV version (`latest`): 4.1.2

Image tagged with `:contrib` contains docker image built with [contrib modules](https://github.com/opencv/opencv_contrib/)

List of available docker tags:

- `4.1.2` (`master` branch)
- `contrib-4.1.2` (`opencv_contrib` branch)

## Usage:

    docker run -it atup/docker-opencv python
    >>> import cv2
