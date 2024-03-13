# Higgs Boson Event Detection

## Project Report

**https://sugatagh.github.io/dsml/projects/higgs-boson-event-detection/**

## Overview
 
- In [**particle physics**](https://en.wikipedia.org/wiki/Particle_physics), an _event_ refers to the results just after a [**fundamental interaction**](https://en.wikipedia.org/wiki/Fundamental_interaction) took place between [**subatomic particles**](https://en.wikipedia.org/wiki/Subatomic_particle), occurring in a very short time span, at a well-localized region of space.

- A _background event_ is explained by the existing theories and previous observations. On the other hand, a _signal event_ indicates a process that cannot be described by previous observations and leads to the potential discovery of a new particle.

- In this project, we aim to predict if a given event is _background_ or _signal_, based on the data provided in the Kaggle competition [**Higgs Boson Machine Learning Challenge**](https://www.kaggle.com/competitions/higgs-boson/).

- A detailed backdrop of the problem is given, and [**exploratory data analysis**](https://en.wikipedia.org/wiki/Exploratory_data_analysis) on the provided data is carried out.

- The observations obtained from EDA are used in the [**data preprocessing**](https://en.wikipedia.org/wiki/Data_Preprocessing) and [**feature engineering**](https://en.wikipedia.org/wiki/Feature_engineering) stages.

- We build a [**neural network**](https://en.wikipedia.org/wiki/Neural_network) and [**tune**](https://en.wikipedia.org/wiki/Hyperparameter_optimization) it to predict if a given event is _background_ or _signal_.

- We employ the [**approximate median significance**](https://www.kaggle.com/competitions/higgs-boson/overview/evaluation) (AMS) metric to evaluate the models. The final model obtains a training AMS of $2.500144$ and a test AMS of $1.200022$. It achieves a training [**accuracy**](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification) of $0.827070$ and a test accuracy of $0.824100$.