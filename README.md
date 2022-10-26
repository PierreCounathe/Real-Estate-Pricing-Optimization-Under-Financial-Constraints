# Real-Estate-Pricing-Optimization-Under-Financial-Constraints
This repository contains a high-level description of a Pricing Optimization project in Real Estate (RE). The scope of this project ranges from data scraping, to single-point market value prediction for RE assets, to time-on-market or time-to-sell prediction given a price, to price optimization.

The work and results are summarized in [](). Below, we list and briefly describe the project's modules.

## Project modules

**1. Data Scraping**

Information about listed properties in NYC (features, size, location, history of listing prices, etc.) was first gathered by scraping the main real-estate marketplaces such as Zillow and Streeteasy. As these websites reinforced their security during summer 2021, mock drivers created by `selenium` would have gotten kicked-out quickly. The srcaping was thus done with `beautifulsoup` by infering search results URLs, gathering all listings URLs, and fetching their characteristics.


**2. Data Analysis**

A study of the statistical properties of listings characteristics in NYC's neighborhoods showed us that narrowing the project scope to the Upper East and West Side would allow us to have enough data points and to make the assumption that the real-estate market was an homogeneous marketplace.
