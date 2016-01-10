## Data sets

* D Martin, C Fowlkes, D Tal, J Malik: A database of human segmented natural
  images and its application to evaluating segmentation algorithms and
  measuring ecological statistics.

### Berkeley Segmentation Dataset and Benchmark
> Our dataset for this evaluation is the Berkeley Segmentation Database [5],
> whichcontains 300 natural images with multiple ground truth hand
> segmentations of each image.
>
> [5] D. Martin, C. Fowlkes, D. Tal, J. Malik, “A Database of Human Segmented
> Natural Images and its Application to Evaluating Segmentation Algorithms and
> Measuring Ecological Statistics”, Intl Conf on Computer Vision, 2001.

* http://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/

@InProceedings{MartinFTM01,
  author = {D. Martin and C. Fowlkes and D. Tal and J. Malik},
  title = {A Database of Human Segmented Natural Images and its
           Application to Evaluating Segmentation Algorithms and
           Measuring Ecological Statistics},
  booktitle = {Proc. 8th Int'l Conf. Computer Vision},
  year = {2001},
  month = {July},
  volume = {2},
  pages = {416--423}
}

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


### LabelMe

B. C. Russell, A. Torralba, K. P. Murphy, and W. T. Freeman. La-
belMe: A database and web-based tool for image annotation. IJCV,
77(1-3):157–173, 2008

#### LabelMe Outdoor (LMO) dataset

> * "subset of LabelMe" (see )
> * "2,488 training images, 200 test images, and 33 labels"
> * "ground truth in the form of overlapping object polygons"

Source: Scene parsing with object instances and occlusion ordering

* C. Liu, J. Yuen, and A. Torralba. Nonparametric scene parsing via label
  transfer. PAMI, 33(12):2368–2382, 2011. http://people.csail.mit.edu/celiu/pdfs/LabelTransferTPAMI.pdf


### SUN

"offshot of LabelMe"

J. Xiao, J. Hays, K. A. Ehinger, A. Oliva, and A. Torralba. Sun
database: Large-scale scene recognition from abbey to zoo. In
CVPR, 2010. 5


### Corel database
* For comparison with previous work we have also used the 7-class Corel data-
  base subset (where images are 180×120 pixels) and the 7-class Sowerby
  database (96 × 64 pixels) used in [1]. For those two databases the numbers of
  images in the training and test sets are exactly as for [1].
* Source: "Textonboost: Joint appearance, shape and context modeling for
  multi-class object recognition and segmentation"


### Sowerby database

* He et al [1]: "He, X., Zemel, R.S., Carreira-Perpiñán, M.A.: Multiscale
  conditional random fields for image labeling. Proc. of IEEE CVPR (2004)"


### Weitere

* http://rodrigob.github.io/are_we_there_yet/build/
* http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm
* http://www.via.cornell.edu/databases/


## Papers for Classification

* [Instance-aware Semantic Segmentation via Multi-task Network Cascades](http://arxiv.org/pdf/1512.04412.pdf) !!!!!!!!!!!!!
* Kohonen map? Pulse-coupled networks?
* [From Image-level to Pixel-level Labeling with Convolutional Networks](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Pinheiro_From_Image-Level_to_2015_CVPR_paper.pdf)
* Object detection via a multi-region & semantic segmentation-aware CNN model
* http://arxiv.org/abs/1511.02680 - Bayesian SegNet: Model Uncertainty in Deep
  Convolutional Encoder-Decoder Architectures for Scene Understanding
* Dan Ciresan, Alessandro Giusti, Luca M Gambardella, and Jurgen Schmidhuber.
  Deep Neural Networks ¨ Segment Neuronal Membranes in Electron Microscopy
  Images. In NIPS, 2012.
* Liang-Chieh Chen, George Papandreou, Iasonas Kokkinos, Kevin Murphy, and Alan
  L Yuille. Semantic Image Segmentation with Deep Convolutional Nets and Fully
  Connected CRFs. In ICLR, 2015.
* Mahinda Pathegama & Ö Göl (2004): "Edge-end pixel extraction for edge-based
  image segmentation", Transactions on Engineering, Computing and Technology,
  vol. 2, pp 213–216, ISSN 1305-5313
* [Can Pretrained Neural Networks Detect Anatomy?](http://arxiv.org/pdf/1512.05986.pdf)

## Techniques for speedups

### Stride

* Applied in "Textonboost: Joint appearance, shape and context modeling for
  multi-class object recognition and segmentation"

### Refinement

* Region refinement as in "Textonboost: Joint appearance, shape and context
  modeling for multi-class object recognition and segmentation"
* "Object Detection Combining Recognition and Segmentation"

### Papers

* An Efficient Approach to Semantic Segmentation
* [Instance-aware Semantic Segmentation via Multi-task Network Cascades](http://arxiv.org/pdf/1512.04412.pdf)


## Both of us

* [Relating Cascaded Random Forests to Deep Convolutional Neural Networks for Semantic Segmentation](http://arxiv.org/pdf/1507.07583v1.pdf)
* Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet,
  Zhizhong Su, Dalong Du, Chang Huang, and Philip H S Torr. Conditional Random
  Fields as Recurrent Neural Networks. arXiv.org, 2015.