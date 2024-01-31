# Java June Coffee Shops Analysis Project

## Overview

This project focuses on analyzing data from Java June, a company owning several coffee shops across Europe. The aim is to understand factors leading to more reviews for these coffee shops and to explore any potential link between the number of reviews and the shop's rating. This analysis will provide insights for better decision-making and strategies to attract new customers.

## Project Structure

### Task 1: Data Cleaning
- Worked with the 'coffee.csv' file.
- Created a clean and structured DataFrame named `clean_data`.
- Addressed missing values and inconsistencies across columns as per the specified criteria, ensuring data quality and reliability for further analysis.

### Task 2: Review Analysis by Rating
- Analyzed how the number of reviews varies with the rating.
- Generated a DataFrame `reviews_by_rating` that includes columns `rating`, `med_review`, `min_review`, `max_review`.
- This analysis provided insights into customer engagement and satisfaction levels across different ratings.

### Task 3: Baseline Model for Predicting Reviews
- Developed a predictive model using data from 'train.csv'.
- Aimed to predict the number of reviews a store would receive.
- Utilized the 'validation.csv' for model testing and validation.
- Produced a DataFrame `base_result` containing `Place name` and the predicted `rating`.

### Task 4: Comparative Model Development
- Built an alternative predictive model using the same training dataset.
- Focused on enhancing prediction accuracy for the number of reviews.
- Predicted values on 'validation.csv' were compiled in `compare_result`, which includes `Place name` and the predicted `rating`.

## Technologies Used
- Data cleaning and manipulation: `pandas`
- Predictive modeling: `sklearn`


## Contributors
- Danial Rashid Inam

*This project provides valuable insights into customer behavior and preferences for Java June, aiding in strategic planning for better customer reach and service improvement.*
