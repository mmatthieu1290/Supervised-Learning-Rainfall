<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# SUPERVISED-LEARNING-RAINFALL

<em>Predict Rain, Empower Decisions, Transform Weather Forecasting</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/mmatthieu1290/Supervised-Learning-Rainfall?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/mmatthieu1290/Supervised-Learning-Rainfall?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/mmatthieu1290/Supervised-Learning-Rainfall?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Methodology](#Methodology)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)

---

## Overview

Supervised-Learning-Rainfall is a comprehensive developer tool that predicts rainfall occurrence by harnessing meteorological data and machine learning models. It integrates a trained XGBoost classifier to deliver real-time weather forecasts, supporting environmental monitoring and decision-making.

**Why Supervised-Learning-Rainfall?**

This project simplifies the development and deployment of rainfall prediction systems. The core features include:

- 🧪 **🔍 Data Analysis & Modeling:** Utilizes Jupyter Notebook for data preprocessing, feature engineering, and model development.
- ⚙️ **Model Integration:** Seamlessly incorporates a trained XGBoost model for accurate rainfall classification.
- 🚀 **Real-Time Predictions:** Supports operational deployment with real-time weather data analysis.
- 📊 **Actionable Insights:** Transforms raw meteorological data into meaningful forecasts for timely decisions.
- 🌦️ **Open-Source Flexibility:** Designed for developers to customize and extend for various environmental applications.

---
## Methodology

**Features:** atmospheric pressure, maximum temperature, mean temperature, minimum temperature, dew point, humidity, cloud coverage, sunshine duration, wind direction, and wind speed.

**Feature selection:** given the complexity and potential multicollinearity among these features, we applied a feature selection process to identify the most informative variables. The final set of selected features includes: Humidity, Cloud coverage, Sunshine duration, Wind speed, and Diff_temp_dewpoint (the difference between air temperature and dew point).

**Model:** XGBoost delivers the best performance.

**Metric:** ROC AUC score is equal to 0.888271.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JupyterNotebook

### Installation

Build Supervised-Learning-Rainfall from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/mmatthieu1290/Supervised-Learning-Rainfall
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Supervised-Learning-Rainfall
    ```

3. **Install the dependencies:**

echo 'INSERT-INSTALL-COMMAND-HERE'

### Usage

Run the project with:

echo 'INSERT-RUN-COMMAND-HERE'

### Testing

Supervised-learning-rainfall uses the {__test_framework__} test framework. Run the test suite with:

echo 'INSERT-TEST-COMMAND-HERE'

---

<div align="left"><a href="#top">⬆ Return</a></div>

---


