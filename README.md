<h1 align="center">Basic Accommodation Comparisons in Seattle and Boston</h1>

## Table of contents

- [Description and Facilities](#Desc-inst)
- [Motivation](#Motivation)
- [Description of files](#Desc-files)
- [Interacting with the project](#Interact)
- [Acknowledgments]("#Acknowledgments)

## Description and Facilities
The code is set in the Python programming language. The ability to be executable both on the colab platform and in a Jupyter notebook is presented.

For its correct execution, the following modules must be installed:
- numpy
- pandas
- matplotlib
- sklearn
- seaborn
- Python version: 3.10.12

## Motivation
For exchange reasons, work reasons or purely for leisure and wanting to rest and see places, it is important to think about the place where you will spend the night. The hosts, owners of said lodgings, are therefore interested in this detail in order to be able to have guests.

For the host, one of the main questions would be: What are the characteristics that guests value most to feel comfortable in an accommodation? How can I improve the guest experience in order to gain trust so that the accommodation welcomes more and more?

For the guest, the question may be what factors may be potential for an increase in the value of a lodging.

Personally, I don't usually travel much, therefore I don't know much about the subject, but it is of particular interest given that understanding this type of behavior from now on will leverage future decisions regarding vacations, business trips or study opportunities. This, plus the curiosity that this work generates in order to support the delivery of tools and insights that allow us to improve these services.

## Description of files
Regarding databases, in the repository you can find:
- [listings.csv](listings.csv) Contains information regarding descriptions of Seattle accommodations, as well as descriptions of guest experience and ratings, among other aspects of interest. The information was collected from the platform [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle/data).
- [listings_BOS.csv](listings_BOS.csv) It contains information regarding descriptions of accommodations in Boston, as well as descriptions of the experience and ratings of guests, among other aspects of interest. The information was collected from the platform [Kaggle](https://www.kaggle.com/datasets/airbnb/boston).

As for code, the file [Project_1_Airborn_SyB.ipynb](https://github.com/jdiazbeta/00_DataSciente_Proj_Rep/blob/a5484dc4ed7933d70d13f0edaa3afb6f213d9cad/Project_1_Airborn_SyB.ipynb) contains the code made to carry out the analysis.

## Interacting with the project
The project is designed to give a first outline of a large project that allows us to understand, from the perspective of both guest and host, the main characteristics when choosing accommodation ranging from the price, its characteristics and even potential. improvements given its geographical location.

This notebook can be downloaded to work locally or from Google Colab.

Basic data imputation techniques are used, as well as a very brief descriptive - exploratory analysis. Likewise, the Skit-Learn library is used to create a multiple linear regression model to understand the potential variables that significantly impact the accommodation price.

As of July 8, 2024, the code is functional, and very available for use and improvement, this is only the first version, made as an initial exploration. I invite you to improve it for future work by providing new perspectives, from debugging and descriptive analysis to models that are of interest.

## Acknowledgments
I want to express my deep gratitude to the following platforms and communities for their invaluable support and resources that made this project possible:

UDACITY: For providing the knowledge and tools, as well as practical scenarios that increase my interest in data science.
Kaggle: For providing robust data sets that allowed the completion of this project, as well as increasing my interest in data science.

Additionally, I am grateful to all those who have directly or indirectly contributed to this work through comments, suggestions, and shared resources.












