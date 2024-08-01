# Bangalore_House_Price_Prediction
This project predicts house prices in Bangalore using a Ridge regression model. The web application is built with Flask, providing an interface for users to input house features and receive price predictions.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to predict the prices of houses in Bangalore based on various features such as location, area, number of bedrooms, bathrooms, etc. The prediction model is implemented using Ridge regression and has achieved an R² score of 0.82. The project includes a web application built with Flask, allowing users to interact with the model through a user-friendly interface.

## Features

- **User Input:** Enter house features such as location, area, BHK, etc.
- **Price Prediction:** Get an estimated price based on the input features.


## Installation

### Prerequisites

- Python 3.7 or above
- pip (Python package manager)

### Clone the Repository

```bash
git clone https://github.com/Sayak-das/Bangalore_House_Price_Prediction
cd Bangalore_House_Price_Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Set Up the Flask App

Make sure you have the trained model file (`RidgeModel.pkl`) in the project directory.

## Usage

1. **Run the Flask App:**

   ```bash
   python app.py
   ```

2. **Access the Web App:**

   Open a web browser and go to `http://localhost:5000`.

3. **Input House Features:**

   Enter the required details about the house, such as location, area, BHK, etc.

4. **Get Price Prediction:**

   Submit the form to get the estimated price.

## Model

The prediction model is built using Ridge regression. The model has been trained on a dataset of Bangalore house prices and features. The model achieves an R² score of 0.82, indicating a good fit for the data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

