CompVisProject
==============

*Automate Image Analysis*


This is a computer vision project, which aims to build a classifier to distinguish between control and drug treated samples. Data comes from automated image processing pipeline, which corrects, normalizes and segments collected images to automatically detect and describe structures of interest with 200-1000+ attributes. To date, the dataset holds quantification data from 30 000+ images of both control and experimentally treated samples. The project will involve loading both images and corresponding quantification data into one database and testing various supervised learning algorithms for accurate binary classification. Unsupervised approaches will also be used to gain additional insights as to which features might more strongly contribute to the formation of two clusters and/or to find additional structure in the data. If successful, the project can be built upon by using existing image datasets from molecular treatments affecting other molecular pathways and incorporating established hierarchical ontologies to both name the classes and maintain known links between them. All in all, the project aims to lay a groundwork for applying data science methods for biomedical data to accelerate drug discovery. 


**Techniques** to evaluate:

Perceptron, Neural Networks, SVM with Gaussian kernel.

In the case of neural networks, both above mentioned features and actual images will be used for training.

**Data:**

1.
2.

1. Set of CSV files from automated image processing pipeline: several indepenedently acquired data sets. Approximately 30 0000 examples in total. Structures of interest with 200-1000+ features.

2. Actual images: still need to have dimensions reduced. Requires some changes in the pipeline.
                                                                                                                                                                                

