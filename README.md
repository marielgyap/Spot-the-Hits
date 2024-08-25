# Spot-the-Hits! 
## PREDICTING THE NEXT VIRAL SONG BASED ON AUDIO ATTRIBUTES: INSIGHTS FROM THE TOP SONGS ON SPOTIFY IN 2024
My capstone project for the Institute of Data aims to predict the popularity of songs on Spotify using a machine learning model trained on a comprehensive dataset of top songs from 70 countries. The dataset includes both audio features and artist popularity metrics, making it a robust resource for building a predictive model.

There were three components required for the capstone encompassing a Jupyter notebook containing the code, technical report, and presentation delivered to my cohort and a panel of expert data trainers.
### Features Used
The model leverages two key sets of features:
1. **Audio Features**: Includes attributes such as danceability, energy, loudness, and others extracted from the audio tracks.
2. **Artist Popularity**: Considers artist popularity metrics like cumulative artist popularity to further enhance the model's accuracy.
### Project Structure
- **Data Preprocessing**: Feature engineering, missing data handling, scaling, and preparation of two datasets.
- **Modelling**: Various machine learning models were applied, such as CatBoost, RandomForest, LGBM, Gradient Boosting, Lasso, and Linear Regression.
- **Evaluation**: The models were evaluated on metrics like R² and Mean Absolute Error.
### Machine Learning Approach
Several machine learning models were employed, including:
- CatBoostRegressor
- LGBMRegressor
- RandomForestRegressor
- GradientBoostingRegressor
- Lasso Regression
- Linear Regression
The final model achieved an R² score of 0.87 when using both audio features and artist popularity, demonstrating its strong predictive performance.
### Key Findings
- Audio features alone yielded moderate predictive power, with an R² score of 0.20.
- Incorporating artist popularity significantly improved model performance, achieving an R² score of 0.87, highlighting the importance of artist recognition in predicting song success.
### Conclusions
This project successfully built a predictive model for Spotify song popularity, providing valuable insights into the impact of both audio features and artist popularity on a song's likelihood of success.
### Future Work
Future improvements could include:
- Expanding the model to include data outside of the Top 50 charts to capture the data of less popular songs.
- Expanding the model to incorporate more detailed artist data, such as social media presence or historical performance trends.
- Experimenting with advanced hyperparameter tuning and stacking models for further optimisation.
