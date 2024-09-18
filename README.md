# Overview

This is a repository containing datasets used in other Astronomer resources like the [Learn page](https://docs.astronomer.io/learn).

## Datasets

- `databricks-tutorial`: 3 CSVs from [this Kaggle Dataset](https://www.kaggle.com/datasets/programmerrdai/renewable-energy) (License [Public Domain CC0](https://creativecommons.org/publicdomain/zero/1.0/)) by the Kaggle user programmerrdai derived from [Renewable Energy, Our World In Data](https://ourworldindata.org/renewable-energy), License [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). 
- `etl-snowflake-blogpost`: A dataset consisting of 4 CSV files about tea. 
- `dog_intelligence.csv`: A slightly modified version of [this Kaggle Dataset](https://www.kaggle.com/datasets/jasleensondhi/dog-intelligence-comparison-based-on-size) by Jasleen Sondhi and Tejas Junankar. [License CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
- `movie_descriptions.txt`: A slightly modified version of [this Kaggle Dataset](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb) by radmirkaz based on publicly available movie descriptions on [IMDB](https://www.imdb.com/).
- `possum.csv`: A dataset about possums for simple regression analysis. The data was provided [on Kaggle](https://www.kaggle.com/datasets/abrambeyer/openintro-possum) by ABeyer. [License CC0 Public Domain](https://creativecommons.org/publicdomain/zero/1.0/).
- `subset_energy_capacity.csv`: A subset of: Open Power System Data. 2020. Data Package National generation capacity. Version 2020-10-01. https://doi.org/10.25832/national_generation_capacity/2020-10-01. (Primary data from various sources, for a complete list see URL).

## Synthetic Datasets

- `ski_dataset.csv`: contains generated data describing fictive skiers, their attributes and choice of afternoon beverage.

## Wheel files

These files contain beta versions for new Airflow providers. They are not meant for production use.

- `airflow_provider_weaviate-0.0.1-py3-none-any.whl`: Beta version of the Airflow Weaviate provider.
- `astro_provider_snowflake-0.0.0-py3-none-any.whl`: Beta version of the Airflow Snowpark provider (to be integrated with the existing Snowflake provider in a future release).