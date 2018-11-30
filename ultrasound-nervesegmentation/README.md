## Prerequisite - 
* One of the good beginner problem to start with in semantic segmentation space
* Good knowledge of PyTorch/Any other deep learning framework
* UNet architecture
 
## Problem

[Kaggle Link](https://www.kaggle.com/c/ultrasound-nerve-segmentation)

Pain management in Patients is typically done through the administration of narcotics, which has lot of side affects. On the other hand introducing pain management catheters, that block or mitigate the pain at source, reduce dependency on the narcotics and speed up the recovery process. We will discuss the problem of identifying nerve structures in the region around neck so that the indwelling catheters are rightly placed and provide a pain free future.The goal of the competition was to label the area containing a collection of nerves called the Brachial plexus in ultrasound images.

![BPNerve](https://manikantareddyd.github.io/assets/posts/2016-11-16-ultrasound-nerve-segmentation/Brachial_Plexus.jpg)


## Approach 
This repo contains 2 notebooks

1. [Notebook containing the EDA & data preprocessing part](https://github.com/MohitTare/deepimpact_medicalimaging-ultrasoundnerveseg/blob/master/0_EDA%20and%20Data%20Preprocessing.ipynb)
2. [Notebook containing starter version of model](https://github.com/MohitTare/deepimpact_medicalimaging-ultrasoundnerveseg/blob/master/1_Ultrasound_Nerve_segmentation.ipynb)

## Credits and Useful links
A lot of the ideas/code snippets are taken from the following repositories/blog posts. 
* https://towardsdatascience.com/medical-image-segmentation-part-1-unet-convolutional-networks-with-interactive-code-70f0f17f46c6 
* https://github.com/jakeoung/Unet_pytorch/ 
* https://github.com/prateekmalhotra/ultrasound-nerve-segmentation/blob/master/Ultrasound.ipynb 
* https://github.com/jocicmarko/ultrasound-nerve-segmentation 
* https://mc.ai/segmentation-of-brachial-plexus-from-ultrasound-images-using-u-net-architecture-in-keras/ 
* https://raghakot.github.io/2016/12/26/Ultrasound-nerve-segmentation-challenge-on-Kaggle.html 
* http://fhtagn.net/prog/2016/08/19/kaggle-uns.html 
* http://cs229.stanford.edu/proj2016/poster/LiSegmentationOfUltrasoundImagesUsingConvolutionalNeuralNetworksWithNoisyActivationFunctions-poster.pdf 
* https://manikantareddyd.github.io/blog/ultrasound-nerve-segmentation/ 
* http://asymptoticlabs.com/blog/posts/BP_detection_retrospective.html 

