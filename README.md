# Life Expectancy, Income, and Health Spending Across Countries

[![Data Source](https://img.shields.io/badge/Data-World%20Bank%20WDI-orange?style=flat)](https://datacatalog.worldbank.org/search/dataset/0037712)

Cross-country development-economics project exploring how life expectancy relates to income and health spending using World Bank data.

This repository is structured as a portfolio-ready Quarto project. It frames a real-world question, uses internationally comparable data, and turns that analysis into a public-facing research workflow.

## Project Snapshot

- Topic: Life expectancy and development outcomes
- Coverage: Global cross-country data
- Time period: 2000-2023
- Data source: World Bank World Development Indicators
- Core variables: life expectancy, GDP per capita, health expenditure
- Tools: R, WDI, tidyverse, ggplot2, Quarto

## Research Question

How do differences in income and health spending relate to life expectancy across countries?

This project focuses on a classic development-economics question: why do some countries achieve much better health outcomes than others, and how closely are those outcomes tied to economic resources and health-system investment?

## Why This Project Matters

Life expectancy is one of the clearest summary indicators of human development. It sits at the intersection of economics, public policy, public health, and inequality.

For an economics portfolio, this repo shows the ability to:

- work with international development data
- formulate a policy-relevant research question
- retrieve and clean multi-country data in R
- compare countries across regions and income groups
- communicate analysis through a reproducible website

## Data

Source: World Bank World Development Indicators (WDI)

Indicators used in the current project structure:

- `SP.DYN.LE00.IN`: Life expectancy at birth, total (years)
- `NY.GDP.PCAP.CD`: GDP per capita (current US dollars)
- `SH.XPD.CHEX.GD.ZS`: Current health expenditure (% of GDP)

The Quarto source files are designed to analyze:

- cross-country differences in the most recent year
- regional patterns in health and development
- longer-run movement by income group from 2000 to 2023

## Current Project Structure

This repo now includes a lightweight analysis scaffold:

- `index.qmd` for the main analysis page
- `sources.qmd` for indicator definitions and data notes
- `about.qmd` for project context
- `_quarto.yml` for website configuration
- `styles.css` for basic presentation

## Analytical Approach

The current source project is exploratory rather than causal. It is built to:

- download WDI data directly in R
- clean the cross-country sample
- visualize life expectancy against GDP per capita
- compare average life expectancy across income groups over time

This makes the repo a strong starting point for future extensions such as:

- inequality-focused comparisons
- regional case studies
- panel regressions
- policy discussions around health investment and development

## Portfolio Value

This repo strengthens an economics CV because it demonstrates a development question with real data, not just a list of software skills.

A concise CV description for this project could be:

> Built a cross-country development-economics project using World Bank WDI data to examine how life expectancy relates to GDP per capita and health spending, with a reproducible Quarto workflow in R.

## Reproducibility

Install the required R packages:

```r
install.packages(c("WDI", "tidyverse", "ggplot2", "scales", "knitr"))
```

Then render the site locally with Quarto.

## Author

Faran Abbas
Graduate Student, World Economy, Shandong University

- Email: [faranabbas@hotmail.com](mailto:faranabbas@hotmail.com)
- GitHub: [faranabbas-repo](https://github.com/faranabbas-repo)

## Acknowledgment

This project is part of a broader effort to build a stronger economics portfolio with real-world data projects.
