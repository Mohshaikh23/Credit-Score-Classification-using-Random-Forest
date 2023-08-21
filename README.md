# Credit Score Classification using Random Forest

This project aims to predict credit scores based on various financial and personal factors using the Random Forest classification algorithm. The dataset contains features such as annual income, monthly in-hand salary, number of bank accounts, credit cards, interest rate, and more. By analyzing these features, the goal is to create a model that accurately predicts credit scores.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Exploration](#data-exploration)
- [Model Building](#model-building)
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, we analyze a dataset containing financial and personal factors to predict credit scores using the Random Forest classification algorithm. The main steps include:

1. Exploring the dataset to understand the features and data distribution.
2. Preprocessing the data, converting categorical features into numerical ones.
3. Splitting the data into training and testing sets.
4. Building a Random Forest classification model using important features.
5. Making predictions using user-input features.

## Data Exploration

The dataset consists of various financial and personal features, and their impact on credit scores is analyzed. Box plots are used to visualize the relationship between each feature and credit scores.

## Model Building

A Random Forest classification model is trained using important features identified during data exploration. This model is used to predict credit scores based on user input.

## Usage

To predict credit scores using the trained model, follow these steps:

1. Clone this repository.
2. Ensure you have the required dependencies installed (see [Dependencies](#dependencies)).
3. Run the provided Python script (`credit_score_prediction.py`).
4. Input the required features (annual income, monthly in-hand salary, etc.).
5. The script will output the predicted credit score.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Mohshaikh23/Credit-Score-Classification-using-Random-Forest.git
```

2. Navigate to the project directory:

```bash
cd credit-score-prediction
```

3. Run the prediction script:

```bash
python credit_score_prediction.py
```

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- scikit-learn

You can install them using the following command:

```bash
pip install pandas numpy scikit-learn
```

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests for any improvements or features.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the content according to your project's specific details. Good luck with your Credit Score Classification project!