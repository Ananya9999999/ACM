📊 Score Predictor using Linear Regression

This project predicts a student’s marks based on the number of hours they study using Linear Regression. It demonstrates a simple end-to-end machine learning workflow including data loading, training, testing, evaluation, and prediction.

🚀 Features

Uses Linear Regression from scikit-learn
Splits data into training and testing sets
Evaluates model performance using Mean Squared Error (MSE)
Predicts marks for new study hours input
Simple and beginner-friendly implementation

🛠️ Technologies Used

Python
NumPy
Pandas
Scikit-learn

📂 Dataset

The project uses a CSV file named Student_Marks.csv with the following columns:

Column Name	Description
time_study	Number of hours studied
Marks	Marks obtained by the student

⚙️ How It Works

Load the dataset using Pandas
Separate features (time_study) and target (Marks)
Split data into training and testing sets
Train a Linear Regression model
Make predictions on test data
Evaluate performance using Mean Squared Error
Predict marks for a custom study duration

▶️ Running the Project

Clone the repository:
git clone https://github.com/your-username/score-predictor.git

Install dependencies:

pip install numpy pandas scikit-learn

Run the script:

python score_predictor.py

📈 Sample Output

Displays the first 5 records from the dataset
Shows predicted marks for test data
Prints Mean Squared Error (MSE)
Predicts marks for 10 hours of study

Example:
Predicted Marks for studying 10 hours: 88.45

🎯 Use Cases

Learning basic machine learning concepts
Understanding regression models
Academic mini-projects
Practice with real datasets

📌 Future Improvements

Add data visualization (matplotlib / seaborn)
Use multiple features
Build a web interface for predictions

Compare with other regression models

⭐ If you find this project helpful, feel free to star the repository!
