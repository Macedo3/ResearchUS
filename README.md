# ResearchUS

## 👨‍🎓 Developers: 
- <a href="https://www.linkedin.com/in/gabriel-demacedosantos/">Gabriel de Macedo Santos</a>


## 📜 Description

This project aims to predict the next American Consumer Price Index (CPI), a crucial measure for understanding economic stability and inflationary trends in the United States. The CPI is a metric reflecting variations in the prices of a basket of goods and services consumed by urban households, widely monitored by investors, policymakers, and market analysts.

To achieve this goal, this project combines detailed macroeconomic analysis with advanced machine learning techniques. Factors such as interest rates, fluctuations in oil prices, variations in USD exchange rates, labor market indicators, and other relevant economic metrics will be considered in developing the model. Specifically, the following variables will be included:

- Commercial and Industrial Loans, All Commercial Banks, Percent Change at Annual Rate
- Federal Debt Total Public Debt as Percent of Gross Domestic Product, Percent of GDP
- Federal Debt Total Public as Percent of GDP
- Federal Debt Dollars
- M2
- Median CPI
- StickyCPI_Less_Food_And_Energy
- Unemployment Rate for ages 25-34
- Unemployment Rate for ages 45-54
- Unemployment Rate for ages 55-64
- Unemployment Rate for ages 65 and over

The chosen algorithm to construct the forecasting model is the K Neighbors Regressor, a supervised learning technique that seeks to identify patterns in historical data of the American CPI and utilize them for making future predictions. This algorithm was selected due to its ability to handle non-linear relationships in the data, as well as its flexibility to adapt to different economic contexts.

Moreover, this project incorporates economic expertise into the modeling process, ensuring that the model takes into account nuances and specific market trends in the American economy. The aim is to create a robust and accurate model that can provide reliable CPI forecasts, enabling investors, analysts, and policymakers to make informed decisions regarding financial markets and the economy as a whole.

## 📁 Folder structure

### Project Documentation

1. **Data**: Stores the datasets used in the project.
   - `Commercial and Industrial Loans.xlsx`: Dataset containing information about commercial and industrial loans.
   - `Federal Debt Total Public Debt as Percent of Gross Domestic Product.xlsx`: Dataset representing public debt as a percentage of GDP.
   - `Federal Debt Total Public as Percent of GDP.xlsx`: Dataset representing total public debt as a percentage of GDP.
   - `Federal Debt Dollars.xlsx`: Dataset representing federal debt in dollars.
   - `M2.xlsx`: Dataset containing M2 money supply data.
   - `Median CPI.xlsx`: Median CPI dataset.
   - `StickyCPI_Less_Food_And_Energy.xlsx`: Dataset for Sticky CPI excluding food and energy.
   - `UnemploymentRate_25-34Y.xlsx`: Dataset representing unemployment rate for ages 25-34.
   - `UnemploymentRate_45-54Y.xlsx`: Dataset representing unemployment rate for ages 45-54.
   - `UnemploymentRate_55-64Y.xlsx`: Dataset representing unemployment rate for ages 55-64.
   - `UnemploymentRate_65-OverY.xlsx`: Dataset representing unemployment rate for ages 65 and over.

2. **src**: Contains the Jupyter Notebook files for analysis and machine learning model construction.
   - `analysis.ipynb`: Notebook for exploratory data analysis.
   - `machine-learning-model.ipynb`: Notebook for building the K Neighbors Regressor machine learning model.

3. **document**: Directory for additional project documentation.
   - `images`: Folder for storing images used in documentation.
   - `report.md`: Markdown file containing project report.

4. **README.md**: Explanatory document detailing the project's structure and how to execute the code.

5. **LICENSE**: License file defining the terms of use for the project.

### Directory Structure

```
├── data
│   ├── Commercial and Industrial Loans.xlsx
│   ├── Federal Debt Total Public Debt as Percent of Gross Domestic Product.xlsx
│   ├── Federal Debt Total Public as Percent of GDP.xlsx
│   ├── Federal Debt Dollars.xlsx
│   ├── M2.xlsx
│   ├── Median CPI.xlsx
│   ├── StickyCPI_Less_Food_And_Energy.xlsx
│   ├── UnemploymentRate_25-34Y.xlsx
│   ├── UnemploymentRate_45-54Y.xlsx
│   ├── UnemploymentRate_55-64Y.xlsx
│   └── UnemploymentRate_65-OverY.xlsx
├── src
│   ├── analysis.ipynb
│   └── machine-learning-model.ipynb
├── document
│   ├── images
│   └── report.md
├── README.md
└── LICENSE
```

## 🔧 Installation

### Installation Guide

To run the project successfully, follow these steps to set up the required libraries:

1. **Python Installation**: Ensure Python is installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

2. **Library Installation**:
    - Install required libraries using `pip` command:
        ```bash
        pip install pandas numpy matplotlib scikit-learn
        ```

3. **Jupyter Notebook Installation (Optional)**: If you prefer using Jupyter Notebook:
    - Install Jupyter Notebook using `pip`:
        ```bash
        pip install jupyterlab
        ```

### Additional Libraries Used in the Project

The project utilizes the following libraries:
- `pandas` and `numpy` for data manipulation and computation.
- `matplotlib` for data visualization.
- `scikit-learn` for building the machine learning model.

### Usage Instructions

1. **Data Collection**:
    - Place the necessary datasets in the `data` directory of the project.

2. **Exploratory Analysis**:
    - Open and execute the `analysis.ipynb` file located in the `src` directory using Jupyter Notebook or any compatible platform.

3. **Model Training**:
    - Utilize the `machine-learning-model.ipynb` file inside the `src` directory for building and training the machine learning model using the K Neighbors Regressor algorithm.


## 🗃 Release history 
* 0.3.0 - 26/02/2024
    * Finished the report.
* 0.2.0 - 25/02/2024
    * Started develop the report.
* 0.1.0 - 24/02/2024
    * Finished the model and analysis.

## 📋 License

Copyright 2023 <a href="https://www.linkedin.com/in/gabriel-demacedosantos/">Gabriel de Macedo Santos</a>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.