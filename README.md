# End-to-End Price Predictor

This repository contains the "End-to-End Price Predictor" project, built to predict prices using core Machine Learning (ML) concepts and Python. The project demonstrates an end-to-end ML pipeline, including data preprocessing, feature engineering, model building, and deployment. It utilizes **MLflow** and **Zenflow** for experiment tracking and deployment management.

## Table of Contents
- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The "End-to-End Price Predictor" aims to:
- Build a robust price prediction model using Python and core ML techniques.
- Demonstrate step-by-step ML processes, including data ingestion, preprocessing, and model evaluation.
- Deploy the trained model and track experiments using **MLflow** and **Zenflow**.

## Directory Structure
```
END-TO-END-PRICE-PREDICTOR
|
├── analysis
│   ├── analyze_src
│   │   ├── basic_data_inspection.py
│   │   ├── bivariate_analysis.py
│   │   ├── missing_values_analysis.py
│   │   ├── multivariate_analysis.py
│   │   ├── univariate_analysis.py
│   │   └── EDA.ipynb
│   └── data
│       └── archive.zip
|
├── explanations
│   ├── factory_design_pattern.py
│   ├── strategy_design_pattern.py
│   └── template_design_pattern.py
|
├── extracted_data
│   └── AmesHousing.csv
|
├── pipelines
|
├── src
│   ├── data_splitter.py
│   ├── feature_engineering.py
│   ├── handle_missing_values.py
│   ├── ingest_data.py
│   ├── model_building.py
│   ├── model_evaluator.py
│   └── outlier_detection.py
|
├── steps
│   ├── data_ingestion_step.py
│   ├── data_splitter_step.py
│   ├── dynamic_importer.py
│   ├── feature_engineering_step.py
│   ├── handle_missing_values_step.py
│   ├── model_building_step.py
│   ├── model_evaluator_step.py
│   ├── model_loader.py
│   ├── outlier_detection_step.py
│   └── prediction_service_loader.py
|
├── .gitignore
├── config.yaml
├── LICENSE
├── README.md
├── requirements.txt
├── run_deployment.py
├── run_pipeline.py
└── sample_predict.py
```

## Features
- **Data Analysis and Preprocessing**: Scripts for handling missing values, outlier detection, and feature engineering.
- **Modular Pipelines**: Flexible and reusable ML pipeline design with stepwise modular scripts.
- **Experiment Tracking**: Integration with **MLflow** and **Zenflow** for tracking experiments and managing deployments.
- **Design Patterns**: Implementation of factory, strategy, and template design patterns to enhance code reusability and scalability.
- **Deployment**: Easily deployable pipelines with `run_deployment.py`.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/FAbdullah17/End-to-End-Price-Predictor.git
   cd End-to-End-Price-Predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure the project:
   - Update the `config.yaml` file with your project settings.

## Usage
- **Run the Pipeline**:
  ```bash
  python run_pipeline.py
  ```
- **Deploy the Model**:
  ```bash
  python run_deployment.py
  ```
- **Test Predictions**:
  ```bash
  python sample_predict.py
  ```

## Technologies Used
- **Python**: Core language for development.
- **MLflow**: For experiment tracking.
- **Zenflow**: For deployment management.
- **pandas**, **NumPy**, **scikit-learn**, **matplotlib**: Libraries for data manipulation, analysis, and modeling.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
Developed by [FAbdullah17](https://github.com/FAbdullah17).
