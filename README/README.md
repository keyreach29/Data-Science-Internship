# Data-Science-Internship
Project on Data Science Internship at Cognifyz Technology
# Restaurant Analysis Project

This project is an analysis of a restaurant dataset, focusing on various aspects such as geospatial distribution, availability of table booking and online delivery, and correlations between these features and restaurant ratings.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Accessing the Notebook](#accessing-the-notebook)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
  - [Geospatial Analysis](#geospatial-analysis)
  - [Distribution Analysis](#distribution-analysis)
  - [Feature Correlation Analysis](#feature-correlation-analysis)
  - [Service Availability Analysis](#service-availability-analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to provide insights into restaurant data, including:
- Visualizing the locations of restaurants on a map
- Analyzing the distribution of restaurants across different cities and countries
- Determining the correlation between restaurant locations and their ratings
- Comparing the availability of table booking and online delivery services
- Analyzing the availability of online delivery among restaurants with different price ranges

## Dataset

The dataset used in this project contains the following columns:
- `Restaurant ID`: int64
- `Restaurant Name`: object
- `Country Code`: int64
- `City`: object
- `Address`: object
- `Locality`: object
- `Locality Verbose`: object
- `Longitude`: float64
- `Latitude`: float64
- `Cuisines`: object
- `Average Cost for two`: int64
- `Currency`: object
- `Has Table booking`: bool
- `Has Online delivery`: bool
- `Is delivering now`: bool
- `Switch to order menu`: bool
- `Price range`: int64
- `Aggregate rating`: float64
- `Rating color`: object
- `Rating text`: object
- `Votes`: int64

## Accessing the Notebook

You can access and run the analysis directly in your browser using Google Colab:
[Restaurant Analysis Notebook](https://colab.research.google.com/drive/1U7CUO2Oo8O56T9mPNDp1AYtF4ULVbPHK?usp=sharing)

## Installation

To run the notebook locally, you need to have Python installed along with the following libraries:
- pandas
- folium
- matplotlib
- seaborn

You can install the required libraries using the following command:

```bash
pip install pandas folium matplotlib seaborn

Usage
Clone the repository and navigate to the project directory:
git clone https://github.com/keyreach29/restaurant-analysis.git
cd restaurant-analysis

Analysis
Geospatial Analysis
Visualize the locations of restaurants on a map using latitude and longitude information.

Distribution Analysis
Explore the distribution of restaurants across different cities and countries.

Feature Correlation Analysis
Determine if there is any correlation between the restaurant's location and its rating.

Service Availability Analysis
Calculate the percentage of restaurants that offer table booking and online delivery.
Compare the average ratings of restaurants with table booking to those without.
Analyze the availability of online delivery among restaurants with different price ranges.
Results
The analysis results are displayed in the notebook and visualized using plots.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

Author~ Mike Kerich
Medium channel: https://medium.com/@mkibekerich14