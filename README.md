# Fred Analysis: The US economy Project

## Introduction

Welcome to the Fred Analysis: The US economy Project! This project is designed to explore and analyze economic data from the Federal Reserve Economic Data (FRED) using Python. The goal is to provide insights into various economic indicators such as GDP, unemployment rates, and international trade activities across the United States.

## Project Overview

This project consists of several key components:

1. **Economic Data Collection**: I utilize the FRED API to fetch economic data related to GDP and unemployment rates across different states in the US, as well as data on US imports and exports.

2. **Data Cleaning and Transformation**: The raw data pulled from FRED is processed to improve readability and usability. This includes renaming series identifiers to state names, dropping unnecessary columns, mapping state names, sorting datasets, and handling missing values.

3. **Data Analysis and Visualization**: I conduct a detailed analysis of the collected data. This involves plotting the GDP data for visual comparison and investigating the relationship between the GDP and unemployment rates. Additionally, I analyze how US GDP is influenced by international trade by examining import and export data.

## Key Features

- **GDP Analysis by State**: Analyze and visualize the Gross Domestic Product (GDP) for each state in the US, providing insights into regional economic health.
  
- **Unemployment Trends**: Explore unemployment rates alongside GDP to understand economic conditions and labor market dynamics across states.
  
- **Impact of International Trade on US Economy**: Assess the effects of imports and exports on the overall GDP of the United States from 2020 to 2024.

## Technologies Used

This project leverages Python libraries such as `matplotlib` for plotting, `pandas` for data manipulation, and `requests` for API interactions.

## Getting Started

To run this project, ensure you have Python installed along with the necessary libraries. You will also need an API key from FRED, which you can obtain by registering on their website.
