# Fraud-Detection-with-Auto-Encoder-v1.0

how it is possible that neural network which is used for recontruction of input values can be used as a classifier 
for fraud transcations

so answer to this curiousity is very simple
as we know autoencoder is useful for reconstruciton of values
but if I train it on non-fraudulent transaction then it will be able to contruct non-fraudlent only
so if I pass fraudulent transaction with non-fraudulent one then mse will be high for fraud transaction one
why because it's weight are made on the basis of non-fraudulent transaction
then at last I will decide a perfect threshold for classify fraudulent vs non-fraudulent transaction

### for big thing to watch pls see my notebook
