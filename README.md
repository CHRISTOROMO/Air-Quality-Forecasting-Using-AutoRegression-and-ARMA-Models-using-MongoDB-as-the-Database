# Air Quality Forecasting Using AutoRegression, ARMA Models, and MongoDB Database

## Overview
This project focuses on forecasting air quality by leveraging time series analysis techniques, specifically AutoRegression (AR) and AutoRegressive Moving Average (ARMA) models. The primary objective is to predict PM2.5 concentrations, a critical indicator of air pollution, using data sourced from a MongoDB database. The repository demonstrates efficient data handling, model training, and validation processes, making it a practical resource for environmental data analysis.

## Features
- Integration of MongoDB as the source database for PM2.5 data.
- Implementation of AutoRegression and ARMA models for time series forecasting.
- Data preprocessing and exploratory analysis to ensure high-quality input.
- Walk-forward validation to evaluate model performance.
- Visualization of predictions compared to actual values.

## Requirements
- Python 3.12+
- MongoDB
- Libraries: `pandas`, `numpy`, `statsmodels`, `matplotlib`, `pymongo`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/CHRISTOROMO/Air-Quality-Forecasting-Using-AutoRegression-and-ARMA-Models-using-MongoDB-as-the-Database.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Results
The repository includes visualizations comparing predicted PM2.5 values with actual measurements, showcasing the effectiveness of AR and ARMA models.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- PM2.5 dataset sourced from MongoDB.
- Inspiration from environmental monitoring and data science communities.
