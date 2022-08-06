#### tabular-playground-series-aug-2022

# **Tabular Playground Series - Aug 2022**

##### Help the fictional company Keep It Dry improve its main product: Super Soaker

The August 2022 edition of the Tabular Playground Series in an opportunity to help the fictional company Keep It Dry improve its main product *Super Soaker*. The product is used in factories to absorb spills and leaks.

The company has just completed a large testing study for different product prototypes. We will use this data to build a model that predicts product failures?

### **Data Description**

This data represents the results of a large product testing study. For each ```product_code``` a number of product ```attributes``` (fixed for the code) as well as a number of ```measurement``` values for each individual product, representing various lab testing methods. Each product is used in a simulated real-world environment experiment, and and absorbs a certain amount of fluid (```loading```) to see whether or not it fails.

The task is to use the data to predict individual product failures of new codes with their individual lab test results.

### Files

- **train.csv** - the training data, which includes the target ```failure```
- **test.csv** - the test set; your task is to predict the likelihood each ```id``` will experience a failure
- **sample_submission.csv** - a sample submission file in the correct format

Access the 7.21 MB dataset using Kaggle API:
```console
kaggle competitions download -c tabular-playground-series-aug-2022
```

