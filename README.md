## Olist Brazil ecommerce Data Analysis and Visualization


### Table of Contents
- [Project Overview](#project-overview)
- [Implementation details](#implementation-details)
- [Project Organization](#project-organization)


### Project Overview

Olist is an online marketplace in Brazil. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

The dataset is taken from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and contains information about 100K oreders from 2016 to 2018 made at multiple marketplaces in Brazil. This is real commercial data that has been anonymized.

In this project, we will do EDA (Exploratory Data Analysis) on the dataset provided, and clean the data such that we can answer the following questions:

- What was the sales performance of Olist in 2017-2018?
- What does the data tell us about customer satisafaction? Are there any specific areas that we should pay attention to?
- What is the relationship between seller location and buyer location?

### Implementation details

- The data cleaning is done in a Jupyter notebook.
- Visulizations for sales performance and product reviews are done using Tableau and can be viewed on [Tableau Public here](https://public.tableau.com/app/profile/anamika.lal/viz/Olist_ecommerce_data_analysis/Olist_Sales_And_Product_Reviews_Dash)


### Project Organization

* `data`
    - `raw` folder contains the relevant data copied from Kaggle.
    - `interim` folder contains any intermediate files.
    - `final` folder contains the csv file after cleaning and feature engineering.

* `notebooks`
    - `1-EDA-Cleaning.ipynb` - Cleaning the dataset.

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license
