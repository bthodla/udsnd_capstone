# udsnd_capstone
## Udacity Data Science Nanodegree Capstone Project

This project was developed in fulfillment of my Udacity Data Science Nanodegree program.

Although I had several choices of problem spaces to pick from that Udacity provided, I decided to bring one of my own problems to solve using this opportunity.

InvestSure is a fictional investment company that manages the retirement accounts of employees of its customers. It gets a dump of many data elements in CSV and JSON formats from transactional and external systems. It wants me to use this data and build a recommendation engine to suggest funds to its customers based on the funds that they already own and those that are owned by other similar customers.

The project is implemented using the following broad steps:

1. A description of the data used in the project
2. Loading Data
3. Doing Exploratory Data Analysis (EDA)
4. Doing Feature Engineering
5. Making Recommendations
   1. Based on funds already bought by a customer - Content-based Filtering
   2. Based on funds bought by other similar customers - Collaborative Filtering
6. Conclusions
7. Future Directions

The accompanying Jupyter Notebook has detailed explanations of each of these steps. Specifically, it describes all the relevant features that were engineered from the data and the steps that were taken to implement recommendations.

The project is available in GitHub at https://github.com/bthodla/udsnd_capstone and is structured as follows:

* Project Root Folder
  * data: the folder that contains the datasets used in the project in CSV and JSON formats
  * invest_sure.ipynb: The Jupyter notebook that contains all the code for conducting the above steps
  * LICENSE: a BSD-3 Clause License file
  * README.md: this readme file

The following libraries were used in the project:

* Pandas
* Numpy 
* Matplotlib 
* Seaborn

This project was developed using PyCharm 2022.1 (Professional Edition).

