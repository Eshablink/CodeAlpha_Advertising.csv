# CodeAlpha_Advertising.csv
CodeAlpha_Project_Advertising_Sales_Prediction
Project Overview
This project predicts Sales based on the advertising budgets for TV, Radio, and Newspaper. The goal is to use various machine learning models to analyze how advertising spend impacts sales. The dataset is used to train and evaluate Linear Regression, Decision Tree, and Support Vector Machine (SVM) models.

Dataset Description
The dataset contains the following columns:

TV: The budget allocated for TV advertising (in monetary units).
Radio: The budget allocated for Radio advertising (in monetary units).
Newspaper: The budget allocated for Newspaper advertising (in monetary units).
Sales: The sales achieved (in monetary units).
Example data:

TV	Radio	Newspaper	Sales
230.1	37.8	69.2	22.1
44.5	39.3	45.1	10.4
17.2	45.9	69.3	9.3
Objective
Train machine learning models to predict sales based on advertising budgets across different channels.
Evaluate model performance using metrics like MAE, RMSE, and R².
Machine Learning Models Used
Linear Regression: A simple model to capture the linear relationship between the advertising spend and sales.
Decision Tree Regression: A non-linear model that splits the data into branches based on feature values.
Support Vector Machine (SVM): A non-linear model that uses a Radial Basis Function (RBF) kernel for better prediction in non-linear relationships.
Performance Evaluation
The following metrics were used to evaluate the model performance:

Mean Absolute Error (MAE): Measures the average magnitude of errors in predictions.
Root Mean Squared Error (RMSE): Penalizes larger errors more than MAE.
R² (Coefficient of Determination): Measures how well the model explains the variance in the target variable (Sales).
How to Run the Project
Clone the repository:



git clone https://github.com/YourUsername/CodeAlpha_Project_Advertising_Sales_Prediction.git
Install dependencies:

Make sure you have Python installed, then use pip to install the required packages:



pip install -r requirements.txt
Run the model training and evaluation:

Once the dependencies are installed, you can run the script to train and evaluate the models:

python train_models.py
View the results:

The model's performance metrics will be printed on the console.

Repository Structure
train_models.py: Python script to train and evaluate the machine learning models.
requirements.txt: List of required Python libraries.
README.md: Project documentation (this file).
advertising_sales_data.csv: The dataset used in this project.
output/: Folder containing the model results and performance metrics.
Project Completion
GitHub Repository:
The entire source code for this project has been uploaded to GitHub. You can access it here:
GitHub Repository - CodeAlpha_Project_Advertising_Sales_Prediction

LinkedIn Update:
I have shared a video explaining the project and its results on LinkedIn. You can watch the video and view the update here:
LinkedIn Project Update

License
This project is licensed under the MIT License. See the LICENSE file for details.

How to Contribute
Feel free to fork the repository, make changes, and submit a pull request if you have any improvements or suggestions.

Contact
For any questions or suggestions, you can contact me via:eshascs@gmail.com

Email: eshascs@gmail.com
GitHub: 
LinkedIn: 
Final Notes
This project is a part of my learning journey in machine learning and data science. I am happy to share it with the community, and I hope it helps others who are working with advertising data or similar datasets.
