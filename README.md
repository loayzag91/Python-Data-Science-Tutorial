# Python Data Science Tutorial
These notebooks are my personal notes taken from the video lectures of the
online course [Python for Data Science and Machine Learning Bootcamp](https://www.pieriandata.com/p/python-for-data-science-and-machine-learning-bootcamp).


# Installing the Notebooks
First install [poetry](https://github.com/python-poetry/poetry), a Python dependency manager.

Please note that this project requires Python 3.5–3.8 for TensorFlow dependencies.  
To ensure the proper version of Python is being used, pyenv is recommended.  

For example, from the directory of wherever this repository was cloned to your file system,  
run this before installing:

`> pyenv install 3.8.6`  
`> pyenv local 3.8.6`

Then:

`> poetry install`

# Running the Notebooks
Running the notebooks is a simple as running the command:

`> poetry run jupyter-notebook`
