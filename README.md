# Household-Poverty-Level-Prediction

## Problem description

The model predicts whether or not a given household of the given country is poor or not. Survey data is provided at the household level for a country. Each household is identified by its id.

## Data Format

### Training Data

Predictions are made at the household level. There is one train file and one test file in total. Each column in the dataset corresponds with a survey question. Each question is either multiple choice, in which case each choice has been encoded as random string, or it is a numeric value. Many of the MCQs are about consumable goods--for example does your household have items such as soap, oil, etc. Whereas numeric questions ask for some quantitative information from the household.

### Test Data

The test data format is the same as the training data, except that the poor column is not included.
