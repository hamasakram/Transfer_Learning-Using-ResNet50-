# Transfer Learning with ResNet50

## Project Overview
This project demonstrates the application of transfer learning using the ResNet50 architecture to classify images of flowers. The model is trained on a dataset of five different flower types, leveraging pre-trained weights from ImageNet to enhance feature extraction.

## Dataset
The dataset comprises images of five flower species and is sourced from Kaggle:
- **Dataset URL**: [Kaggle - 5 Flower Types Classification](https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset)
- **License**: Other

## Requirements
- Python 3.x
- TensorFlow 2.x
- Keras
- Matplotlib
- PIL

Model Architecture
The model uses the ResNet50 architecture with the following modifications:

The top layer is replaced with a Dense layer for classification.
The pre-trained layers are frozen during the initial training phase.
Training and Validation
The model is trained on 80% of the dataset with data augmentation techniques applied to reduce overfitting. The remaining 20% serves as the validation set.

Results
Training accuracy and validation accuracy graphs are included in the notebook to demonstrate the effectiveness of the model.

Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your suggested changes.

## Installation
Clone the repository and install the required Python libraries:
```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
pip install -r requirements.txt



