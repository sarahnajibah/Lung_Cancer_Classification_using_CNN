# Lung_Cancer_Classification_using_CNN
Machine learning project for classifying lung cancer into three types - benign, malignant, and normal - using CNN. 
The dataset was obtained from Kaggle's: https://www.kaggle.com/datasets/hamdallak/the-iqothnccd-lung-cancer-dataset. 
In this implementation, I divided the process into five stages: 
- importing libraries
- preprocessing images 
- building the model 
- training the model  
- calculating accuracy

During preprocessing, I applied image normalization, class naming, data separation into test, train, and validation sets, as well as augmentation. 
The model was built with convolution on four layers, gradually increasing the filter size. Then, I trained the model, performed classification, and 
calculated accuracy, achieving a score of 86.45%.
