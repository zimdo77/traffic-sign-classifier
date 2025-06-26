# Traffic Sign Classifier
- This project focuses on classifying traffic sign images using machine learning techniques; models used:
    - Random Forest (RF)
    - Support Vector Machine (SVM)
    - Convolutional Neural Network (CNN)
- Feature extraction, feature selection, standardization, and model training pipelines were implemented.
- Computer vision techniques (e.g., OpenCV and scikit-image) were used for feature extraction and preprocessing.
- Report attached (`report.pdf`) along with code to support (`traffic-sign-classifier.ipynb`).
- Libraries used: pandas, numpy, seaborn, matplotlib, OpenCV, scikit-learn, scikit-image, tensorflow (keras).
- Kaggle competition: https://www.kaggle.com/competitions/traffic-sign-prediction/

## Enivronment
- Python version 3.11.0
- All required dependencies are listed in `requirements.txt`

## Data files
- Traffic sign images are a subset of the [German Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign):
    - 5488 training images with class labels
    - 2353 test images without labels
    - 43 total traffic sign classes
- All train/test data is located in the `data/` directory.
- Directory structure:
    - `data/`
        - `train/`
            - training images
            - `train_metadata.csv`: metadata for training images (ids, image filenames and class labels)
        - `test/`
            - test images
            - `test_metadata.csv`: metadata for test images (ids, image filenames only, no labels)


## Running code
All models and their full pipelines can be executed by running `traffic-sign-classifier.ipynb` from top to bottom.
This notebook:
- Performs feature extraction and selection.
- Trains models.
- Evaluates models (with visualisations).
- Outputs csv files for Kaggle submission.

## Kaggle submission format
Final submission CSV should follow this structure:q

Id,ClassId  
67.jpg,4  
94,2  
...  
521.jpg,12