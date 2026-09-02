# Efficient Home Data

This repository hosts the centralized `regions.json` data file used by the **Government Resource Selector** tool on [An Efficient Home](https://anefficienthome.com).

## Purpose
The JSON file maintains a structured, hierarchical database of geographic locations (countries, states, counties, and cities) mapped to their corresponding government authorities, building departments (AHJs), and utility efficiency incentives. 

## How It Works
Your WordPress site fetches this `regions.json` file dynamically via JavaScript whenever a visitor uses the regional dropdown selector on your site, allowing for zero-maintenance updates whenever new cities or resources are added to the file.
