# GNSS Decimeter Level Accuracy Improvement using Machine Learning

## Big Data Analysis - Sem 6

### Project Overview:
This repository contains the code for the project titled "GNSS Decimeter Level Accuracy Improvement using ML." The project aims to enhance the accuracy of GNSS (Global Navigation Satellite System) measurements at the decimeter level using machine learning techniques, with the integration of Kalman filtering.

### Project Details:
- **Name**: Anuj Patel
- **Roll Number**: 21BCP411

### About the Project:
In this project, we delve into the realm of Big Data Analysis to improve the accuracy of GNSS measurements. The focus lies on utilizing machine learning algorithms, coupled with Kalman filtering, to refine the accuracy of GNSS measurements at the decimeter level. The repository includes exploratory data analysis (EDA) performed on both aggregate and phone-level data. Subsequently, a neural network model is trained to predict the residuals of base estimations provided with aggregated features.

### Repository Structure:
- `data/`: Contains the datasets used for analysis and model training.
- `notebooks/`: Jupyter notebooks containing the code for EDA and model training.
- `models/`: Stores trained machine learning models.
- `src/`: Source code files, including Kalman filtering implementation, if any.
- `README.md`: Overview and instructions for the project.
- `results.png`: Image showing the error of the trained model. The y-axis represents the error multiplied by 10,000 to display it in centimeters.

### Project Workflow:
1. **Data Collection**: Gather GNSS data at both aggregate and phone levels.
2. **Exploratory Data Analysis (EDA)**: Understand the characteristics of the data, identify patterns, and gain insights.
3. **Data Preprocessing**: Prepare the data for model training by handling missing values, scaling, etc.
4. **Model Training**: Train a neural network model using the preprocessed data.
5. **Integration of Kalman Filtering**: Implement Kalman filtering to further refine GNSS measurements.
6. **Model Evaluation**: Assess the performance of the trained model using appropriate metrics.
7. **Deployment**: If applicable, deploy the model for practical use.

### Instructions for Use:
1. Clone the repository to your local machine.
2. Install the required dependencies as mentioned in `requirements.txt`.
3. Explore the Jupyter notebooks in the `notebooks/` directory for EDA, model training, and Kalman filtering implementation.
4. Follow the instructions within the notebooks to execute the code and reproduce the results.

### Contribution Guidelines:
- Contributions are welcome via pull requests.
- For major changes, please open an issue first to discuss the proposed changes.
- Ensure to update documentation as appropriate.

### License:
This project is licensed under the [MIT License](LICENSE).

For any queries or feedback, feel free to contact Anuj Patel at [email@example.com](mailto:email@example.com).
