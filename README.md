# Lotto-Max-Predictor

## Preclaim

***Just for Fun!***

## Introduction
This program uses a random forest regression model to predict the numbers in the next lottery list based on historical data. The program takes as input a list of previous lottery lists, and outputs a list of predicted numbers for the next list.

## Code
The code first prepares the data by extracting features from previous lists of numbers and converting them into a feature matrix X and a target vector y. The random forest regression model is trained on the prepared data, and then used to predict the next list of numbers based on the current date.

The resulting predicted list of numbers is printed out at the end of the code.


## Requirements
The code utilizes the following packages:

- `datetime` to work with dates and times.
- `numpy` for numerical computing.
- `sklearn` to build and train the random forest regression model.

## License

This work is licensed under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0) (or any later version). 

`SPDX-License-Identifier: Apache-2.0-or-later`

## Author

Zeyong Jin

February 17th, 2023



