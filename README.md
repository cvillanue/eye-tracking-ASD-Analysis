
---

# Eye Tracking Data Analysis

## Overview
This project aims to analyze eye tracking data to understand differences in eye movement patterns between individuals with Autism Spectrum Disorder (ASD), Neurotypical individuals, and participants labeled as Unidentified(Pos). The analysis includes preprocessing the data, conducting statistical tests such as ANOVA, and building a machine learning model to classify the participants into different groups based on their eye tracking measurements.

## Data Description
The dataset (”Eye-Tracking Dataset to Support the Research on Autism Spectrum Disorder”), published by Federica Cilia et. al, is distributed over 25 CSV-formatted files. Each file represents the output of an eye-tracking experiment. However, a single experiment usually included multiple participants. The participant ID is clearly provided at each record at the ‘Participant’ column, which can be used to identify the class of participant (i.e., Typically Developing or ASD). Furthermore, a set of metadata files is included. The main metadata file, Participants.csv, is used to describe the key characteristics of participants (e.g. gender, age, CARS). Every participant was also assigned a unique ID.

## Project Structure
- `data/`: Contains the raw and processed data files.
- `notebooks/`: Jupyter notebooks for data preprocessing, analysis, and model building.
- `models/`: Trained machine learning models saved in .h5 format.
- `scripts/`: Python scripts for data preprocessing and model evaluation.
- `README.md`: This file, providing an overview of the project.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eye-tracking-analysis.git
   cd eye-tracking-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks in the `notebooks/` directory to preprocess the data, conduct analysis, and build the model.

4. Use the trained model in the `models/` directory for classification tasks.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tensorflow

## Contributors
- Callyn Villanueva, Christian Oliveto

