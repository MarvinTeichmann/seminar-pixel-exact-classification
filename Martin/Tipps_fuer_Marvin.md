## Data sets

### Berkeley
> Our dataset for this evaluation is the Berkeley Segmentation Database [5],
> whichcontains 300 natural images with multiple ground truth hand
> segmentations of each image.
>
> [5] D. Martin, C. Fowlkes, D. Tal, J. Malik, “A Database of Human Segmented
> Natural Images and its Application to Evaluating Segmentation Algorithms and
> Measuring Ecological Statistics”, Intl Conf on Computer Vision, 2001.


### Medicine

*  http://mis.haifa.ac.il/~ishimshoni/SegmentCrypt/Download.htm


#### Brain segmentation dataset

> Segmentation of brain MR images: The IBSR real T1- weighted brain-MR dataset
[10] is chosen, in which three tissues, cerebrospinal (CSF), gray matter (GM),
and white matter (WM) are to be segmented. Each brain data contains 128 scanned
slices. The dataset makes available expert hand segmentations of each brain in
the dataset, which we use for training and testing the classifier. In our
tests, 4 brain images were randomly selected for training, and 14 brain images
were used for testing. In order to evaluate the quality of our segmentations,
we compute the dice metric for the 14 test datasets [11]. Results are compared
to the work of Awate et al [11] who showed overall high quality in segmenting
the same dataset using a semi-supervised learning approach.

Source: A pixel classification system for segmenting biomedical images using
        intensity neighborhoods and dimension reduction

* The IBSR real T1-weighted brain-MR dataset: Internet Brain Segmentation
  Respository (IBSR), “http://www.cma.mgh.harvard.edu/ibsr,”


#### Nuclei in fluorescence images

> Segmentation of nuclei from fluorescence images: expert segmented nuclei
images are available from Dr. Murphy’s group at Carnegie Mellon University
[13]. The data consists of 48 2D images, out of which 6 images were randomly
selected for training and the remaining images were used for test- ing. The
results were assessed following Coelho et al. [13]. Three types of metrics are
used for evaluation: (1) the Rand and Jaccard indices, which measure the
fraction of the pixel pairs where the segmentation and the ground truth agree.
The larger the value, the better the result. (2) Error Counting: split, merged,
added, and missing, which counts the errors in segmenting nuclei. (3)
Spatially-Aware Evaluation: NSD and Hausdorff metrics, which measure the
distance of segmented nuclei to the ground truth. We calculate the mean values
for all test images, and compare with the best results in [13].

Source: A pixel classification system for segmenting biomedical images using
        intensity neighborhoods and dimension reduction

* L.P. Coelho, A. Shariff, and R.F. Murphy, “Nuclear segmentation in microscope
  cell images: a hand-segmented dataset and comparison of algorithms,” in ISBI
  2009. IEEE, 2009, pp. 518–521.


## Papers for Classification

* [From Image-level to Pixel-level Labeling with Convolutional Networks](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Pinheiro_From_Image-Level_to_2015_CVPR_paper.pdf)
