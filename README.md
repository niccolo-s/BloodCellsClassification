# Convolutional Neural Network for Blood Cells Classification
This project was developed during a two-week Coding Challenge as part of the evaluation for the _Artificial Neural Networks and Deep Learning_ course at Politecnico di Milano, A.Y. 2024-2025.
The programming language used is Python, specifically employing the TensorFlow/Keras library.

# Files description
- [CNN_for_Blood_Cells_Classification.pdf](https://github.com/niccolo-s/BloodCellsClassification/blob/main/CNN_for_Blood_Cells_Classification.pdf): this is the project report. Please read it to fully understand how the models were built.
- [DataAugmentation.ipynb](https://github.com/niccolo-s/BloodCellsClassification/blob/main/DataAugmentation.ipynb) contains the code used to perform data augmentation on the raw training set.
- [EfficientNetB6_Tuned.ipynb](https://github.com/niccolo-s/BloodCellsClassification/blob/main/EfficientNetB6_Tuned.ipynb), [ResNet152_Tuned.ipynb](https://github.com/niccolo-s/BloodCellsClassification/blob/main/ResNet152_Tuned.ipynb), [ResNet50_Tuned.ipynb](https://github.com/niccolo-s/BloodCellsClassification/blob/main/ResNet50_Tuned.ipynb) are the notebooks that contain the code for building, training and testing the models. Here you can also find the specific performance metrics for each model.

# Final results 
The final model was an ensemble of the three models listed above, achieving an accuracy of 91.7% on a highly corrupted test set used for the evaluation.

# Authors
- Agnese Negroni
- Alberto Pola
- Fabio Romagnoli
- Niccolò Signorelli

# Grade
This project received the highest grade possible (5.5 out of 5.5).
