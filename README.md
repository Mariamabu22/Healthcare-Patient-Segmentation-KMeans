# Healthcare Patient Segmentation Using K-Means Clustering

## About the Project

This project uses machine learning to segment healthcare patients into meaningful groups based on their healthcare behaviors and characteristics.

The analysis was performed on a dataset containing 150,249 patient records. The goal was to identify patient groups with similar patterns in healthcare utilization, clinical complexity, lifestyle, engagement, and hospitalization.

K-Means clustering was used to create patient segments that can support more targeted healthcare strategies, improve patient engagement, support preventive care, and help healthcare organizations allocate resources more effectively.

## My Role

My main contributions to this project included:

- Data cleaning and preprocessing
- Data quality validation
- Feature engineering
- Data standardization
- K-Means clustering
- Elbow Method and Silhouette Score analysis
- PCA visualization
- Cluster interpretation
- Development of healthcare recommendations
- Presentation of analytical findings

## Key Skills & Tools

- [Python & Data Preprocessing](notebooks/) – Data cleaning, validation, and preparation
- [Feature Engineering](notebooks/) – Development of six patient-level features
- [Machine Learning](notebooks/) – K-Means clustering and model evaluation
- [Data Visualization](images/) – Elbow, Silhouette, PCA, and cluster comparison
- [Project Report](report/) – Detailed methodology, results, and recommendations
- [Presentation](presentation/) – Data storytelling and communication of findings

## Project Highlights

- Analyzed 150,249 patient records.
- Engineered six features: Recency, Length of Stay, Healthcare Utilization, Engagement Score, Lifestyle Score, and Clinical Complexity.
- Evaluated different numbers of clusters using the Elbow Method and Silhouette Score.
- Selected K = 4 to create detailed and meaningful patient segments.
- Identified four patient groups: Low Engagement, Healthy, Inactive, and Long Stay patients.
- Used PCA to visualize the patient clusters and evaluate their separation.

## How to Navigate the Repository

- `notebooks/` – Jupyter Notebook containing the Python analysis and machine learning model.
- `data/` – Anonymized or sample healthcare data used for demonstration.
- `report/` – Final project report.
- `presentation/` – Final project presentation.


## Privacy / Client Note

This repository is intended for educational and portfolio purposes. Any healthcare data shared publicly should be anonymized, down-sampled, or replaced with synthetic data. Personally identifiable or confidential patient information is not included.

## Artifacts

This repository includes project artifacts such as:

- Jupyter Notebook with the complete analysis
- Project report
- Project presentation
- Elbow Method visualization
- Silhouette Score visualization
- PCA cluster visualization
- Patient cluster comparison visualization

## Project Outcome

The project demonstrates how K-Means clustering can be used to identify meaningful patient segments and translate analytical results into practical healthcare strategies. The findings can support patient engagement, preventive care, care coordination, and more effective healthcare resource allocation.
