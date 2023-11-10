# Movie Recommendation System with H2O and H2O Wave

## Overview

Users can search movie names and get released year, rating, and actor names and can see a predicted rating of actors for next year by using a trained model with H2O AutoML. 

## Folder Structure

The project directory is structured as follows:

```
movie_recommendation/
│
├── data/
│   ├── movies.csv
│   ├── rating.csv
│   ├── result.csv
|
├── model/
│   ├── model
|
├── assets/
│   ├── screen.png
│   ├── screen1.png
│   ├── recording.mp4
│
├── scripts/
│   ├── rating_predictor.py
│   ├── trainer.py
│
├── app.py
├── test.py
│
├── README.md
```

- **Screenshots**
  - Screenshot 1
![Sceenshot](https://raw.githubusercontent.com/Luxshan2000/movie_recommendation_project/main/assets/screen.png)
  - Screenshot 2
![Sceenshot](https://raw.githubusercontent.com/Luxshan2000/movie_recommendation_project/main/assets/screen2.png)

- **[See demo Video](https://raw.githubusercontent.com/Luxshan2000/movie_recommendation_project/main/assets/recording.mp4)**


## Getting Started

1. **Install Dependencies**:
   - Ensure you have Python installed.
   - Install required packages using `pip install -r requirements.txt`.


3. **Running the Web App**:
   - Start the web app by running `wave run app` 
   - Access the web app in your browser at `http://localhost:10101`.

## Usage

1. Open the web app
2. Use the Search bar to find Tamil movies
3. Scroll down and see the predicted rating of actors

## Author

T.Luxshan
