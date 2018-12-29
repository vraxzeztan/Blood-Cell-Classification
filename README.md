# Blood Cell Classification

## Dataset

This dataset contains 12,500 augmented images of blood cells (JPEG) with accompanying cell type labels. There are approximately 3,000 images for each of 4 different cell types grouped into 4 different folders (according to cell type). The cell types are Eosinophil, Lymphocyte, Monocyte, and Neutrophil. This dataset is accompanied by an additional dataset containing the original 410 images (pre-augmentation) as well as two additional subtype labels (WBC vs WBC) and also bounding boxes for each cell in each of these 410 images (JPEG + XML metadata). More specifically, the folder 'dataset-master' contains 410 images of blood cells with subtype labels and bounding boxes (JPEG + XML), while the folder 'dataset2-master' contains 2,500 augmented images as well as 4 additional subtype labels (JPEG + CSV). There are approximately 3,000 augmented images for each class of the 4 classes as compared to 88, 33, 21, and 207 images of each in folder 'dataset-master'.

**Link to dataset** : [Kaggle-Blood-Cell-Dataset](https://www.kaggle.com/paultimothymooney/blood-cells)

## Implementation

Implemented CNN model on the dataset

## Score

**Training Accuracy** - 96.9%
**Testing Accuracy** - 75.67%