# A simple use case for machine learning

The following challenge is a typical machine learning practice. It takes place in several steps:

    Exploring and cleaning the data
    Generating usable features
    Visualisation
    Models, train set and test set
    Robust model

**About the data set:**

The data set (imaginary data) concerns the assurance of credit cards, which protects against death, disability, loss of employment and critical illness. The csv file is build of 500000 samples (rows). Each row corresponds to one account with 12 features and one label.

Features:

    ID (integer): account ID
    credit_used (integer): Monthly credit used
    limit_allowed (integer): The limit of credit to use by costumer
    credit_score (float): A score gived by credit office
    nb_days_account_open(float): Number of days between the account open date and today
    interests (float): Previous interests that must be paid
    loyalty (float): Quantity of loyalty points accumulated
    card_change(integer): Has the credit card type changed in the past? (1=yes, 0=no)
    age (float)
    nb_costumers (integer): numbers of costumers per account
    reward (char): Reward given by credit card
    name_card (string): name of card type

Label

    inssurance (string): name inssurance ('No' means no inssurance)

This is a supervised machine learning problem. The task of this challaenge is to make prediction of wich of account will takes an insurance plan.
