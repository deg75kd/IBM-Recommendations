# IBM Recommendations

## Table of Contents

* [Summary](#summary)
* [File Descriptions](#file-descriptions)
* [Prerequisites](#prerequisites)
* [Running the Code](#running-the-code)
* [Results](#results)
* [Built With](#built-with)
* [License](#license)

## Summary

This project was part of the Udacity Data Science Nanodegree.  In it I use FunkSVD matrix factorization to generate recommendations based on past user interactions with articles on the IBM Watson site.  The project begins with exploratory data analysis of user interactions.  Then I built a method to produce rank based recommendations.  Next I employed user-user based collaborative filtering.  Finally, I use matrix factorization to produce recommendations and test the effects of different numbers of latent features.

## File Descriptions

* Recommendations_with_IBM.ipynb - Jupyter notebook of my work
* Recommendations_with_IBM.html - Notebook saved as html
* project_test.py - Validation tests provided by Udacity
* top_10.p - Top 10 results provided by Udacity for validation
* top_20.p - Top 20 results provided by Udacity for validation
* top_5.p - Top 5 results provided by Udacity for validation
* user_item_matrix.p - user-item matrix provided by Udacity
* data/articles_community.csv - data on articles
* data/user-item-interactions.csv - user-item interaction data

## Prerequisites

Pyhon
Pandas
Numpy
Matplotlib
Pickle

## Running the Code

Open Recommendations_with_IBM.ipynb in Jupyter Notebook and run all cells.

## Results

Due to the way the train/test split was created there was not much overlap.  Thus testing the results of different numbers of latent features produced unexpected results.  I proposed an alternative solution of conducting an A/B test on the web site using different numbers of latent features to get a practical view into their effectiveness.

## Built With

* [Jupyter Notebook](https://jupyter.org/) - Web application for running Python code

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
