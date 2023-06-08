
## Housing Price Prediction Model
This repository contains an Jupyter Notebook script that builds a machine learning model to predict housing prices. The model is trained on a dataset of housing features and corresponding prices, allowing it to learn patterns and make accurate predictions on new, unseen data. [Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Dataset
The dataset used for training the housing price prediction model contains the following features:

longitude: The longitude coordinate of the house's location. 
latitude: The latitude coordinate of the house's location. 
housing_median_age: The median age of the houses in the neighborhood. 
total_rooms: The total number of rooms in the house. 
total_bedrooms: The total number of bedrooms in the house. 
population: The population of the neighborhood. 
households: The total number of households in the neighborhood. 
median_income: The median income of the household in the neighborhood. 
median_house_value: The median value of houses in the neighborhood. 
ocean_proximity: The proximity of the house to the ocean (e.g., "Near Bay," "Inland," "Oceanfront"). 
These features provide valuable information about the location, size, and demographic characteristics of the houses and their neighborhoods. The model leverages these features to learn patterns and make accurate predictions on housing prices. 

## Installation
To run the script and build the prediction model, follow these steps:

Clone the repository to your local machine using the following command:

Copy code
```bash
$ git clone https://github.com/Jacob411/House-Price-Predictions.git

Navigate to the project directory:
$ cd housing-price-prediction

Create a virtual environment (optional but recommended) and activate it:
$ python -m venv venv
$ source venv/bin/activate

Install the required dependencies:
$ pip install -r requirements.txt
```

Open the housing_price_prediction.ipynb notebook in your browser and execute the cells to run the code.

## Usage
The Jupyter Notebook contains step-by-step instructions on loading the dataset, preprocessing the data, training the machine learning model, and making predictions. Each code cell is thoroughly documented to explain its purpose and functionality.

Feel free to experiment with different parameters, algorithms, or feature engineering techniques to improve the model's performance. You can also use the trained model to predict the prices of new houses by providing the relevant features.

## Contribution
Contributions to this project are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request. Let's collaborate to make the model even better!
