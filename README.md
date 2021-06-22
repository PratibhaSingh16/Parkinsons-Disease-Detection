# Parkinson's Disease Detection

![1](https://user-images.githubusercontent.com/77543839/122868080-744f2b80-d2f8-11eb-9227-34648a75b264.jpeg)



Parkinson's disease is a brain disorder that leads to shaking, stiffness, and difficulty with walking, balance, and coordination.
Parkinson's symptoms usually begin gradually and get worse over time. As the disease progresses, people may have difficulty walking and talking. 
They may also have mental and behavioral changes, sleep problems, depression, memory difficulties, and fatigue.
Both men and women can have Parkinson’s disease. However, the disease affects about 50 percent more men than women.

# What Causes Parkinson's Disease?
Parkinson's disease occurs when nerve cells, or neurons, in an area of the brain that controls movement become impaired and/or die. Normally, these neurons produce an important brain chemical known as dopamine. When the neurons die or become impaired, they produce less dopamine, which causes the movement problems of Parkinson's. Scientists still do not know what causes cells that produce dopamine to die.


# Detection of Parkinson's Disease using Machine Learning tools:

I have used Parkinson's dataset which was created by Max Little of the University of Oxford in
collaboration with the National Centre for Voice and Speech, Denver,
Colorado, who recorded the speech signals.

This dataset is composed of a range of biomedical voice measurements from
31 people, 23 with Parkinson's disease (PD). Each column in the table is a
particular voice measure, and each row corresponds one of 195 voice
recording from these individuals ("name" column). The main aim of the data
is to discriminate healthy people from those with PD, according to "status"
column which is set to 0 for healthy and 1 for PD.

# Process:

I used dataset, applied Python skill to:
- Assign required features and labels for classification S
- Split data into Training and Testing variables
- Used Decision Tree for classification, fitting the modle for Machine to learn
- Prediction on Test variables
- Confusion matrix to see type 1 and type 2 errors
- Random forest for particular feature selection
- Gridsearch applies particular parameter for decision tree
- Fitting the data for machine to learn
- Finding best parameters for classification
- Predicting values based on random forest

# Result:

After following the processes, we had our p=model predicting the chances of getting infected with Parkinson's Disease, and our model had 87.9% of prediction accuracy.

# Dataset:

https://www.kaggle.com/nidaguler/parkinsons-data-set
