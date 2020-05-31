# 2020 Deep Learning Project

Team: Unilayer Perceptron

## Instructions

0. (First run only) run paths.py to ensure proper data directory architecture
1. Add images to data training and test data directories
2. Run main.py

Labels in the required (long/tidy) format in the data directory as CSV.

## File Structure

Directories:

* data: directory architecture for
* old: PeopleNet older trial.
* pkl: pickle files for trained networks

Files:

* datasets.py: make the custom PyTorch datasets and transforms.
* main.py: coordinate the rest of scripts, train, validate, plot.
* model.py: convolutional network used by main.py.
* multilabel.py: preprocessing of labels data structure.
* paths.py: manage all file paths in the project.
* README.md: you are here.
* utils.py: auxiliary methods for main.py.