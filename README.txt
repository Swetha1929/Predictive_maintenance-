# Predictive Maintenance - Engine Condition Prediction

## Project Overview
This project predicts the condition of an engine using a trained Machine Learning model. The application is built using **Streamlit** and deployed on **Streamlit Community Cloud**. The trained model is stored on the **Hugging Face Model Hub** and downloaded dynamically during application startup.

## Features
- Predicts engine condition based on user inputs.
- Downloads the trained model from the Hugging Face Model Hub.
- Displays prediction probabilities.
- Interactive Streamlit interface.

## Repository Structure

```
.
├── app.py
├── requirements.txt
├── .github/
│   └── workflows/
│       └── pipeline.yml
└── README.md
```

## Model Repository

The trained model is hosted on Hugging Face:

**https://huggingface.co/Swetha1929/predictive-maintenance-engine-model**

## Deployment

The application is deployed using **Streamlit Community Cloud**.

Deployment Steps:
1. Push the project to GitHub.
2. Connect the GitHub repository to Streamlit Community Cloud.
3. Select:
   - Repository
   - Branch: `main`
   - Main file: `app.py`
4. Set Python version to **3.11**.
5. Deploy the application.

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Hugging Face Hub

## Author

Swetha
