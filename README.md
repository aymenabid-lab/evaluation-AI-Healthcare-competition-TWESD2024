# Scoring code for the AI healthcare competition - TWESD2024

This repository contains the Python evaluation code for the Challenge.

The `evaluate_model` script evaluates the outputs of your models using the evaluation metric that is described on the [webpage](http://www.ceslab.org/TWESD2024/) for the 2024 Challenge. 
This script reports multiple evaluation metrics, so check the [scoring section](https://docs.google.com/document/d/1JvY1cgFr49i-zp5-ovEtRSaY9buSiSbbDJv9LiLPMZk/edit#bookmark=id.hd4qv2dmvr1i) of "AI Healthcare TWESD competiton Description" document, to see how we evaluate and rank your models.

## Python

You can run the Python evaluation code by installing the NumPy package and running the following command in your terminal:

    python evaluate_model.py -d labels -o outputs -s scores.csv

where

- `labels` (input; required) is a folder with labels for the data, such as the [training data](https://docs.google.com/document/d/1JvY1cgFr49i-zp5-ovEtRSaY9buSiSbbDJv9LiLPMZk/edit#bookmark=id.gwnt0cr575kd) on the PhysioNet Challenge webpage;
- `outputs` (input; required) is a folder containing files with your model's outputs for the data; and
- `scores.csv` (output; optional) is a collection of scores for your model.

## Troubleshooting

Unable to install or run Python? Try [Python](https://www.python.org/downloads/), [Anaconda](https://www.anaconda.com/products/individual), or your package manager.

## How do I learn more?

Please see the [Challenge website](http://www.ceslab.org/TWESD2024/) for more details. Please post questions and concerns on the [Challenge classroom](https://classroom.google.com/u/1/c/NjUyNjE0ODk0MDg5), after joining it (only one of the team).

## Useful links

- [Challenge website](http://www.ceslab.org/TWESD2024/)
- [Python example code](https://github.com/aymenabid-lab/code-competiton-TWESD-2024/tree/main)

