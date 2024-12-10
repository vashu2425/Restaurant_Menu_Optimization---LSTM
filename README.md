# Food Review Rating Prediction

## Overview  
This project predicts food recipe ratings using user reviews and recipe details. It integrates LSTM-based text processing with numerical features like cooking time and nutritional content to predict ratings effectively.

## Dataset  
- **Source**: [Food.com - Recipes and Reviews](https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews)  
- **Details**:  
  - Contains over 500,000 recipes and 1,400,000 reviews from Food.com.  
  - Includes two files:  
    - `reviews.csv`: User reviews with ratings.  
    - `recipes.csv`: Recipe details such as ingredients, preparation time, cooking time, and nutritional values.

## Features  
- **Textual Features**:  
  - Reviews processed using NLP techniques like tokenization and padding.  
- **Numerical Features**:  
  - Recipe details, including preparation time, cooking time, total time, and nutritional values (protein, carbs, fat).  

## Workflow  
1. **Data Preprocessing**:  
   - Cleaned review texts.  
   - Tokenized and padded textual data.  
   - Normalized numerical features.  
2. **Model Building**:  
   - LSTM network for analyzing review texts.  
   - Dense layers for numerical feature processing.  
   - Combined model for final rating predictions.  
3. **Model Evaluation**:  
   - Metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).  
4. **Menu Optimization**:  
   - Suggested high-rated recipes based on predictions.

## Requirements  
- Python 3.x  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `nltk`  
  - `scikit-learn`  
  - `tensorflow`  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/vashu2425/Restaurant_Menu_Optimization---LSTM.git
   cd FoodReviewPrediction

