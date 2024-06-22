# Predictive Analytics in Supply Chain Management

## Project Overview

This project leverages predictive analytics to enhance decision-making in supply chain management with a focus on assessing the timeliness of deliveries. It aims to build a predictive classification model using historical delivery data to forecast delivery performance and identify key factors that impact delivery times.

### Background

In the fast-paced realm of logistics, the timeliness of deliveries is crucial for maintaining customer satisfaction and operational efficiency. Delays can lead to increased costs and reduced customer satisfaction. Predicting potential delays before they occur allows for preemptive action, thus mitigating risks associated with late deliveries.

### Methodology

The project workflow includes:
- **Data Exploration**: Analyzing historical delivery records to identify patterns and trends related to delivery performance.
- **Data Preprocessing**: Transforming raw data into a suitable format for modeling, including handling missing data and feature engineering.
- **Model Development and Comparison**:
  - **Logistic Regression**: Establishes a baseline for performance.
  - **Random Forest**: Utilized for its robustness in handling overfitting and its effectiveness in large datasets.
  - **Support Vector Machine (SVM)**: Employed to handle complex patterns in data effectively.

### Objectives

The objectives of this project are to:
- Analyze the factors affecting delivery timeliness.
- Develop a predictive model that accurately forecasts whether deliveries will be on time.
- Provide actionable insights to improve delivery performance based on the model's predictions.

## Data 

The data for this project comes from the following source:
- [DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) on Kaggle.

## Contents

- **Project.Rmd**: R Markdown document containing all analyses, from data processing to modeling and evaluation.
- **Project-4.html**: Compiled HTML version of the R Markdown file for easy viewing in web browsers.

## Installation

Requirements to run the analysis:
- **R and RStudio**
- **R Packages**: `tidyverse`, `caret`, `randomForest`, `e1071`

To install necessary R packages, run the following command in R:

```R
install.packages(c("tidyverse", "caret", "randomForest", "e1071"))
```

## Usage

To run the analysis:
1. Open `Project.Rmd` in RStudio.
2. Run the code chunks in sequence to reproduce the analysis or modify them for different scenarios.

## Contributing

Contributions are welcome. Please fork the repository and submit pull requests to propose changes.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Inspired by advancements in machine learning and their application in logistics and supply chain management.

