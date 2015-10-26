## Applications

* Detection street / no street
* Detecting traffic signs
* Detecting surgery instruments
* Tumor detection (Image-Processing Techniques for Tumor Detection by Robin N. Strickland)

## Types

* by result:
    * fixed-class
        * binary (street / no street)
    * open: any number of objects might be in the image.
* by data:
    * greyscale / colored
    * single image / time series


## Performance measures
* Quality:
    * Normalized Probabilistic Rand (NPR) index
* Speed
* Stability:
    * Image choice
    * Parameter choice

## Annotation / Label
* Another image with the same widht / height as the original image. Each object
  has exactly one color. Different colors belong to different objects.

## Test sets

* KITTI
* Berkeley Image segmentation database: D. Martin, C. Fowlkes, D. Tal, J.
  Malik, “A Database of Human Segmented Natural Images and its Application to
  Evaluating Segmentation Algorithms and Measuring Ecological Statistics”, Intl
  Conf on Computer Vision, 2001.


## Measures for speed-up
One major non-functional requirement besides the segmentation accuracy is
speed. The following measures can be taken to speed up segmentation algorithms:

* Downsampling (reducing the resolution of the image)
* Superpixels
* Refinement of coarse segmentations


## Segmentation algorithms
* Neural Networks
    * Convolutional Networks
* Mean shift segmentation
    * D. Comaniciu, P. Meer, “Mean shift: A robust approach toward feature
      space analysis”, IEEE Trans. on Pattern Analysis and Machine
      Intelligence, 2002, 24, pp. 603-619
    * http://stackoverflow.com/q/4831813/562769
    * https://en.wikipedia.org/wiki/Mean_shift
* mean shift based fuzzy c-means
* Graph based
    *  P. Felzenszwalb, D. Huttenlocher,“Efficient Graph-Based Image
       Segmentation”, Intl Journal of Computer Vision, 2004, 59 (2)
* Watershed algorithm
* k-Means

## More

* Matting (see http://luthuli.cs.uiuc.edu/~daf/courses/CS-498-DAF-PS/Segmentation.pdf)
* Software:
    * [EDISON](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1047421)

## Problems
* Lens blur
* Smoke
