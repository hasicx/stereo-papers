# Stereo Vision and Deep Learning

A collection of papers somewhere near the intersection of stereo vision and deep
learning (DL).

Stereo vision is one of the fundamental problems of computer vision.
Early implementations date back to the 1970s.
Traditional (pre-DL) stereo systems typically compute disparities
    in a series of steps collectively referred to as the **stereo pipeline**.
The following paper provides a survey of traditional stereo methods and an
    introduction to the stereo problem from a computational point of view.

-   **A taxonomy and evaluation of dense two-frame stereo correspondence
    algorithms** (2002)
    _Scharstein, D., and Szeliski, R._
    [[doi]](http://doi.org/10.1023/A:1014573219977)
    [[pdf]](https://vision.middlebury.edu/stereo/taxonomy-IJCV.pdf)

Deep learning has since come to play a pivotal role in computer vision.
The stereo problem is by no means exception.
State-of-the-art algorithms for stereo (2021) are often learning-based and
    typically use neural networks.
The first section, [Surveys](#overviews), lists the most recently published
    review articles, any one of which could serve as a starting point for an
    introduction to the field.
The second (and final) section ([Influential papers](#influential-papers))
    contains publications of specific architectures or techniques with
    importance to the development of the field.


## Overviews

The following four papers are recent overviews of the field.
There is some overlap as they cover the same research area.
The surveys do differ with regard to depth and are not equally technical.
As a whole, they offer a relevant and in-depth overview of the field of
(deep) learning-based stereo vision.

-   **Stereo matching algorithm based on deep learning: A survey** (2020)
    *M. S. Hamid, N. A. Manap, R. A. Hamzah et al.*
    [[doi]](https://doi.org/10.1016/j.jksuci.2020.08.011)

-   **Review of Stereo Matching Algorithms Based on Deep Learning** (2020)
    *K. Zhou, X. Meng, and B. Cheng*
    [[doi]](https://doi.org/10.1155/2020/8562323)

-   **On the Synergies between Machine Learning and Binocular Stereo for Depth
    Estimation from Images: a Survey** (2020)\
    *M. Poggi, F. Tosi, and K. Batsos*
    [[doi]](https://doi.org/10.1109/tpami.2021.3070917)

-   **A Survey on Deep Learning Techniques for Stereo-based Depth Estimation**
    (2020) *H. Laga, L. V. Jospin, F. Boussaid et al.*
    [[doi]](https://doi.org/10.1109/tpami.2020.3032602)


## Influential papers

The first applications of deep learning and deep neural networks (DNNs) to the
    stereo problem emerged around 2015.

This paper is the first to use deep learning to learn a portion of
    the traditional pipeline (i.e. **learning within the pipeline**) while
    treating the remainder manually.
-   **Computing the Stereo Matching Cost with a Convolutional Neural Network**
    (2015) _Jure Žbontar, Yann LeCun_
    [[doi]](http://doi.org/10.1109/CVPR.2015.7298767)
    [[pdf]](https://arxiv.org/pdf/1409.4326)

The papers below pioneered a different approach - **end-to-end learning** -
    where the full pipeline is learned with DL techniques.
-   **FlowNet: Learning Optical Flow with Convolutional Networks** (2015)
    _Dosovitskiy et al._
    [[doi]](http://doi.org/10.1109/ICCV.2015.316)
    [[pdf]](https://arxiv.org/pdf/1504.06852.pdf)
-   **A Large Dataset to Train Convolutional Networks for Disparity, Optical
    Flow, and Scene Flow Estimation** ["the DispNet paper"] (2016)
    _Mayer et al._
    [[doi]](http://doi.org/10.1109/CVPR.2016.438)
    [[pdf]](https://arxiv.org/pdf/1512.02134.pdf)
    [[papers-with-code]](https://paperswithcode.com/paper/a-large-dataset-to-train-convolutional)
-   **End-to-End Learning of Geometry and Context for Deep Stereo Regression**
    (2017) _Kendall et al._ 
    [[doi]](http://doi.org/10.1109/ICCV.2017.17)
    [[pdf]](https://arxiv.org/pdf/1703.04309.pdf)
    [[papers-with-code]](https://paperswithcode.com/paper/end-to-end-learning-of-geometry-and-context)

Finally, some more recent papers with successful models.
-   **Pyramid Stereo Matching Network** (2018) _Jia-Ren Chang, Yong-Sheng Chen_
    [[doi]](http://doi.org/10.1109/CVPR.2018.00567)
    [[pdf]](https://arxiv.org/pdf/1803.08669v1.pdf)
    [[papers-with-code]](https://paperswithcode.com/paper/pyramid-stereo-matching-network)
