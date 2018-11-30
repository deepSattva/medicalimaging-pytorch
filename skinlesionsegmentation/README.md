## Prerequisite - 
* Basic understandiong of Image processing operations
* Semantic segmentation understanding (Unet,SegNet)
 
## Problem

[Problem link](https://challenge2018.isic-archive.com/)

Skin cancer is a major public health problem, with over 5,000,000 newly diagnosed cases in the United States every year. Melanoma is the deadliest form of skin cancer, responsible for an overwhelming majority of skin cancer deaths. In 2015, the global incidence of melanoma was estimated to be over 350,000 cases, with almost 60,000 deaths. Although the mortality is significant, when detected early, melanoma survival exceeds 95%.
The goal is to submit automated predictions of lesion segmentation boundaries within dermoscopic images. 


![Lesion](https://challenge2018.isic-archive.com/wp-content/uploads/2018/04/task1.png)


## Approach 
### Data Download
For easy acccess of the data we can use the [ISIC downloader](https://github.com/GalAvineri/ISIC-Archive-Downloader). 
Just follow the instruction set written in the repository to get the data. We have done some exploration on the dataset and tried to solve this problem using 2 approaches

[EDA and Segmentation using opencv](0_SkinLesionSegmentation_EDA_preprocessing.ipynb)
[Model based on SegNet Architecture](1_SkinLesionSegmentation.ipynb)


## Credits and Useful links
A lot of the ideas/code snippets are taken from the following repositories/blog posts. 
* List of submitted abstracts - https://challenge2018.isic-archive.com/leaderboards/ 
* Non dl approach paper - https://arxiv.org/ftp/arxiv/papers/1807/1807.07001.pdf 
* Blog - https://www.linkedin.com/pulse/skin-lesion-segmentation-using-deep-learning-keras-isic-sander 
* Data Augmentation - https://github.com/fabioperez/skin-data-augmentation
