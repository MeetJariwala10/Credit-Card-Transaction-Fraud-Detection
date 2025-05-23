# Credit Card Transactions Fraud Detection Model

This repository contains a project that builds and evaluates machine learning models for detecting fraudulent credit card transactions. The work covers data acquisition, preprocessing, exploratory analysis, model training (multiple classifiers), evaluation, and key insights.

## Project Overview

Credit card fraud costs financial institutions and customers billions of dollars each year. The goal of this project is to develop machine learning models that can accurately identify fraudulent transactions. We compare multiple classifiers, analyze their performance, and extract actionable insights.

## Dataset

- **Source**: Publicly available credit card transactions dataset (downloaded via automated scraping script).
- **Size**: Approximately 30,000 transactions with each record labeled as fraudulent or legitimate.

## Feature Description

| Feature                   | Description                                                                                         |
|---------------------------|-----------------------------------------------------------------------------------------------------|
| `trans_amount`            | Transaction amount. High values may indicate fraud.                                                 |
| `trans_date_trans_time`   | Timestamp of the transaction. Abnormal times (late night, holidays) may correlate with fraud.       |
| `merchant`                | Merchant identifier and related details (latitude, longitude).                                      |
| `dob`                     | Customer date of birth. Allows extraction of age.                                                   |
| `category`                | Transaction category (e.g., groceries, electronics).                                                |
| `job`                     | Customer occupation.                                                                               |
| `is_fraud`                | Target label (0 for legitimate, 1 for fraud).                                                      |

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection

2. **Create a virtual environment**
- `python3 -m venv env`
- `source env/bin/activate`

3. **Install dependencies**
- `pip install -r requirements.txt`

4. **Move forward and run model**

