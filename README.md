# NOVO BANCO - Data Science Challenge


## Introduction

In online advertising, click-through rate (CTR) is a very important metric forevaluating ad performance.  As a result, click prediction systems are essentialand widely used for sponsored search and real-time bidding.For this challenge, contesters were provided with data representing 11 daysof interactions between the different ads and its users.

## Structure

1. `0.1-vfernandes-sampling.ipynb`: Initial ingestion of data, sampling;
2. `0.2-vfernandes-exploration.ipynb`: Deep dived data exploration and feature generation;
3. `0.3-vfernandes-modelling.ipynb`: Modelling.

## How-to-Run

0. Create `../data/`, `../data/featurized-data`, `../data/hashed_data`, `../data/selected_data`

1. Create a Python 3.6.7 Virtual Environment:

`python3 -m virtualenv .venv`

2. Install required packages:

`pip install -r requirements.txt`

3. Add raw data at `../data/`

4. Activate `virtualenv`:

`source .venv/bin/activate`

5. Run Jupyter-Lab:

`jupyter-lab`

We are all set to go!
