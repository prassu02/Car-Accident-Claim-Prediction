# Car Accident Claim Prediction

This project predicts the outcome of car accident claims (e.g., whether a claim will result in a loss) using a Logistic Regression model. The dataset contains information about the claimant, accident details, and insurance status.

## Features
The model predicts the `LOSS` column based on the following features:
- **CASENUM**: Unique identifier for each case.
- **ATTORNEY**: Indicates whether an attorney is involved (1 = Yes, 0 = No).
- **CLMSEX**: Claimant's gender (1 = Male, 0 = Female).
- **CLMINSUR**: Claimant's insurance status (1 = Insured, 0 = Not Insured).
- **SEATBELT**: Indicates whether the claimant was wearing a seatbelt (1 = Yes, 0 = No).
- **CLMAGE**: Claimant's age (in years).

## Installation
1. Clone the repository: `git clone <repository-link> && cd car-claim-prediction`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Streamlit app: `streamlit run app/streamlit_app.py`

## Usage
1. Open the Streamlit app in your browser.
2. Input details such as attorney involvement, claimant’s gender, insurance status, age, and seatbelt usage.
3. Click the **"Predict"** button to get the prediction for the claim outcome.

## Technologies Used
- **Python**: Data processing and modeling.
- **Scikit-learn**: Logistic Regression model.
- **Streamlit**: Web app interface.
- **Pandas**: Data analysis and manipulation.


