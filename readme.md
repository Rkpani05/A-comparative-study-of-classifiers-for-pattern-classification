# A Comparative Study of Classifiers for Pattern Classification

This project aims to compare the performance of four classifiers, namely K-Nearest Neighbors (KNN), Random Forest, Multi-Layer Perceptron (MLP), and Support Vector Machine (SVM), for pattern classification. The project utilizes four different datasets: Iris, Breast Cancer, Digits, and Wine.

## Dataset Selection

The project allows the user to choose one of the following datasets for classification:

- Iris: A dataset containing measurements of iris flowers from three different species.
- Breast Cancer: A dataset containing features of breast cancer tumors, categorized as malignant or benign.
- Digits: A dataset of handwritten digits (0-9) represented as 8x8 images.
- Wine: A dataset with chemical analysis results of wines from three different cultivars.

## Workflow

1. The user is prompted to enter the name of the dataset they want to use for classification.
2. The chosen dataset is loaded using scikit-learn's `load_*` functions.
3. The dataset is divided into training and testing sets using a 80:20 train-test split.
4. Preprocessing steps, such as data normalization or feature selection, can be applied to the data (not implemented in the provided code).
5. Four classifiers (KNN, Random Forest, MLP, and SVM) are trained on the training set.
6. The trained classifiers are evaluated using the testing set.
7. Evaluation metrics, including accuracy, precision, recall, and F1 score, are calculated for each classifier.
8. Comparison bar graphs and confusion matrices are generated to visualize the performance of each classifier.

## How to Run the Code

1. Ensure that you have Python installed on your system.
2. Install the required dependencies by running the following command: `pip install -r requirements.txt`.
3. Run the code by executing the script file: `python classifier_comparison.py`.
4. Follow the on-screen instructions to select the dataset.
5. The code will output the evaluation metrics and generate comparison graphs and confusion matrices.

## Possible Improvements

To further enhance the project, the following improvements can be considered:

- Implement cross-validation to obtain more reliable performance estimates.
- Perform hyperparameter tuning using techniques like grid search for each classifier.
- Utilize scikit-learn's `Pipeline` to streamline the workflow and make the code more modular.
- Explore feature engineering techniques to improve classification performance.
- Consider incorporating ensemble methods to further boost classifier performance.
- Experiment with additional classifiers available in scikit-learn.

## License

This project is licensed under the [MIT License](LICENSE).
