
# An Analysis of Nearpeer's Influence on Student Enrollment

**Authors**: Emmanuel Owusu Asante, Obeng Adjei Paa Kwasi, Chinonso Ozoigbo, and David York

## Project Overview

This project investigates the influence of Nearpeer—a student engagement platform—on student enrollment in universities. Using data from Nearpeer and university datasets, the analysis focuses on identifying patterns and correlations in student engagement metrics and their relation to enrollment outcomes.

## Project Structure

1. **Data Loading and Preprocessing**
   - Load and clean data from two main sources: `University data` and `Nearpeer User data`.
   - Perform various data cleaning steps, such as:
     - Standardizing column names.
     - Converting data types and handling missing values.
     - Merging datasets based on a common identifier.

2. **Exploratory Data Analysis (EDA)**
   - Visualize key metrics (e.g., `last_activity_date`) to understand the engagement patterns of Nearpeer users.
   - Analyze distributions and calculate relevant time-based metrics, such as the number of days between deposit and September 1st, and between last activity and September 1st.

3. **Data Dictionary**
   - Load and inspect data dictionaries for each dataset to understand variable definitions and units.

## Installation

1. Clone this repository.
2. Install required dependencies with:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure the `requirements.txt` file lists necessary packages, including `pandas`, `numpy`, `matplotlib`, `seaborn`, and `janitor`.)*

3. Ensure the data files (e.g., `Nearpeer Data Roux Analytics Class 040524.2 confidential.xlsx`) are stored in a `data` folder within the project directory.

## Usage

1. Open and run `aly_6080_nearpeer_final.ipynb` to see the full analysis.
2. Modify data paths or parameters as needed to customize the analysis for different datasets or time frames.

## Results

The notebook provides insights into:
- Patterns of student engagement and activity.
- Potential correlations between specific Nearpeer engagement metrics and university enrollment outcomes.

## License

This project is for educational purposes only. Any distribution of the confidential Nearpeer data files is prohibited.
