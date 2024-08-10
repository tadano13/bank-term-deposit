# Bank Term Deposit Prediction

## Overview
This project involves predicting whether a client will subscribe to a term deposit at a bank using machine learning models, specifically a Random Forest classifier. The project is implemented in Python and Jupyter Notebook.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Data Processing:** Preprocesses bank marketing data.
- **Model Training:** Trains a Random Forest model to predict term deposit subscriptions.
- **Evaluation:** Evaluates the model's performance using various metrics.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/tadano13/bank-term-deposit.git
    cd bank-term-deposit
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Jupyter Notebook to explore the data and train the model:
    ```bash
    jupyter notebook BANK\ RANDOM\ FOREST\ PROJECT.ipynb
    ```
2. Alternatively, use the `app.py` script to execute the model pipeline:
    ```bash
    python app.py
    ```

## Dataset
The dataset used in this project is from a bank marketing campaign, containing features related to clients' demographics, job information, and interaction history with the bank.

## Results
The Random Forest model is evaluated for accuracy, precision, recall, and F1 score, providing insights into the effectiveness of the predictive model.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or feature requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
