# Starbucks Capstone Project | Udacity - ML Engineer Nanodegree

## Overview

Our goal is to analyze historical data about the offers transacted by the customers and develop
an algorithm that can improve the conversion rate of the offers and thereby increase the overall
profit.
We will use the dataset which has been provided by Starbucks for this task.

## Datasets

The data is contained in three files:
- **portfolio.json** - containing offer ids and meta data about each offer (duration,
type, etc.)
- **profile.json** - demographic data for each customer 
- **transcript.json** - records for transactions, offers received, offers viewed, and
offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
- id (string) - offer id 
- offer_type (string) - type of offer ie BOGO, discount, informational 
- difficulty (int) - minimum required spend to complete an offer 
- reward (int) - reward given for completing an offer 
- duration (int) - time for offer to be open, in days 
- channels (list of strings)

**profile.json**
- age (int) - age of the customer 
- became_member_on (int) - date when customer created an app account 
- gender (str) - gender of the customer (note some entries contain 'O' for other
rather than M or F)
- id (str) - customer id 
- income (float) - customer's income

**transcript.json**
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id 
- time (int) - time in hours since the start of the test. The data begins at time t=0 
- value - (dict of strings) - either an offer id or transaction amount depending on the
record

### Files
The following files are important references for this project.
- [Notebook.ipynb](https://github.com/schatterjeecs/capst_recomendation/blob/master/Starbucks_Capstone_notebook_actual.ipynb)
- [Project Proposal](https://github.com/schatterjeecs/capst_recomendation/blob/master/Capstone_Proposal.pdf)
- [Datasets](https://github.com/schatterjeecs/capst_recomendation/tree/master/data)

## Acknowledgements
Special Thanks to Starbucks and Udacity for providing the datasets and facilitating this project.

