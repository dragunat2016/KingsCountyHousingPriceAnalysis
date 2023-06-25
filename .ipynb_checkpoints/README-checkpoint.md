{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# King's County House Prediction Project"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Repository Navigation\n",
    "\n",
    "This repository contains the following information\n",
    "\n",
    "* Jupyter [notebook](index.ipynb)\n",
    "* [presentation](presentation.pdf)\n",
    "* [Data Set](data/kc_house_data.csv)\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Project Goal\n",
    "<hr>\n",
    "\n",
    "The goal of this project is to predict house sale prices in King's County Washington."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Data Source and Data Exploration\n",
    "<hr>\n",
    "\n",
    "* The data source is from King's County House sale prices in csv format. This data contains records of houses sold in King's county with variables such as the price, bedrooms, bathrooms, view etc.\n",
    "\n",
    "\n",
    "* Data use: This dataset can be used to create models that help predict prices of houses in King County.\n",
    "\n",
    "\n",
    "* Size of Data: The dataset has 21597 records and 21 columns.\n",
    "\n",
    "\n",
    "* Data Limitations: This data set is limited by the amount of variables recorded during the house sale. There are other key points to consider when evaluating a potential sale price such as quality of the school districts, noise in the area, etc."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Methods\n",
    "<hr>\n",
    "* Linear Regression was used to determine the relationship between the variables and house sale price.\n",
    "\n",
    "\n",
    "* Linear Regression allows us to quantitatively estimate the change in sales price from a change in a variable.\n",
    "\n",
    "\n",
    "* The model can estimate how much a house will sell for in a zip code, with a certain amount of square footage, and a given view.\n",
    "\n",
    "\n",
    "* We will use a parameter called R-squared to measure the efficacy of the model: R-Squared \n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Results\n",
    "<hr>\n",
    "\n",
    "* Higher square footage is generally correlated with higher sale prices.\n",
    "* Better views are correlated with higher sale prices.\n",
    "* The following areas tend to positively impact the sale price: 98039, 98004, 98112, 98040, 98012, 98019, 98119, 98105, 98199, 98033, 98122, 98107"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python (learn-env)",
   "language": "python",
   "name": "learn-env"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
