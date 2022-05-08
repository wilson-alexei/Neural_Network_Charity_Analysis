# Neural_Network_Charity_Analysis
With machine learning and neural networks, we will use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded. We will utilize `Scikit-learn` and `TensorFlow`.

## Overview
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

## Results
* Data Preprocessing
  * What variable(s) are considered the target(s) for your model?

  <img width="1102" alt="Screen Shot 2022-05-07 at 21 11 58" src="https://user-images.githubusercontent.com/95068439/167277633-2630f900-4de7-4e86-a30a-e18b0fcc2cec.png">

  * What variable(s) are considered to be the features for your model?

  <img width="600" alt="Screen Shot 2022-05-07 at 21 12 48" src="https://user-images.githubusercontent.com/95068439/167277650-2fc48886-6e25-4c7e-90b0-04628a702f44.png">

  * What variable(s) are neither targets nor features, and should be removed from the input data?
> The variables that are left out and removed for the model are `NAME`, `EIN`, `ASK_AMT` and `STATUS`.

* Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?

<img width="946" alt="Screen Shot 2022-05-07 at 21 18 03" src="https://user-images.githubusercontent.com/95068439/167277761-026456e4-8c1e-4345-8f63-f95ef7131fb7.png">

  * Were you able to achieve the target model performance?

<img width="875" alt="Screen Shot 2022-05-07 at 21 18 39" src="https://user-images.githubusercontent.com/95068439/167277789-b6a1aee3-8d3a-4ff0-bdaa-f50890f6cdc0.png">

  * What steps did you take to try and increase model performance?

> Steps I took to try to increase model performance are adding more layers on `hidden_nodes_layer2` and add `hidden_nodes_layer3` with 20 layers that produces approximately **70.6%** model accuracy

<img width="935" alt="Screen Shot 2022-05-07 at 21 22 29" src="https://user-images.githubusercontent.com/95068439/167277905-14109513-073b-449d-a4b0-d7c4816fc7b3.png">

<img width="872" alt="Screen Shot 2022-05-07 at 21 22 56" src="https://user-images.githubusercontent.com/95068439/167277908-734d1bc7-3253-45d5-b96c-565992d35854.png">

## Conclusion
The optimized model achieved 70.6% accuracy by increasing layers to Hidden Nodes Layer 2 and add Hidden Nodes Layer 3. Recommendations to improve the model accuracy are increasing layers in Hidden Nodes 3 or changing the activation functions. We can try Tanh or Linear and hopefully have an improved results. 


> LinkedIn: https://www.linkedin.com/in/wilson-alexei/

> Email: wils.alexei@gmail.com
