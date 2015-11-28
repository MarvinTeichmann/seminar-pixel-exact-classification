## The State of the Art in automatic, fixed class, single-image Segmentation

### 1. Introduction (Marvin + Martin)

### 2. Segmentation Quality Evaluation and Datasets (Marvin + Martin)

#### Quality measures (Martin)

#### Datasets (Marvin)
- Pixel-labels
    * KITTI
    * Berkeley Image segmentation database: D. Martin, C. Fowlkes, D.
      Tal, J. Malik, “A Database of Human Segmented Natural Images and
      its Application to Evaluating Segmentation Algorithms and
      Measuring Ecological Statistics”, Intl Conf on Computer Vision,
      2001.
    * PascalVoc?
    * Berkeley Segmentation dataset
    * A Database of Human Segmented Natural Images and its Application to
      Evaluating Segmentation Algorithms and Measuring Ecological Statistics
      - http://www.ics.uci.edu/~fowlkes/papers/mftm-iccv01.pdf
- Image labels
    * ImageNet

### 3. Traditional Segmentation Algorithms (Martin) --------------------- most work
* Sliding Window approach + Standard fixed-size classifier
* SVM
* Mean shift segmentation
    * http://stackoverflow.com/q/4831813/562769
    * https://en.wikipedia.org/wiki/Mean_shift
* mean shift based fuzzy c-means
* Reine Klassifikation
    * Sliding Window vs Deconvolution
    * SVM, Neuronale Netze
    * Regression vs Klassifikation


### 4. Neural Networks for Segmentation (Marvin) ------------------------ most work
* Convolutional Networks
    * Sliding-Window based approaches
    * FCNNs

### 5. Typical problems (Martin)

### 6. Speed-ups for segmentation (Marvin)
(Only an overview, not detailed)
* Downsampling (reducing the resolution of the image)
* Superpixels
* Refinement of coarse segmentations

### Bibliography

### Glossary
* SVM
* CNN
* FCNN
* GPU
* ...

### Appendix
    Algorithms, Tables, Figures, ...