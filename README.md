# Personal Fitness Tracker

## Overview
The **Personal Fitness Tracker** is a Streamlit-based web application that predicts the number of calories burned during exercise based on user-provided parameters such as age, BMI, heart rate, body temperature, and workout duration. The application utilizes machine learning models to provide accurate predictions and comparisons.

## Features
- User-friendly interface with a dark grey theme and white text.
- Real-time predictions of calories burned based on input parameters.
- Comparison of results with existing dataset values.
- Interactive visualizations and insights.
- Developed using **Streamlit**, **Pandas**, **Scikit-learn**, and **Matplotlib**.

## Technologies Used
- **Python**
- **Streamlit** (for web app development)
- **Pandas** (for data manipulation)
- **Scikit-learn** (for machine learning models)
- **Matplotlib & Seaborn** (for visualizations)
- **RandomForestRegressor** (for calorie prediction)

## Installation
### Prerequisites
Ensure you have Python installed. You can download it from [Python's official website](https://www.python.org/).

### Clone the Repository
```bash
git clone https://github.com/yourusername/personal-fitness-tracker.git
cd personal-fitness-tracker
```

### Create and Activate a Virtual Environment
```bash
# For Windows\python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Running the Application
```bash
streamlit run src/fitness.py
```

## Usage
1. Open the web app in your browser.
2. Enter your details in the sidebar (Age, BMI, Heart Rate, Duration, Body Temperature, and Gender).
3. View the predicted calories burned.
4. Compare results with similar exercise data.
5. Gain insights about how your stats compare with others.

## Dataset
The application requires two datasets:
- `calorie.xlsx` - Contains calorie expenditure data.
- `workouts.xlsx` - Contains exercise-related metrics.

Ensure these files are placed inside the `datasets/` folder before running the app.

## Future Improvements
- Integration with fitness tracker devices.
- More advanced machine learning models.
- Personalized workout recommendations.

## License
This project is licensed under the **MIT License**.

## Contributors
- [Your Name](https://github.com/yourusername)

Feel free to fork and contribute to the project! 🚀

