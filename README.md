# deep-learning-challenge
Training and evaluating neural networks to help select charity applicants to fund with the best chance of success in their ventures.

## Repo Description/Outline:

Using charity data, neural networks are implimented to see if charity applicants will or won't be successful. The process:

### Preprocessing:

- The target is whether or not the venture is successful
- The features are things like affiliation, organization, income amount and amount of money requested
- Features like name and EIN are removed to allow for processing

### Compiling, Training, and Evaluating the Model:

- The best performing model used 3 hidden layers. The first 100 neurons, second 75 neurons, and third 30 neurons. Activation functions for hidden layers were all ReLU.
- Though 3 seperate attempts were made, I was unable to get the model above 75% accuracy
- I attempted adding a 3rd hidden layer and increasing neurons. Both of which did little to increade model accuracy.

Overall the model could be improved further. Perhaps dropping more columns, or increasing the amount of buckets used would help achieve a higher accuracy score. 
Perhaps a logistic regression model could be used to greater effect. The target results are available, and could aid in training a supervised model such as that.


## Notes & Resources:

Dataset used: https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv