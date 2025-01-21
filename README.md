# Customer Retention Prediction Model

## Project Overview
This solo project aims to showcase my expertise in machine learning, data science, and cloud deployment by predicting customer retention (churn) using a classification model. The project covers the full data science workflow, including exploratory data analysis (EDA), data preprocessing, feature engineering, model building, and hyperparameter tuning, culminating in deployment on Azure.

## Features
- **Retention Prediction**: Classifies customers as retained or likely to churn based on various input features.
- **End-to-End Workflow**: Includes EDA, data preprocessing, feature engineering, model building, and hyperparameter tuning.
- **Azure Deployment**: Deployed on Azure for scalability and ease of access.
- **Automated CI/CD**: GitHub Actions used for continuous integration and deployment.

## Live Application
Access the live application here: [Customer Retention Prediction App](https://customer-retention-prediction-project.azurewebsites.net/)

## Dataset
The model uses a dataset featuring:
- **Demographics**: Age, gender, etc.
- **Behavioral Metrics**: Weekly usage, song skip rate, etc.
- **Subscription Details**: Type, pauses, etc.
- **Interaction Data**: Customer service inquiries, notifications clicked, etc.

## Technologies Used
- **Python**: Core language for model development.
- **Pandas & NumPy**: Data manipulation and numerical computations.
- **Scikit-learn**: Model building and hyperparameter tuning.
- **Matplotlib/Seaborn**: Visualization tools for EDA.
- **Jupyter Notebook**: For interactive analysis and development.
- **Azure**: Cloud deployment platform.
- **GitHub Actions**: CI/CD pipeline management.

## Installation and Setup
### Local Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-retention-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd customer-retention-prediction
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

### Azure Deployment
The application is deployed on Azure and can be accessed via the provided link. No additional setup is needed for general use.

## CI/CD Pipeline
GitHub Actions manage the CI/CD pipeline:
- **Continuous Integration**: Runs tests and linting on every push.
- **Continuous Deployment**: Deploys to Azure upon successful test completion.

Details can be found in the [.github/workflows](.github/workflows) directory.

## Usage
1. Access the live application via the provided Azure link.
2. Input customer data through the web interface.
3. Receive predictions on whether the customer is likely to be retained or churn.

## Results
Performance metrics of the classification model:
- Accuracy: 0.8391
- F1 score: 0.8391

## Methodology
- **Exploratory Data Analysis (EDA)**: Analyzed data distributions and key patterns.
- **Data Preprocessing**: Cleaned and prepared the data for training.
- **Feature Engineering**: Created and selected features to improve model performance.
- **Model Building**: Developed a classification model using Scikit-learn.
- **Hyperparameter Tuning**: Optimized model parameters for better performance.

## Future Work
- **Model Refinement**: Enhance accuracy with additional data and features.
- **User Experience**: Improve the web interface for a better user experience.
- **Broader Application**: Adapt the model for other industries and customer datasets.

## Purpose
This project serves as a demonstration of my skills in:
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Feature Engineering
- Machine Learning Model Development and Hyperparameter Tuning
- Cloud Deployment and Continuous Integration/Deployment (CI/CD)

## License
This project is licensed under the MIT License.

## Acknowledgements
- Dataset sourced from [Kaggle].


---

For queries or feedback, please contact [yusufsiddiquiwork@icloud.com].

