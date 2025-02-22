📂 Dataset Description

This repository contains a dataset related to telescope observations, structured in CSV format (.csv). It can be used for data analysis, classification, and research in astronomy.

🔭 Dataset Details

1️⃣ Telescope Data Dataset (telescope_data.csv)

File Format: CSV (.csv)Total Records: 19,020Columns:

fLength → Focal length measurement (float)

fWidth → Width of the object (float)

fSize → Size of the object (float)

fConc → Concentration of the object (float)

fConc1 → Secondary concentration (float)

fAsym → Asymmetry of the object (float)

fM3Long → Third moment along the major axis (float)

fM3Trans → Third moment along the transverse axis (float)

fAlpha → Angle of the object (float)

fDist → Distance of the object (float)

class → Classification label (string: g for gamma rays, h for hadrons)

📊 Usage

This dataset can be used for:

Classifying astronomical objects based on their features.

Understanding the characteristics of telescope observations.

Machine learning and deep learning model training for classification tasks.

🤖 Machine Learning Model

The K-Nearest Neighbors (KNN) algorithm was used for classification. KNN is a supervised learning algorithm that classifies data points based on the majority class of their nearest neighbors.

Steps Involved:

Data Preprocessing: Handling missing values and normalizing features.

Splitting the dataset: Training and test sets.

Training the KNN model: Finding the optimal value of k.

Evaluating the model: Using accuracy, confusion matrix, and classification report.


