# Short overview
This repository contains the jupyter notebook files used to train a potato disease identification model that utilizes ensemble learning that integrates <b>MobileNetV3-Large</b> and <b>EfficientNetV2B3</b> architectures, along with a XAI techniques integration.

# Installation and Setup
It's recommended to use <b>Google Colab</b> for the notebooks, by uploading all the files in drive or directly to the session's storage, and then running the files.

# Notebook Content
1. <b>Preprocess_Code_Doc.ipynb</b> contains data preprocessing functions, starting from data counting, data splitting, to data augmentation.
2. <b>Model_Code_Doc.ipynb</b> contains model training fucntions, starting from importing the pretrained model, to ensemble training using average and concatenation method.
3. <b>Evaluation_Code_Doc.ipynb</b> contains model evaluation functions, starting from predicting the test data with the trained model, plotting the learning curve, generating classification report and confusion matrix, to saving the model.

# Results & Findings
* Achieved 97.91% accuracy on test data
* XAI integration results in the interpretability enhancement through heatmaps and saliency maps
