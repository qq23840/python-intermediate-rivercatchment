# Rivercatch

![Continuous Integration build in GitHub Actions](https://github.com/qq23840/python-intermediate-rivercatchment/actions/workflows/main.yml/badge.svg?branch=develop)

RiverCatch is a data management system written in Python that manages measurement data collected in river catchment surveys and campaign. It was created during the NERC Intermediate Python Workshop (Reproducible Research Through Reusable, Reliable Code)

## Main Features
Here are some key features of InFlam:

- Provide basic statistical analyses of data
- Ability to work on measurement data in Comma-Separated Value (CSV) format
- Generate plots of measurement data
- Analytical functions and views can be easily extended based on its Model-View-Controller architecture

## Prerequisites
RiverCatch requires the following Python packages:

- [NumPy](https://www.numpy.org/) - makes use of NumPy's statistical functions
- [Pandas](https://pandas.pydata.org/) - makes use of Panda's dataframes
- [GeoPandas](https://geopandas.org/) - makes use of GeoPanda's spatial operations
- [Matplotlib](https://matplotlib.org/stable/index.html) - uses Matplotlib to generate statistical plots

The following optional packages are required to run RiverCatch's unit tests:

- [pytest](https://docs.pytest.org/en/stable/) - RiverCatch's unit tests are written using pytest
- [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test coverage stats to unit testing

