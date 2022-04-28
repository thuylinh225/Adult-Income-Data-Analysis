# Adult-Income-Data-Analysis
Introduction
Data
The title of this data is Adult and it's the original owners is US Census Bureau. The donors are Ronny Kohavi and Barry Becker, Data Mining and Visualization Silicon Graphics, e-mail: ronnyk@sgi.com. The adult income data was received on May 19, 1996, it may change over time without name change.

The adult income data is downloaded from: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset?select=adult.csv

As the author of this page:

"This dataset named “adult” is found in the UCI machine learning repository http://www.cs.toronto.edu/~delve/data/adult/desc.html

The detailed description on the dataset can be found in the original UCI documentation http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html "

This dataset has 48,842 entries and each entry contains the following information about an individual:

Attribute Information:
Class Values (Income level): >50K, <=50K

Attributes:
There are 6 continuous, 8 nominal attributes.

age: (continuous) the age of the individual.
workclass: (categorical) the employment status of an individual.
fnlwgt: (continuous) final weight of the record, this is the number of people the census believes the entry represents.
education: (categorical) the highest level of education achieved by an individual.
education-num: (continuous) the number of years of education.
marital-status: (categorical) marital status of an individual.
occupation: (categorical) the general type of occupation of an individual.
relationship: (categorical) Relationship in terms of the family.
race: (categorical) race of an individual.
sex: (categorical) the biological sex of the individual.
capital-gain: (continuous) dollar gain of capital.
capital-loss: (continuous) dollar loss of capital.
hours-per-week: (continuous) working hours per week.
native-country: (categorical) country at birth.
Project Topic
My goal is to predict whether an individual’s income will be greater than $50,000 per year based on several attributes from the adult income data, therefore, it's a classification task. I'll find which features affect the most to income level of each individual by visualizing, running some models and examine which model is the best?

To analyze this data, I would like to make an overview of the solution:

Part 1: Import and Explore data
Part 2: Tidy and Transform data
Part 3: Add Visualization and Analysis
Part 4: Build Models
Part 5: Discussion and Conclusion
