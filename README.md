# Pokemon-by-Dose-of-Data

# Pokémon Data Analysis and Classification

![Pokémon](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-lBlhtAhIWQ06GBntsdwCUbdOpsiVMBQdCw&s)

Welcome to the Pokémon Data Analysis and Classification project! In this repository, you will find an in-depth exploratory data analysis (EDA) of the Pokémon dataset, as well as a predictive model to classify Pokémon as either Legendary or Non-Legendary based on their attributes.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Predictive Modeling](#predictive-modeling)
- [Insights](#insights)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

The goal of this project is to utilize machine learning algorithms to predict whether a Pokémon is Legendary based on its stats and type. The project involves data preprocessing, exploratory data analysis, model training, hyperparameter tuning, and model evaluation.

## Dataset

The dataset used in this project includes various attributes of Pokémon such as:

- Name
- HP
- Attack
- Defense
- Special Attack
- Special Defense
- Speed
- Type 1
- Type 2
- Generation
- Legendary Status

For more details, refer to the [data.md](data.md) file.

## Installation

To get started, clone this repository to your local machine and install the required dependencies.

```bash
git clone https://github.com/UnbeatableBann/Pokemon-by-Dose-of-Data.git
cd Pokemon-by-Dose-of-Data
pip install -r requirements.txt
```

## Usage

You can explore the Jupyter notebook provided to understand the data preprocessing steps, exploratory data analysis, model training, and evaluation.

```bash
jupyter notebook Pokemon.ipynb
```

## Exploratory Data Analysis

In the EDA section, we explore various aspects of the Pokémon dataset:

- **Distribution of Pokémon Types:** Visualize the distribution of primary and secondary types.
- **Base Stats Analysis:** Analyze the distribution of base stats (HP, Attack, Defense, etc.).
- **Generational Differences:** Compare base stats across different generations of Pokémon.
- **Correlations:** Identify correlations between different attributes.
- **Height and Weight Analysis:** Explore how heights and weights vary across different types and generations.

![image](https://github.com/UnbeatableBann/Pokemon-by-Dose-of-Data/assets/140196120/463e72ad-c47a-49d3-a631-0e0356018a5c)

![image](https://github.com/UnbeatableBann/Pokemon-by-Dose-of-Data/assets/140196120/6a3e1a0b-1ba6-4d68-85b9-1d88073e20af)

## Predictive Modeling

The predictive modeling section includes building and evaluating models to classify Pokémon as Legendary or Non-Legendary. The models used include:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

![image](https://github.com/UnbeatableBann/Pokemon-by-Dose-of-Data/assets/140196120/4713531d-3b71-46ab-b7af-42246c020b0f)

### Model Training and Evaluation

We split the data into training and testing sets, train the models, and evaluate their performance using metrics such as accuracy, precision, recall, and F1 score.

### Hyperparameter Tuning

Hyperparameter tuning is performed to optimize the model's performance.

![image](https://github.com/UnbeatableBann/Pokemon-by-Dose-of-Data/assets/140196120/d2b188bb-3afe-4a49-bf82-21df97bb079f)

## Insights

Here are some interesting insights derived from the exploratory data analysis:

- **Type Distribution:** Water and Normal types are the most common primary types among Pokémon. Some types, such as Ice and Ghost, are less common compared to others.
- **Base Stats:** Legendary Pokémon generally have higher base stats across all categories compared to non-legendary Pokémon. Specifically, Legendary Pokémon excel in HP, Attack, and Special Attack.
- **Generational Patterns:** Each generation introduces a variety of new types and stats. For instance, Generation 4 has a higher average Attack stat compared to other generations.
- **Height and Weight Correlation:** There is a moderate positive correlation between the height and weight of Pokémon, meaning taller Pokémon tend to be heavier.
- **Type Combinations:** Some type combinations are more prevalent among Legendary Pokémon. For example, Dragon and Psychic types are common among Legendaries. But as secondary type it changes.
- **Capture Rates:** Legendary Pokémon have significantly lower capture rates compared to non-legendary Pokémon, making them harder to catch.

These insights can be valuable for Pokémon enthusiasts and researchers to understand the characteristics and patterns within the Pokémon universe.

## Results

The performance of each model is evaluated, and the best-performing model is selected based on the evaluation metrics. Below is a comparison of model accuracies:

| Model                 | Accuracy |
|-----------------------|----------|
| Logistic Regression   | 0.93     |
| Decision Tree         | 0.93     |
| Random Forest         | 0.92     |
| XGBoost               | 0.92     |

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Acknowledgements

- The Pokémon dataset used in this project is sourced by [Analysis](https://github.com/Dose-of-Data/analysis-arena/blob/main/data.md).
- Special thanks to the Pokémon community and [Dose of Data](https://github.com/Dose-of-Data) who provided valuable feedback and support.

