# Restaurant Analysis Project

This project consists of three tasks focused on analyzing restaurant data, building predictive models, and developing recommendation systems. The tasks aim to explore restaurant ratings, recommend restaurants based on user preferences, and perform geographical analysis of restaurant locations.

## Tasks Overview

### Task 1: Predict Aggregate Restaurant Ratings

**Objective:** Build a machine learning model to predict the aggregate rating of a restaurant based on other features.

#### Steps:
1. Preprocess the dataset:
   - Handle missing values.
   - Encode categorical variables.
   - Split the data into training and testing sets.
2. Select a regression algorithm (e.g., linear regression, decision tree regression).
3. Train the model on the training data.
4. Evaluate the model's performance using appropriate regression metrics:
   - Mean Squared Error (MSE).
   - R-squared.
5. Interpret the model's results and analyze the most influential features affecting restaurant ratings.

### Task 2: Build a Restaurant Recommendation System

**Objective:** Create a restaurant recommendation system based on user preferences.

#### Steps:
1. Preprocess the dataset:
   - Handle missing values.
   - Encode categorical variables.
2. Determine the criteria for recommendations (e.g., cuisine preference, price range).
3. Implement a content-based filtering approach:
   - Recommend restaurants similar to user preferences.
4. Test the recommendation system:
   - Provide sample user preferences.
   - Evaluate the quality of recommendations.

### Task 3: Perform Geographical Analysis of Restaurants

**Objective:** Analyze the geographical distribution of restaurants.

#### Steps:
1. Explore latitude and longitude coordinates and visualize restaurant distribution on a map.
2. Group restaurants by city or locality:
   - Analyze the concentration of restaurants.
3. Calculate statistics (e.g., average ratings, cuisines, price ranges) by city or locality.
4. Identify insights and patterns related to restaurant locations.

---

## Dataset
The dataset includes features related to restaurants such as ratings, cuisines, price range, geographical coordinates, and more.

---

## Project Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Folium (for geographical visualization)

---

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run
1. Open the Jupyter Notebook files (`TASK_1_Restaurant_Rating.ipynb`, `TASK_2_Restaurant_Recommendation.ipynb`, `TASK_4_Location_Based_Analysis.ipynb`).
2. Follow the instructions in each notebook to execute the tasks.
3. Visualize the results and explore the analyses.

---

## Results and Insights
- **Task 1:** Identified key features influencing restaurant ratings.
- **Task 2:** Built a recommendation system tailored to user preferences.
- **Task 3:** Discovered geographical patterns in restaurant distributions.

---

## Future Improvements
- Incorporate collaborative filtering for Task 2 to enhance recommendations.
- Use advanced regression models like Random Forest or Gradient Boosting for Task 1.
- Include additional features like user reviews and restaurant popularity for better insights.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
