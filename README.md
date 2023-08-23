## Setup

Install OpenCV on your machine (https://docs.opencv.org/4.x/d7/d9f/tutorial_linux_install.html)

Set the library's location in your Makefile, e.g. after installing with homebrew:

    OPENCV_LIBS=$(shell pkg-config --cflags --libs /opt/homebrew/Cellar/opencv/4.6.0_1/lib/pkgconfig/opencv4.pc)

Make and run the the project by running the following bash commands:

    make
    ./proj_runner
