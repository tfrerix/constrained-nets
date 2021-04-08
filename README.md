Homogeneous Linear Inequality Constraints for Neural Network Activations
================
This repository contains a Python implementation of the algorithm presented in our paper:

[**Homogeneous Linear Inequality Constraints for Neural Network Activations**](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w45/Frerix_Homogeneous_Linear_Inequality_Constraints_for_Neural_Network_Activations_CVPRW_2020_paper.pdf)<br>
Thomas Frerix, Matthias Nießner, Daniel Cremers<br>
CVPR 2020 Deep Vision Workshop


Installation
-------------------
1. Make sure you have a running Python 3 (tested with Python 3.7) ecosytem, e.g., through conda, and an Nvidia GPU (tested with CUDA 10.1  on a Titan X)
2. Install pytorch, e.g., `conda install pytorch torchvision cudatoolkit=10.1 -c pytorch`
3. Install the other dependencies via `pip install -r requirements.txt`

Example
-------------------
Execute the file `example.sh` to make a sample run of our algorithm. 
In this toy experiment, the algorithm learns an orthogonal projection onto a checkerboard constraint.
The `results` directory will contain MNIST test set samples and the output of the trained model.

Paper Reference
-------------------
```
@InProceedings{Frerix2020,
    author = {Frerix, Thomas and Nie{\ss}ner, Matthias and Cremers, Daniel},
    title = {Homogeneous Linear Inequality Constraints for Neural Network Activations},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    year = {2020}
}
```
