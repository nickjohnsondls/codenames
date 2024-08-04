#Codenames Project
Overview
The Codenames project, developed by the Michigan Data Science Team, centers around building and testing models based on word vector representations. This repository contains data files and Jupyter notebooks that facilitate the creation and evaluation of these models.

Repository Structure
Data Files
cleaned_dict.csv: A cleaned version of the dictionary data used for model training.
wordlist-eng.txt: A text file containing a list of English words used in the project.
Jupyter Notebooks
create_model.ipynb: This notebook loads the dictionary data from cleaned_dict.csv and creates a Word2Vec model. The trained model is saved for further use in the project.

example_function_code.ipynb: Demonstrates example functions that utilize the Word2Vec model created in create_model.ipynb. It includes functions for processing words and generating vector representations.

model_tester.ipynb: Tests the Word2Vec models created. This notebook includes various methods to evaluate the performance of the models.

qLearn.ipynb: Implements a Q-learning-like method. It contains code for reinforcement learning algorithms that can be applied to the Word2Vec model to enhance its performance.

q_learning.ipynb: Provides a simple example of a Q-learning implementation. This notebook demonstrates the basics of reinforcement learning using Q-learning techniques.

FastText.ipynb: This notebook explores the use of FastText, an alternative to Word2Vec, for generating word vector representations.

member_models/HenryDrew QLearn.ipynb: A specialized Q-learning method developed by team member Henry Drew. This notebook includes unique approaches and optimizations for the reinforcement learning process.

Other Files
README.md: Provides an overview and instructions for the Codenames project.

.DS_Store: A system file for macOS directory metadata.

Usage
