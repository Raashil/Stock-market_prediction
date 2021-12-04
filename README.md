# Stock-market_prediction
Running for the first time?

The files environment.yml, requirements.txt make it easy to replicate the environment required for running the model.

Setting up the Environment

For anaconda:
To install anaconda, refer this
The base directory contains 'environment.yml' file. To replicate the same environment:
conda env create -f environment.yml
For python3 virtual environment:
To install virtualenv, refer this
pip install virtualenv
virtualenv --python=python3 ml-stock-prediction
The base directory contains 'requirements.txt' file. To install the required packages:
pip install -r requirements.txt
Getting Data

Though the datasets folder has some symbol stock prices. You can populate with more.

python get_data.py [symbols]
Running the models

You can run the model on a list of symbols supplied as command line arguments.

python main.py [symbols]
