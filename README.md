Here is a README file based on the provided information:

---

# House Price Prediction Challenge

Welcome to the House Price Prediction Challenge!

## Hackathon Details

* Hackathon Name: [House Price Prediction Challenge](https://machinehack.com/hackathons/house_price_prediction_beat_the_benchmark/overview)
* Provided By: [MachineHack](https://machinehack.com)
* Profile Link: [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6)
* Rank: 82
* Score: 0.40532

## Overview

This challenge is provided by [MachineHack](https://machinehack.com/). In this competition, you will test your regression skills by designing an algorithm to accurately predict house prices in India. The task involves considering various factors beyond just the size (square feet) of the house to understand the buyer's behavior and determine the house prices. The dataset is collected from various property aggregators across India. You will have the opportunity to explore feature engineering and master advanced regression techniques such as Random Forest, Deep Neural Nets, and various other ensembling techniques.

## Data Description

The dataset consists of the following files:
- **Train.csv**: 29451 rows x 12 columns
- **Test.csv**: 68720 rows x 11 columns
- **Sample Submission**: Acceptable submission format (.csv/.xlsx file with 68720 rows)

### Attributes Description
- **POSTED_BY**: Category marking who has listed the property
- **UNDER_CONSTRUCTION**: Under Construction or Not
- **RERA**: Rera approved or Not
- **BHK_NO**: Number of Rooms
- **BHK_OR_RK**: Type of property
- **SQUARE_FT**: Total area of the house in square feet
- **READY_TO_MOVE**: Category marking Ready to move or Not
- **RESALE**: Category marking Resale or not
- **ADDRESS**: Address of the property
- **LONGITUDE**: Longitude of the property
- **LATITUDE**: Latitude of the property

## Evaluation

The submission will be evaluated using the RMSLE (Root Mean Squared Logarithmic Error) metric. The RMSLE can be calculated using the formula:

```python
np.sqrt(mean_squared_log_error(actual, predicted))
```

The hackathon supports both private and public leaderboards:
- **Public Leaderboard**: Evaluated on 30% of the test data
- **Private Leaderboard**: Evaluated on 100% of the test data and made available at the end of the hackathon

## Participation Details

- **Profile**: [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6)
- **Rank**: 82
- **Score**: 0.40532

## Resources

The following files are included in the repository:
- `Notebook.ipynb`: Jupyter Notebook containing the code and analysis for the competition
- `Train.csv`: Training dataset
- `Test.csv`: Test dataset
- `predictions.csv`: Predictions made on the test dataset

---

Feel free to update or customize this README file further based on your needs!
