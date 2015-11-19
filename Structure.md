1. Introduction (Marvin + Martin)
    - Applications
    - Types of classification
        * by result:
            * fixed-class: A set of classes is defined before hand, then
                * binary (street / no street) <---- we write about this type
            * open: any number of objects might be in the image. (only overview)
        * by data:
            * greyscale / colored
            * single image (we write about this) / time series (only mention it)
2. Segmentation Quality Evaluation and Datasets (Marvin + Martin)
    - Quality measures:
        * Accuracy:
            * Normalized Probabilistic Rand (NPR) index
        * Speed
        * Stability:
            * Image choice
            * Parameter choice
    - Datasets:
        * KITTI
        * Berkeley Image segmentation database: D. Martin, C. Fowlkes, D. Tal,
          J. Malik, “A Database of Human Segmented Natural Images and its
          Application to Evaluating Segmentation Algorithms and Measuring
          Ecological Statistics”, Intl Conf on Computer Vision, 2001.
3. Traditional Segmentation Algorithms (Martin)
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
4. Neural Networks for Segmentation (Marvin)
    * Convolutional Networks
5. Typical problems (Marvin+Martin): Only an overview with some nice images
    * Lens blur
    * Smoke
    * occlusions
6. Speed-ups for segmentation (Marvin+Martin)
    (Only an overview, not detailed)
    * Downsampling (reducing the resolution of the image)
    * Superpixels
    * Refinement of coarse segmentations
