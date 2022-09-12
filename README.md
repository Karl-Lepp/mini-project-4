# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
The goal of this project is to implement and delpoy a model to a cloud that can be called upon.  The model is used to predict whether someones loan will be approved.

## Hypothesis
I believe that the total income will be the main factor in determining whether or not a loan is approved.

## EDA 
Of all the data we where given, msot was complete though Credit History and self employed had the most amount of null values.  Both of these were filled assuming they had no credit history/they werent self employed.  Other missing values were filled such as gender being assumed to be man, as majority of applicants were male and loan amount filled as the average for the gender and loan amount.


## Process
### Step 1
Exploring the initial data I plotted several graphs that showed a rough linear relationship between Income and the amount of the loan.
### Step 2
Cleaned Data into numerical form that we can place into a model.
### Step 3
Ran Model
### Step 4
Transformed Step 2 and 3 into pipline
### Step 5
Hosted Model
## Results/Demo
The model performed well with around 79% accuracy.  

## Challanges 
The biggest Challenge for this project was setting up the pipeline. I had done cleaning without pipeline in mind and was difficult to combine all steps, mainly with getting the df transformation into the pipeline.

## Future Goals
The biggest issue I see with the model is the lack of training data that we can use, only having ~600 points to train it.  In respect to my individual project I would like to have clean up and optimize pipline.
