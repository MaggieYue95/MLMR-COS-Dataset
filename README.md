# MLMR-COS Dataset: A New Public Dataset Characterized by Simple Background

Abstract
We established a new co-segmentation dataset (MLMR-COS), which contains 889 image groups with 18 images/group and pixel-wise hand-annotated ground truth. The dataset is characterized by simple background produced from a single color, while we embed four difficult cases into it: ECFB(easy confused foreground and background), TR(transparent regions in objects), MH(minor holes in objects), and SD(shadows).

Introduction
Over the last decades, a lot of co-segmentation algorithms have been proposed. A comprehensive evaluation of these algorithms can provide an understanding of the state-of-the-art and help to reveal the weakness the existed algorithms. For this purpose, evaluation datasets are needed. The commonly used datasets for evaluating co-segmentation algorithms include iCoseg, MSRC, Internet, and FilckerMFC. The image backgrounds in these datasets are all complicated, which vary in color or intensity. The exact co-segmentation over these images with complicated background is difficult to be obtained for current algorithms. Thus, we establish a dataset of images with simple background. It seems easier to obtain a good result on our dataset, however, we embed four difficult cases described above into the dataset, which makes it challenging. We believe that it is more feasible to firstly solve these problems on simple background and then extend the solutions to the images with complex background.

Dataset Description
The MLMR-COS dataset includs 889 groups of images and each group consists of 18 images with common object, leading to 16002 images in total. According to different difficult attributes, we divide the whole dataset into five subsets: with ECFB, TR, MH, SD, and Normal(normal data). The five subsets contain 193, 251, 82, 83 and 280 image groups, respectively. Each original image is in JPG format with pixel size of 360 *360, and each groud truth image is in PNG format.

Rules
The MLMR-COS dataset is established for the development of co-segmentation. We do not want to create any obstacles for publishing methods that use this dataset. At the same time, we ask the people who download or use the MLMR-COS to abide the rules below:
1) Data downloaded from this site may only be used for the purpose of scientific studies, for example, may be used to train or develop new algorithms for scientific studies. All the data from MLMR-COS cannot be used to train or develop algorithms used in commercial products.
2)    When the data and/or the results of algorithms on the data are used in scientific publications (journal publications, conference papers, technical reports, presentations at conferences and meetings) you must state the data sources.
3) Teams must notify the maintainers of this site about any publication that is (partly) based on the data on this site, in order for us to maintain a list of publications associated with the MLMR-COS dataset.

Download
You can download MLMR-COS dataset from this link: $\color{red}{https:baidu.com}$
Notice that you are not allowed to download these data if you do not agree with the above rules.

Contact
If you are not yet clear about the dataset, or if you have additional questions, please e-mail Mengqiao Yu (yumengqiao@bit.edu.cn).
Address: Machine Learning and Muti-Media Retrieval Lab, Beijing Institute of Technology, Beijing 100081, China.
