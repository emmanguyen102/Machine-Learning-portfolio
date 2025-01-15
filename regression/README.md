# Project Name  
1. Predicting the sale price of Bulldozers  (regression)

## 📖 Table of Contents
- [About the Project](#about-the-project)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

---

## 📝 About the Project  
In this project, the bulldozers past sales prices are used to predict the sale price of future bulldozers based on their characteristics.
- Inputs: Bulldozer characteristics such as make year, base model, model series, state of sale (e.g. which US state was it sold in), drive system and more.
- Outputs: Bulldozer sale price (in USD).
This is a typical regression problem since we need to predict a numerical value. And since we're predicting results with a time component (predicting future sales based on past sales), this is also known as a *time series* or *forecasting* problem.
---

## ✨ Overview
We will go through the 6-step Machine Learning model framework. 
![Screenshot 2025-01-15 at 14 00 25](https://github.com/user-attachments/assets/e506b7d9-162b-4265-aecb-6efa040ab20d)

1. Identify the problem:
We are trying to answer the question: How well can we predict future sale price of a bulldozer, based on past sale points and bulldozer characteristics?

2. Dataset: The dataset can be found [License]([#license](https://www.kaggle.com/c/bluebook-for-bulldozers/data)). Data is split into three parts:

- *Train.csv*: is the training set, which contains data through the end of 2011.
- *Valid.csv*: is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
- *Test.csv*: It contains data from May 1, 2012 - November 2012.

3. 
---

## 🚀 Getting Started  

### Prerequisites   
- Python 3.x  


