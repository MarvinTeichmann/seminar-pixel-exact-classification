## The State of the Art in automatic, fixed class, single-image Segmentation

1. Introduction (Marvin + Martin)
    - Applications
        * Health informatics - NOTE: describe very detailed
        * Robotics
        * Autonomous cars (street / no street, street signs)
    - Types of segmentation
        * by result:
            * fixed-class: A set of classes is defined before hand, then
                * binary (street / no street) <---- NOTE: we write about this type
            * open: any number of objects might be in the image. (only overview)
        * by input data:
            * greyscale / colored
            * single image (NOTE: we write about this) / time series (NOTE: only mention it)
        * by "operation state" (TODO: find better word)
            * completely automatically <-- we write about this type
            * interactive (e.g. user clicks on background or user makes a
              coarse segmentation and automatically refinement)
2. Segmentation Quality Evaluation and Datasets (Marvin + Martin)
    - Quality measures (Martin):
        * Accuracy:
            * Normalized Probabilistic Rand (NPR) index, see
                - http://repository.cmu.edu/cgi/viewcontent.cgi?article=1365&context=robotics
                - http://www.cs.cmu.edu/~hebert/segs.htm
                - M. Emre Celebi, Gerald Schaefer, Hitoshi Iyatomi, William V.
                  Stoecker, Joseph M. Malters, James M. Grichnik, "An Improved
                  Objective Evaluation Measure for Border Detection in
                  Dermoscopy Images", 2010. http://arxiv.org/abs/1009.1020
                - http://people.rit.edu/mij7272/My%20Publications/IEEE%20AIPR2010%20A%20Probabilistic%20Framework%20for%20Unsupervised%20Evaluation%20and%20Ranking%20of%20Image%20Segmentations.pdf
        * Speed
        * Stability:
            * Image choice
            * Parameter choice
    - Datasets (Marvin):
        - Pixel-labels
            * KITTI
            * Berkeley Image segmentation database: D. Martin, C. Fowlkes, D.
              Tal, J. Malik, “A Database of Human Segmented Natural Images and
              its Application to Evaluating Segmentation Algorithms and
              Measuring Ecological Statistics”, Intl Conf on Computer Vision,
              2001.
            * PascalVoc?
        - Image labels
            * ImageNet
3. Traditional Segmentation Algorithms (Martin) --------------------- most work
    * Sliding Window approach + Standard fixed-size classifier
    * SVM
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
4. Neural Networks for Segmentation (Marvin) ------------------------ most work
    * Convolutional Networks
        * Sliding-Window based approaches
        * FCNNs
5. Typical problems (Martin)
    (Only an overview with some nice images)
    * Lens blur
    * Smoke
    * occlusions
6. Speed-ups for segmentation (Marvin)
    (Only an overview, not detailed)
    * Downsampling (reducing the resolution of the image)
    * Superpixels
    * Refinement of coarse segmentations

Bibliography
Glossary
    * SVM
    * CNN
    * FCNN
    * GPU
    * ...
Appendix
    Algorithms, Tables, Figures, ...