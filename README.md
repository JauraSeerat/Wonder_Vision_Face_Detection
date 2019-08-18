# Project : Face Detection


  ## Study Group : #sg_wonder_vision
     This is the repository for group project of #sg_wonder_vision Face Detection team
     in Secure and Private AI Scholarship Challenge from Facebook | Udacity.
     In this project, one-shot learning with Siamese Network is implemented using PyTorch.


## Getting Started

This project use Siamese network which is a special type of neural network and it is one of simplest and most popularly used one-shot algorithm. We create the Siamese network by building face recognition model. The objective of  this network is to understand whether two faces are similar or disimilar.  

**Project Dataset**
- For this project, we use the AT&T Database of Faces, which can be downloaded from [here](https://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html). Once you have downloaded and extracted the archieve, it will show s1-s40 folders and each having 10 different images per person.
You can use any dataset. Each class must be in its own folder.


### Dependencies

This require PyTorch v0.4 or newer, and torchvision. The easiest way to install PyTorch and torchvision locally is by following the instructions on the [PyTorch site](https://pytorch.org/get-started/locally/). You'll also need to install numpy and jupyter notebooks, the newest versions of these should work fine.Using the conda package manager is generally best for this,
```
conda install numpy jupyter notebook
```
If you haven't used conda before, please [read the documentation](https://conda.io/en/latest/) to learn how to create environments and install packages. 

*If you don't want to download these dependencies locally*, you can follow up alternative [Google Colab](https://colab.research.google.com/)

## Demonstration of face detection project
-You tube link needs to be included here


## Tutorial:

###### What is Siamese Network?
Siamese Network is a special type of neural network and it is one of the popularly used one-shot learning algorithms. One-shot learning is a technique where model learn from one training example per class.
![siamese network](https://github.com/JauraSeerat/Wonder_Vision_Face_Detection/blob/master/Siamese%20network.jpg)

###### Why we use Siamese Network?
Since our team is  working on face recognition project so we think of broader perspective while selecting model. We want to work on such a model which can be used in a big organization. Let's say an organization have 500 people for training network. If we build this using CNN, then we need many images of all 500 people for training. But apparently, we don't have so many images, so it is best to use one-shot learning algorithm such as Siamese network which can learn from fewer data points.

To learn more about Siamese Network that how does it work, follow up this [tutorial](https://medium.com/swlh/advance-ai-face-recognition-using-siamese-networks-219ee1a85cd5)


## Future Plans
We built an application(which detect if two persons are similar or disimilar and how much disimilarity they have) using siamese network. Our next step is to deploy this model. We will deploy our application in coming days.


##  Contributors:
- Abhishek Tandon (@Abhishek Tandon )
- Alejandro Galindo (@Alejandro Galindo )
- Seeratpal K. Jaura  (@Seeratpal K. Jaura) 
- Sourav Das (@Sourav) 
- Agata Gruza (@Agata [OR, USA])
- Rupesh Purum (@Rupesh Purum )
- Joyce Obi (@Joyce Obi)

## References
- [Face recognition using Siamese Network](https://medium.com/swlh/advance-ai-face-recognition-using-siamese-networks-219ee1a85cd5)- Suggested by @Abhishek Tandon
- [OpenCV Face Recognition](https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/) - Suggested by @Agata [OR, USA] 
- [Face detection using OpenCV and Python: A beginner's guide](https://www.superdatascience.com/blogs/opencv-face-detection) Suggested by @Seeratpal K. Jaura
- [Face recognition with OpenCV, Python, and deep learning](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/) - Suggested by @Agata [OR, USA] 
- [Siamese Network](https://innovationincubator.com/siamese-neural-network-with-pytorch-code-example/) - Suggested by @Alejandro Galindo


## [Meetups Updates](https://docs.google.com/document/d/1bwPe_K4xh2Awk_72c1o9JmxKXtl661ko203j7e2_VpM/edit?usp=sharing)

