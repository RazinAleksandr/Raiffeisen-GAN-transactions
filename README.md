# Raiffeisen-GAN-transactions
Implementing hypotheses about what external data might affect consumer activity in different categories among customers. Simulating the behavior of bank customers using a generative-adversarial neural network based on Raiffeisen dataset.
## Clustering
We clustered all customers based on their transactions groupped by day and MCC (Merchant Category Codes). Defined 8 main clusters to help gan model produce new transactions that follow particular pattern. 
## Data parsing
In this case, we grouped consumer transaction types into the following categories: food, clothing, housing, health, beauty, money, transportation, children, non-food, telecommunications, entertainment, charity, and others.
We parsed the following data from open external sources to replenish the basic dataset: weather data, longitude and latitude using the geopy library, currency rates, statistics of salaries in Russia, full names of cities.
This allowed us to create more complete connections between the attributes. You can view the parsing code in the file.
## GAN model
We used vanila GAN model with input dim of 53 variables. Compiled model is presented in "Pytorch_GAN". 
