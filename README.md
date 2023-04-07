# ZAF056_CV_BlurredImage-detection


### Project Description
There is a dataset of images, par of which is blurred. The task is to develop a machine learning algorithm to detect whether the image is blurred or sharp on the unknown dataset.

### Data Description
The dataset consists of images, and some of them are blurred. The images are blurred using augmentation.

Data files:
- ```train``` - a folder for training
- ```test``` - a folder with images, for which we make predicitons
- ```train.csv``` - labels (answers) to the train sample: **if 1, the image is blurred.**

### Project Methodology

There are two approaches, which can be applied to solving a classification problem for blurred image detection:
- 1) To construct a convolutional neural network, train and test it on unseen given test sample. The quality metric is 'accuracy'; the overfitting problem is to be considered.
- 2) To use  Laplacian or Fourier algorithms to construct the algorithm for interating through the dataset and detecting the blurred images by a advised threshold from the researches (Liu, 2008; Hsu, 2008, Su et al., 2011).

#### Final project output: ***.csv file with predictions for a test (unseen) data for both algorithms.***

### Data
Dataset can be found [here](https://drive.google.com/drive/folders/1CWsLeFXwthxo7n5j6CYZlW_cS9X0oFVP?usp=share_link).

### Papers:
- [Hsu, P., & Chen, B. Y. (2008, January). Blurred image detection and classification. In International conference on multimedia modeling (pp. 277-286). Springer, Berlin, Heidelberg.](https://jiaya.me/all_final_papers/blur_detect_cvpr08.pdf)
- [Su, B., Lu, S., & Tan, C. L. (2011, November). Blurred image region detection and classification. In Proceedings of the 19th ACM international conference on Multimedia (pp. 1397-1400).](https://fled.github.io/paper/blur.pdf)
- [Liu, R., Li, Z., & Jia, J. (2008, June). Image partial blur detection and classification. In 2008 IEEE conference on computer vision and pattern recognition (pp. 1-8). IEEE.](http://graphics.im.ntu.edu.tw/docs/mmm08.pdf)
