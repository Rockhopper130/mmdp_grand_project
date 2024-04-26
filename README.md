# Regression Task Approach 

## Overview
This repository contains a sequence of Jupyter notebooks designed to perform a regression task on a set of data with the goal of predicting 'likes' on media based on captions generated from the media content. The process involves generating captions using the Blip2 model, creating instructional data from these captions, classifying the data into buckets, and then performing regression on each classified bucket.

### Tasks:
- **Caption Generation**: Used the `blip2-caption-generation.ipynb` notebook to generate captions for input media data.
- **Instruction Data Creation**: Utilized the `making-instruction-data-for-task1.ipynb` notebook to create prompts corresponding to the input, incorporating various metadata.
- **Bucket Classification**: Implemented the `training-and-inference-distilbert.ipynb` notebook to classify the data into 7 distinct buckets based on the number of likes.
- **Regression Analysis**: Employed the `regression_on_buckets.ipynb` notebook to perform regression on each bucket using various regressor models.
- **Deployment**: Execute the `task1-deployed.ipynb` notebook to run the project and observe the inferences easily.


### Note

In order to run the deployment code, you must add the following files to their respective model folders. They can be accessed from <a href="https://drive.google.com/drive/folders/1SmjrayGYlBiQQHzvsVNK4E33-KUDdN1f?usp=sharing">link</a>