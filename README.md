# Advertising Agency Analysis
This repository contains resources for analyzing TikTok influencers and utilizing a predictive model to support decision-making in advertising campaigns.

Files Included
advertising agency.ipynb
A Jupyter Notebook that outlines the analysis and steps used to build and evaluate a predictive model. It includes exploratory data analysis, feature engineering, and model training.

forest_model_new.pkl
A pre-trained Random Forest model saved as a .pkl file for deployment. The model predicts outcomes based on influencer data.

social media influencers-TIKTOK ---DEC 2022.csv
A dataset containing information on TikTok influencers as of December 2022, including their reach, engagement metrics, and other relevant features for analysis.


# Load the model
with open('forest_model_new.pkl', 'rb') as f:
    model = pickle.load(f)

# Requirements
Python 3.7+ <br>
Jupyter Notebook <br>
pandas, numpy, scikit-learn, and matplotlib libraries
