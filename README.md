# Codenames Project
Overview
The Codenames project is developed by the Michigan Data Science Team. This repository contains data files and code that together form the foundation for a Word2Vec model, which is essential for our project's main functionality. The project revolves around creating and testing models that leverage word vector representations.

Repository Structure
Data Files
codenames_word_data.csv: This file contains the word data used in the Codenames project.
english_dictionary.csv: This file includes words along with their definitions from the English dictionary.
Jupyter Notebooks
create_model.ipynb: This notebook is used to load the dictionary data and create a simple Word2Vec model. The model is trained on the words and their definitions from the english_dictionary.csv file. This Word2Vec model will be the foundation for our project.

example_function_code.ipynb: This notebook contains example functions that demonstrate how to use the Word2Vec model created in create_model.ipynb. It includes functions for processing words and generating their vector representations.

model_tester.ipynb: This notebook is designed to test the Word2Vec models. It includes various methods to evaluate the performance of the models and ensures that they are functioning correctly.

qLearn.ipynb: This notebook implements a Q-learning-like method. It contains code for reinforcement learning algorithms that can be applied to the Word2Vec model to improve its performance in specific tasks.

member_models/HenryDrew QLearn.ipynb: This notebook is a variant of the Q-learning method, specifically tailored by team member Henry Drew. It includes unique approaches and optimizations for the reinforcement learning process.

Usage
Creating the Word2Vec Model:

Open create_model.ipynb.
Run the cells to load the dictionary data and create the Word2Vec model.
Save the trained model for further use.
Using Example Functions:

Open example_function_code.ipynb.
Run the cells to see example functions in action. These functions demonstrate how to use the Word2Vec model for various tasks.
Testing the Model:

Open model_tester.ipynb.
Run the cells to test the performance of the Word2Vec model. This notebook includes several evaluation metrics to ensure the model's accuracy and effectiveness.
