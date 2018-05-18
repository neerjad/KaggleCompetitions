# KaggleCompetitions
A repo with codes for the Kaggle competitions I have participated in.

## Understanding this repo:
The folders contain codes corresponding to the competitions I have participated in. 

Disclaimer: Some of the codes are entirely mine, while in the others I have taken inspiration from others Kaggle kernels. I will point this out where I have pushed other's codes.

## Repo Structure:
01-TextNormalisation: 

Competition - https://www.kaggle.com/c/text-normalization-challenge-english-language
Codes - 
1. xgboost_class_predictions.ipynb: a modification of LiYun's code. It used XGBoost to predict the type of word. 
                                    Eg. cardinal, ordinal, measurement, etc.
2. Create_function_classes.ipynb: My code where I have created functions to handle words according to their type with the help of regular expressions. These functions take care of roman-to-integers, date/time, telephone numbers, etc.
                                  Then, pass the words in the test set along with their type to these functions to generate predictions.
                        
You can also find my kernel that shows treatment of these 'classes' here: https://www.kaggle.com/neerjad/class-wise-regex-functions-l-b-0-995

Stay tuned for more competition codes as this repo is still WIP.
