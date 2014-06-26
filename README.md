# _Balls Experiment_

This is a try out project for compiling something and running it in OpenCV. It's based on Hough Transform samples, and I've run it on images containing rubber balls to see if the Hough transform is effective in detecting them.

## Project Setup

This project was compiled with OpenCV version 2.4.8 on Ubuntu 14.04. To compile and run do the following:

```
cmake .
make
./houghcircles image.jpg
./HoughCircle_Demo image.jpg
```
In case you've downloaded all the images you want to run Hough Circles on to a folder called `data`, run the following:
```
ls data | xargs -I {} ./houghcircles data/{}
```

