# CNN-for-Bird-s-Eye-Human-Detection
The most common application of computer vision is in autonomous vehicles. Its usage outside of this, especially in aerial tehcnology, is limited. This project aims to use deep learning to perform image detection from an aeiral perspective. Specifically, it aims to help identify humans in hazardous scenarios, such as in the presence of smoke and fire. This requires further refinement of the model than a typical human recognition algorithm, and can have applications in search and rescue situations if drones or aircrafts are being used. 

Three datasets were used (the datasets were filtered for relevant images): 
1. https://www.kaggle.com/datasets/constantinwerner/human-detection-dataset
2. https://www.kaggle.com/datasets/sanikamal/horses-or-humans-dataset
3. https://www.kaggle.com/datasets/arnaud58/landscape-pictures
4. https://www.kaggle.com/datasets/phylake1337/fire-dataset

These datasets were combined appropriately to provide comprehensive training/validation/test sets. 

Models such as VGG16, ResNet50, and many custom CNN architectures were tested. 

The notebooks should be observed in the following order: 
1. Imports
2. FIRE Dataset
3. Dataframe 1 Initialization
4. Dataframe 2 Initialization
5. Dataframe 3 Initialization
6. Image Augmentation
7. Image Augmentation - Dataframe 2
8. Expanded Dataset Construction
9. Models
10. Graphs/Results


