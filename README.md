# Image Processing / Grundlagen Bildverarbeitung (PS)


This repository contains solutions to the assignments of the course "Image Processing & Computer Vision" conducted by [Prof. Dr. Kwitt](https://rkwitt.github.io/) at the University of Salzburg, Department of Computer Science.

The course is part of the Master degree programs "Computer Science" and "Applied Image and Signal Processing". [The Image Processing & Computer Vision course](https://github.com/rkwitt/teaching/tree/master/WS1718/IP) was conducted in WS 2017.


## Assignments
```bash
### Assignment 1

##### Exercise 1.1(5 points)
Write a Python function avg_H_global which takes as input the filename of an RGB image and computes the average value of the H channel. This value should be returned

##### Exercise 1.2 (5 points)
Write a Python function avg_H_per_block which takes, as input, a filename of an RGB image as well as a tuple (N,M) that specifies a block size. 

### Assignment 2

##### Exercise 2.1 (5 points)

Write a Python function which computes a Gaussian pyramid of a grayscale image. In particular, the function should take either a grayscale image as input, or a RGB color image and compute a N-level Gaussian pyramid decomposition. We simplify this example

##### Exercise 2.2 (5 points)
Write a Python function that takes, as input, a grayscale image and performs histogram equalization. The function should output the histogram-equalized image.

##### Exercise 2.3 (10 points)
Write a Python function that takes two images, a source image and a target image (both grayscale) and then matches the source image's histogram to the target images' histogram.

### Assignment 3

##### Exercise 3.1 (5 points)
implemention of median filtering with different neighborhood sizes and implemention to compute the peak-signal-to-noise ratio (PSNR)

##### Exercise 3.2 (5 points)
same as Exercise 3.1 from above, but use a Gaussian smoothing filter and vary the values for sigma (i.e., the standard deviation of the Gaussian filter).

### Assignment 4

##### Exercise 4.1 (10 points)
Write a Python function that performs smoothing (with a Gaussian kernel) in the Fourier domain.


### Assignment 5

##### Exercise 5.1 (10 points)
Implementing an additive (spread-spectrum) watermarking scheme, based on the 2D wavelet transform.

##### Exercise 5.2 (10 points)
Implementing a simple (correlation-based) watermark detector for the watermarking algorithm of Exercise 5.1 and evaluate this detector with a couple of randomly chosen watermarks.


### Assignment 6

##### Exercise 6.1 (15 points)
In this exercise, we will implement a very simple version of the Histogram-Of-Oriented-Gradients (HOG) descriptor of an image(region).

##### Bonus (5 points):
Download the 15 scenes dataset and select a couple of images from each category. Then, compute for each grayscale image its simple HOG descriptor. Voila, if you now do 1-Nearest Neighbor classification (e.g., using the Euclidean distance between the vectors) you have a first, admittely very simple, image classifier.


### Assignment 7

##### Exercise 7.1 (20 points)
In this exercise, we will implement a relatively simple image segmentation algorithm that is similar to the ideas presented in the SLIC superpixels paper.
```

### Recommendation

I do recommend to use Anaconda Python. For Mac/Linux/Windows, download the
Anaconda installer from [here](https://www.anaconda.com/download) and follow
the installation instructions. To check your installation, you can try to
start the Python interpreter and load `skimage` and `sklearn` (which come
as part of the Anaconda installation). E.g.,

```bash
python
>> import skimage
```
If this works, your are all set. To start a Jupyter notebook, run

```bash
jupyter notebook
```
### Tools

* Python 2.7 or 3
* Skimage Framework
* OpenCV Framework
* Numpy / Scipy / Pickle Framework




