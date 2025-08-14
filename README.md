# Titanic Data Science Project

## Overview
This project aims to analyze the Titanic dataset to predict the survival of passengers based on various features. The dataset includes information such as passenger demographics, ticket details, and cabin information. The project involves data exploration, preprocessing, model building, and evaluation.

## Project Structure
- **data/**: Contains the training and test datasets.
  - `train.csv`: The training dataset used for model training.
  - `test.csv`: The test dataset used for making predictions.
  
- **notebooks/**: Contains Jupyter notebooks for analysis and model building.
  - `TitanicNoteBook.ipynb`: The main notebook for data exploration and model evaluation.
  
- **submissions/**: Contains the results of model predictions formatted for submission.
  - `submission0.csv` to `submission5.csv`: Submission files for different models or configurations.
  
- **src/**: Contains source code for the project.
  - `__init__.py`: Indicates that this directory is a Python package.
  
- **requirements.txt**: Lists the Python dependencies required for the project.

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

## Usage Guidelines
- Open the Jupyter notebook `notebooks/TitanicNoteBook.ipynb` to explore the data and run the analysis.
- Use the training dataset to build and evaluate models.
- The submission files in the `submissions/` directory can be used for competition submissions or further evaluation.

#### Data Dictionary
|Variable|Definition|Key|
|--------|----------|---|
|survival|	Survival|	0 = No, 1 = Yes|
|pclass|	Ticket class|	1 = 1st, 2 = 2nd, 3 = 3rd|
|sex|	Sex	|
|Age|	Age in years|	
|sibsp	|# of siblings / spouses aboard the Titanic	|
|parch	|# of parents / children aboard the Titanic	|
|ticket	|Ticket number	|
|fare	|Passenger fare	|
|cabin	|Cabin number	|
|embarked	|Port of Embarkation|	C = Cherbourg, Q = Queenstown, S = Southampton|

## Acknowledgments
This project is based on the Titanic dataset available on Kaggle.