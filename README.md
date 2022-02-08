# Neural Network Charity Analysis

## Overview of the Analysis
The goal of this challenge was to predict which organizations qualify to receive a donation from the non-profit organization called Alphabet Soup. Creating a mathematical data driven solution that can predict this decisions, a neural network was implemented to evaluate all types of input data and output a clear decision making result for the company. Finally, a dataset containing names of the companies, successful money handling, and all the necessary data; was given to the user to work with the neural network.

## Results
This space shows the results obtained from the implementation of a neural network in the dataset of the charity dataset provided. To demonstrate the results in a more orderly way, they are going to be divided into small sections for better evidence.

- **Data Preprocessing**
  - **Target Variables**:The target data was the "IS_SUCCESSFUL" column, which is displayed with a binary format. This column means if the money was used effectively.
  - **Featured Variables**: The following columns were considered features to be used as input parameters in the nerual network model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, ASK_AMT.
  - **Irrelevant Variables**:The dataset contained the identification numbers and names of the organizations asking for funding. These variables were considered irrelevant to the neural network.

- **Compiling, Training, and Evaluating the Model**
  - Relu Activation function was implemented at first to the model, this was due to the complexity of the dataset. After that, two layers were created. The first included 18 neurons, as there 9 features within the dataset. An additional layer was added with 9 neurons using the "Rule of thumb" law.
  - The target model performance was not achieved propertly (75%), this was due to the number of neurons and hidden layers specified by the user during the compilation of the model, giving the result of 72.6%. 
  - To increase the performance, An auto optimzer function was created to calculate the best combination of layers and neurons with the optimal activation function. The result only increased the accuracy by 0.2% giving in a final accuracy of 72.8%.
  
## Summary
In conclusion, the final result obtained was 72.8% precision for the evaluated model. This number is due to the fact that, due to time and resource limitations, no further optimization attempts could be made for the model. It is recommended in the future to increase the number of neurons in the network and the hidden layers to increase the accuracy of the algorithm.
