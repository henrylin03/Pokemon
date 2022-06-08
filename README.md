# Pokemon Data Analysis
<p align="center">
    <img width="500" src="https://external-preview.redd.it/NXrR_qnMRHrwUoE8pbeiX26fq4mNctFsmdEghRVApSQ.jpg?auto=webp&s=b18e1b0df84f417036d4e1ac0affb6245a071ebf">
</p>

## Description
Like many, Pokemon was an intimate part of my life; collecting trading cards, watching the anime, and playing the videos games. Motivated by this, in this Project, I analyse Pokemon data across the 6 Generations. 

I seek to answer questions such as:

* What are the strongest Pokemons in each Generation?
* Have Pokemons become more overpowered with each Generation?
* Is there a relationship between Pokemons' types and their strength?

The data is originally sourced from [Kaggle](https://www.kaggle.com/abcsds/pokemon).

## How to View
All code is within the `pokemon_eda.ipynb` Jupyter Notebook. 

The input `.csv` is within the `/input` subfolder.

## What Was Used
This project is driven by Python in a Jupyter environment. The libraries I use are listed below:

| Library      | Use                                                                  |
| ------------ | -------------------------------------------------------------------- |
| Pandas       | Loading, cleaning, and displaying data in DataFrames                 |
| SQL (SQLite) | Querying data to produce tables                                      |
| SQLalchemy   | Create SQL engine that interprets SQL commands to query input `.csv` |
| Matplotlib   | Data visualisation                                                   |
| Seaborn      | Data visualisation                                                   |