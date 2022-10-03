# CelebAHQ-Gender
CelebAHQ with annotations on genders (male or female)
## Description
Unlike the CelebA dataset, the CelebA**HQ** dataset consists of 30,000 high-resolution and high-quality images.  
However, there are no available annotations like gender, facial expression, or age.  

Thus I trained classifiers (ResNet152 and EfficientNet_B0) to distinguish male and female.  
The trained classifiers were applied to classify the CelebAHQ dataset.  

Nevertheless, the initial results did not seem to distinguish well.  
So, I manually inspected the entire dataset.  

You can access the dataset [here](https://drive.google.com/drive/folders/1GyES0r7MhdP3fpVKyoofnkMt3_leaShG?usp=sharing).  

The number of images per classes:  
Female: 19,057  
Male: 10,943

If you find incorrectly classified samples, please report them to me.

## Acknowledgement
Original dataset: [CelebAHQ](https://github.com/tkarras/progressive_growing_of_gans).  
Resized dataset: [CelebAHQ-256x256](https://www.kaggle.com/datasets/badasstechie/celebahq-resized-256x256).  
