# Steel Plate Defect Prediction

![Steel Plate]![header](https://github.com/SaYanZz0/Kaggle-Competition---Steel-Plate-Defect-Prediction/assets/88038655/45c7ab4b-fa56-45d9-b2e7-3dcd0e9014f3)


Welcome to the Steel Plate Defect Prediction project repository! This project is based on the Kaggle competition where submissions are evaluated using the area under the ROC curve (AUC) using the predicted probabilities and the ground truth targets.

## Objective
The objective of this project is to predict the probability of various defect categories in steel plates. The dataset contains 7 binary targets: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, and Other_Faults. The final score is calculated by averaging the AUC of each predicted column.

## Dataset
The dataset for this competition consists of two main files:
- `train.csv`: the training dataset
- `test.csv`: the test dataset

Additionally, there is a `sample_submission.csv` file provided in the correct format for submissions.

## Evaluation Metric
Submissions are evaluated based on the AUC for each of the 7 defect categories. The final score is the average of the individual AUC of each predicted column.

## Data Source
The dataset used in this competition (both train and test) was generated from a deep learning model trained on the Steel Plates Faults dataset from UCI. While the feature distributions are close to the original dataset, they are not exactly the same. Participants are encouraged to explore differences and assess whether incorporating the original dataset in training improves model performance.


Feel free to reach out me  if you have any questions or suggestions! Happy coding! 🚀
