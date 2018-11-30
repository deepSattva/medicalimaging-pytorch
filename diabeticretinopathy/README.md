## Prerequisite - 
* One of the good beginner problem to start with in semantic segmentation space/image procesing space
* Since data is 2D and competition is a bit older we can get lots of references to kickstart
 
## Problem

[Kaggle Link](https://www.kaggle.com/c/diabetic-retinopathy-detection)

Diabetic retinopathy is the leading cause of blindness in the working-age population of the developed world. 
It is estimated to affect over 93 million people.

![DR](https://storage.googleapis.com/kaggle-competitions/kaggle/4104/media/retina.jpg)


## Approach 
As our first problem while learning basic image processing, we have tired to identify the factors that cause DR from the images. 
As a next step the project can be extended to build a classification model to predict whether person has DR or not

[EDA and Feature generation](EDA_Preprocessing_v1.ipynb)


## Credits and Useful links
* A lot of the ideas/code snippets are taken from the following repositories/blog posts. 
* Useful Techniques (hist normalization) - http://cs231n.stanford.edu/reports/2017/posters/524.pdf 
* First place solution - https://github.com/btgraham/SparseConvNet/tree/kaggle_Diabetic_Retinopathy_competition 
* PDF paper specifying details of implementation and code - https://kaggle2.blob.core.windows.net/forum-message-attachments/88655/2795/competitionreport.pdf 
* Solving DR with opencv only - https://pdfs.semanticscholar.org/011f/f9edb213dbe82eae00c8dadae60c34788a94.pdf 
* Blodvessel segmentation & other good feature extraction (one of the best)  - https://github.com/getsanjeev/retina-features#bloodvessel-segmentation 
* Good Github link - http://jeffreydf.github.io/diabetic-retinopathy-detection/ 
* IIT paper project (basic and easy explanation) https://cse.iitk.ac.in/users/cs365/2015/_submissions/mohitss/report.pdf 
* Paper IOVS journal CNN (Retinal Lesion detection) - http://iovs.arvojournals.org/article.aspx?articleid=2670996 
* Domain link explaining DR - http://www.glycosmedia.com/education/diabetic-retinopathy/diabetic-retinopathy-features-of-diabetes-intraretinal-haemorrhages/ 
* Domain link explaining what are exudates - https://www.researchgate.net/post/Are_there_relationships_between_soft_exudates_hard_exudates_and_cotton_wool_spots_in_retinopathy2 
* DR with Pytorch (VGG16 and Inception) - https://github.com/snehabhattacharya/diabetic_retinopathy
