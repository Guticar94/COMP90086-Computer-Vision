# COMP90086-Computer-Vision
## Physical Reasoning Challenge
This project aims to predict the stability of stacked objects by analyzing images from ShapeStack dataset. It evaluates several deep learning architectures such as Custom CNN, EfficientNet, InceptionV3, InceptionV4, and Inception-ResNetV2. The models are compared based on their performance and computational efficiency.

### Prerequisites

- Operating System: Windows, macOS, or Linux
- Python Version: 3.12 or higher
- Conda: Install from [Anaconda](https://www.anaconda.com/).
- Jupyter Notebook: Included with Anaconda or install separately.


### How to run
1. Setup environment
  ```
  conda env create -f environment.yml
  conda activate envsml
  ```
2. Open up Jupyter Notebook:
  * Please run the below command to start Jupyter Notebook:
    ```
    Jupyter notebook
    ```
3. Notebook Execution for training, validating, and testing model:
   
  * Open ```combineModels.ipynb``` to train, validate, and generate predictions files for Kaggle submission.
    
4. Notebook Execution for visualising results:
   
  * Use ```visualiseResult.ipynb``` to visualize the model performance based on the generated CSV files.

### File Description

```
├── README.md                            # Project overview and instructions
├── combineModels.ipynb                  # Notebook for combining model outputs and predictions
├── visualiseResult.ipynb                # Notebook for visualizing model performance
├── training_results/                    # Training results for each model
│   ├── CNN_history.csv                  
│   ├── EfficientNet_history.csv         
│   ├── Inception_v3_history.csv         
│   ├── inception_v4_ImageNet_history.csv
│   ├── inception_v4_Resnet_v2_history.csv
├── predictions/                         # Predictions from each model
│   ├── predictions_CNN.csv              
│   ├── predictions_EfficientNet.csv     
│   ├── predictions_Inception_v3.csv     
│   ├── predictions_Inception_v4_ImageNet.csv
│   ├── predictions_Inception_v4_Resnet_v2.csv
└── requirements.txt                     # Dependencies list


```
    
  
