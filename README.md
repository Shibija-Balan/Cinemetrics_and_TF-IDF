# CineMetrics: Audience Behaviour and Text Analytics

An R-based data science project analysing movie viewing behaviour, audience ratings, engagement patterns and review text. The analysis combines data wrangling and exploratory analysis with sentiment analysis and TF-IDF text mining.

## Project overview

The project joins viewing-history, user and movie-title datasets into a single analytical table and investigates how genre, budget, subscription type and age relate to audience behaviour. It then extends the analysis to unstructured review text using tokenisation, lexicon-based sentiment scoring and TF-IDF.

## Methods

- Data cleaning, de-duplication and multi-table joins with `tidyverse`
- Missing-value analysis and categorical feature consolidation
- Grouped summaries and distributional analysis
- Confounding analysis and Simpson's paradox
- Tokenisation and stop-word removal with `tidytext`
- Bing lexicon sentiment analysis
- TF-IDF for genre-distinctive vocabulary
- Data visualisation with `ggplot2`

## Selected findings

- Production budget alone did not explain audience ratings. In this dataset, Horror had a substantially lower average budget than Sci-Fi while receiving a higher average user rating.
- Subscription-level averages were confounded by age. Premium users appeared more engaged overall, but Basic users had higher average engagement within every age tier, demonstrating Simpson's paradox.
- Lexicon sentiment did not always align with audience ratings. Horror reviews produced relatively negative sentiment scores despite high user ratings, illustrating the limitations of context-free sentiment dictionaries for genre-specific language.
- TF-IDF was more useful than raw frequency for identifying genre-distinctive vocabulary because generic terms such as "film" were downweighted when they appeared across all genres.

## Repository structure

- `coursework_01.qmd` — source analysis in Quarto/R
- `coursework_01.md` — rendered GitHub-friendly report
- `coursework_01_files/` — generated figures and supporting render files
- `data/` — datasets used by the analysis
- `coursework_01.Rproj` — RStudio project file

## Tools

R, tidyverse, tidytext, ggplot2, knitr

## Notes

This project was originally developed as university data science coursework and has been cleaned for portfolio presentation. The analysis is observational: reported relationships are descriptive and should not be interpreted as causal effects.
