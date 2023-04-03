Deep Learning Project: Charity Funding

Deep learning and neural networks were used to predict if applicants would be funded by Alphabet Soup.

Pre-Processing
The EIN and NAME categories were dropped from the model.  The remaining information was filtered by APPLICATION_TYPE to create a cutoff at 500 with all Application Types with less than 500 being classified as Other.  The same was done for CLASSIFICATION counts, however, the value used was > 1.

The X and y were set using IS_SUCCESSFUL as our y variable and the remaining features as the X variables.

The data was split in to train and test functions and the model was evaluated with two hidden layers with 80 and 30 neurons respectively.  This model determined the accuracy to be ~73%.


Modifications were made to the model to add additional hidden layers with varying neurons, however there was no progress made as the model typically ended up at the same accuracy of around 73%.



