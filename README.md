K-Nearest Neighbors (KNN) Classification with 10-Fold Cross-Validation
**Introduction**
This project implements a simple and effective K-Nearest Neighbors (KNN) classification algorithm from scratch, using only basic Python libraries (csv, random, and math). The model performance is evaluated using 10-Fold Cross-Validation on different datasets.
Objectives
- Load datasets from CSV files.
- Split datasets into K-Folds.
- Manually compute Euclidean distances.
- Find K nearest neighbors for prediction.
- Perform classification.
- Evaluate performance with 10-Fold Cross-Validation.
- Report the mean accuracy for each dataset.
**Requirements**
Python 3.x
No external libraries required (only csv, random, math).
**Datasets**
- hayes.csv – Hayes-Roth dataset.
- car.csv – Car Evaluation dataset.
- cancer.csv – Breast Cancer dataset.

**Note**: The last column in each dataset must contain the class labels.
Execution Steps
1. Place the dataset files (hayes.csv, car.csv, cancer.csv) in the same directory as the Python script.
2. Run the Python script using the command:
   python knn_cross_validation.py
3. The script will print the mean accuracy for each dataset after performing 10-Fold Cross-Validation.
**Output Example
****RESULTS**:

hayes roth          -> 47.00%
car evaluation      -> 85.00%
breast cancer       -> 73.00%

**Folder Structure
**/KNN_10Fold_CV
    |-- knn_cross_validation.py
    |-- hayes.csv
    |-- car.csv
    |-- cancer.csv
    |-- README.docx / README.pdf
**Conclusion**
This project demonstrates how a basic KNN algorithm can be built from scratch without using machine learning libraries. Using 10-Fold Cross-Validation ensures a more reliable and unbiased estimate of model performance across different datasets.

