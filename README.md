# Docker Image with Python 3 and OpenCV

[![Docker Automated buil](https://img.shields.io/docker/automated/jjanzic/docker-python3-opencv.svg)]()

Python version (`latest`, `latest-contrib`): 3.7

OpenCV version (`latest`, `latest-contrib`): 4.1.2

## Available Docker Tags

Image tagged with `:contrib` contains docker image built with [contrib modules](https://github.com/opencv/opencv_contrib/).

- `latest` (`master` branch)
- `latest-contrib` (`opencv_contrib` branch)
- `v4.1.2`
- `v4.1.2-contrib`

## Usage

    docker run -it atup/docker-opencv python
    >>> import cv2
