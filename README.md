# Lab 2: Sampling, Data Wrangling, and Visualization

## Project Overview

This project addresses a variety of statistical problems using R, focusing on sampling, data wrangling, and visualization. It includes two primary sections: **simulating business strategies** for maximizing profits in a rollup sales scenario, and **scraping and analyzing data** on notable female scientists from Wikipedia. The project demonstrates proficiency in using R for simulation, data extraction, and visualization, and aims to answer complex questions by combining these techniques.

## Objectives

- **Profit Simulation**: Simulating various business strategies for maximizing profits from rollup machine sales over 30 days.
- **Data Extraction**: Scraping Wikipedia data to analyze notable female scientists in the 20th century.
- **Visualization**: Creating graphs to visualize data distributions, including histograms, word clouds, and bar plots.

## Key Features

### 1. Rollup Profit Simulation

This section models a scenario where a rollup manufacturer starts with one machine and simulates profits over 30 days under different investment strategies. The tasks involve simulating the rollup manufacturing process using Poisson distributions and analyzing profit distributions for different strategies:

1. **All-in Investment Strategy**: Simulating the scenario where all profits are reinvested into buying new machines until the last day.
2. **No Investment Strategy**: Simulating the profit distribution where no new machines are purchased, and all sales come from a single machine.
3. **Random Investment Strategy**: Introducing randomness by buying a random number of machines each day based on current profits.
4. **Partial Investment Strategy**: Analyzing the optimal day to stop reinvesting profits to maximize expected final profit.
5. **Bonus Question**: Proposing and simulating an optimal strategy to maximize profits.

### 2. Female Scientists Data Extraction and Analysis

In this section, data is scraped from the Wikipedia page on notable female scientists of the 20th century. The data includes names, birth and death years, nationalities, and occupations. Additionally, biographical texts are extracted and analyzed.

1. **Scraping Scientist Data**: Using the `rvest` package to extract the names, birth and death years, nationalities, and occupations of notable female scientists.
2. **Field of Study and URLs**: Extracting the scientists' fields of study and constructing URLs to each scientist’s biography page on Wikipedia.
3. **Text Parsing**: Writing a function to parse the biographies of scientists, excluding references, and measuring the length of the biographies.
4. **Biographical Data Analysis**: Finding the shortest and longest biographies for each field of study and displaying them in separate tables.
5. **Word Frequency Analysis**: Retrieving the words from the biographies and displaying a word cloud of the most common words, excluding stopwords and special characters.
6. **Length Distribution Analysis**: Displaying the distribution of biography lengths and word lengths for each field in separate bar pl
