### DREAMT: Dataset for Real-time Sleep Stage Estimation Using Multisensor Wearable Technology

The project pipeline consists of the following key steps:

- Extracting and organizing raw data
- Preprocessing and feature engineering
- Training and evaluating classification models

### Detailed Description

- dataset_sample: Contains sample data for each participant, including feature-engineered data, participant information, and subsampled raw signal data.

- features_df: A folder with files for feature-engineered data.

- sid_domain_features_df.csv: A CSV file with features calculated from raw Empatica E4 data recorded during data collection.

- participant_info.csv: A CSV file with participant's basic information.

- cpap_analysis.py: A module that processes data to extract breathing information for each participant. The results are output as a JSON file, named with the participant's number.

- quality_score_per_subject.csv: A file that summarizes the percentage of artifacts in each subject's data, based on the sid_domain_features_df.csv.

- read_raw_e4.py: A module that reads raw Empatica E4 data, sleep stage labels, and reports, creating a dataframe that aligns the data with sleep stages and metrics like the Apnea-Hypopnea Index.

- feature_engineering.py: A module that processes data from `read_raw_e4.py` and performs feature engineering. The result is stored in the feature_df file.

- datasets.py: A module that loads, cleans, and resamples the feature-engineered data, then splits it into training, testing, and validation sets.

- models.py: A module that builds, trains, and tests the model using the training, testing, and validation datasets. It provides performance metrics and confusion matrix results.

- main.py: A script that runs the entire pipeline, including data loading, cleaning, splitting, model building, training, testing, and evaluation.

- utils.py: A script containing helper functions for data loading, cleaning, splitting, model building, training, testing, and evaluation.
