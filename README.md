```markdown
# Predicting Match Outcomes in the FIFA World Cup 2022

## Project Overview

This project utilizes machine learning to predict the outcomes of FIFA World Cup 2022 matches. By analyzing various match statistics, the model forecasts whether a team will **Win**, **Draw**, or **Lose**.

**Key Features:**
- **Data Preprocessing:** Cleaning and preparing match data.
- **Model Training:** Developing a Random Forest classifier.
- **Interactive Interface:** Using Google Colab widgets for real-time predictions.
- **Visualization:** Displaying prediction probabilities through bar charts.

## Dataset

The dataset comprises match-level statistics, including:
- Goals scored
- Possession percentage
- Shooting accuracy
- Assists
- Shots inside and outside the penalty area
- Goal conversion rate
- Cross accuracy
- Discipline metrics (fouls, cards)
- Shots per possession

**Note:** Non-numeric columns like `Team`, `Against`, `Group`, and `Pts` were excluded from the training process.

## Model

- **Algorithm:** Random Forest Classifier
- **Performance:** Achieved an accuracy of approximately 73% on the test set.
- **Features:** Utilized numeric match statistics for training.

## Interactive Interface

An interactive interface allows users to adjust match statistics using sliders and view:
- Predicted match outcome
- Probabilities for Win, Draw, and Loss
- A bar chart visualizing these probabilities

**Access the interactive notebook here:**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1b5ALSPGgkJtTbonRHb4MkedyScU8bnWb?usp=sharing)

## Usage

1. Open the notebook using the link above.
2. Follow the instructions within the notebook to:
   - Load the dataset and trained model.
   - Utilize the interactive widgets to simulate different match scenarios.
   - View and interpret the predictions and visualizations.

## Project Structure

```

fifa2022-match-prediction/
│
├── data/                   # Dataset files
│   └── fifa2022\_matches.csv
├── notebooks/              # Jupyter notebooks
│   └── match\_prediction.ipynb
└── README.md               # Project description

```

## Acknowledgments

- **Data Source:** [FIFA 2022 Match Statistics Dataset](https://www.kaggle.com/datasets/abecklas/fifa-world-cup-2022-matches)
- **Libraries Used:** pandas, scikit-learn, matplotlib, ipywidgets

## License

This project is open-source and available under the MIT License.
```

```
## Acknowledgments


- **Data Source:** [FIFA 2022 Match Statistics Dataset](https://www.kaggle.com/datasets/abecklas/fifa-world-cup-2022-matches)
- **Libraries Used:** pandas, scikit-learn, matplotlib, ipywidgets


## License


This project is open-source and available under the MIT License.
```
