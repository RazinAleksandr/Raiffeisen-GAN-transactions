# Raiffeisen_GAN_transactions
Generating new customers transactions based on Raiffeisen dataset
# Clustering
We clustered all customers based on their transactions groupped by day and MCC (Merchant Category Codes). Defined 8 main clusters to help gan model produce new transactions that follow particular pattern. 
# GAN model
We used vanila GAN model with input dim of 53 variables. Compiled model is presented in "Pytorch_GAN". 
