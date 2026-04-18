# Animal Classification

This project aims to classify images into 10 animal classes. The model is built using **MobileNetV2** with a **transfer learning** approach to achieve strong classification performance on an animal image dataset.

---

## Project Summary
- The dataset contains **26,179 images**
- The model is built using **TensorFlow** and **Keras**
- The dataset is sourced from Kaggle:  
  https://www.kaggle.com/datasets/alessiocorrado99/animals10/data
- The dataset has **10 class labels**
- The model achieved high accuracy on both training and testing data
- **Data augmentation** is used to increase data variability and help the model become more robust

---

## Class Label Structure
The Animals-10 dataset consists of 10 animal classes:

- `cane` → dog
- `cavallo` → horse
- `elefante` → elephant
- `farfalla` → butterfly
- `gallina` → chicken
- `gatto` → cat
- `mucca` → cow
- `pecora` → sheep
- `scoiattolo` → squirrel
- `ragno` → spider

---

## Model Architecture
The model used is **MobileNetV2** with the **transfer learning** method.  
This approach takes advantage of a pre-trained model that already has initial weights from previous training, making the training process more efficient while still delivering strong performance for image classification tasks.

---

## Evaluation Results
Based on the model evaluation results, the following performance was obtained:

- **Train Accuracy**: 99.14%
- **Test Accuracy**: 96.74%
- **Train Loss**: 0.0306
- **Test Loss**: 0.0988

These results indicate that the model is able to perform classification very well on both training and testing data.

---

## Model Format
The model is saved in the following format:

- **TFJS (TensorFlow.js)**

This format allows the model to be used for web-based deployment with TensorFlow.js.

---

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- TensorFlow.js

---

## Project Objectives
This project was created to:
- apply transfer learning to image classification
- understand the deep learning model training process
- evaluate the performance of a multi-class classification model
- prepare the model for web-based implementation

---

## Conclusion
The animal classification model based on **MobileNetV2** and **transfer learning** is able to deliver excellent performance for classifying animal images into 10 classes. With a testing accuracy of **96.74%**, this model is effective and has strong potential for further implementation in web-based applications using **TensorFlow.js**.
