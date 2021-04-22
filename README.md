# Data-Science-Projects-With-Python-Second-Edition

This code accompanies the second edition of Data Science Projects with Python (TBD link to Amazon page and more description)

# Installing Anaconda and Setting Up an Environment

Install Anaconda by following the instructions at this link: https://www.anaconda.com/products/individual

It is recommended to create an environment in Anaconda to do the exercises and activities in this book, which have been tested against the software versions indicated here. Once you have Anaconda installed, open a Terminal, if you're using macOS or Linux, or a Command Prompt window in Windows, and do the following:

1. Create an environment with most required packages. You can call it whatever you want; here it’s called `dspwp2`. Copy and paste, or type the entire statement here on one line in the terminal:

`conda create -n dspwp2 python=3.8.2 jupyter=1.0.0 pandas=1.2.1 scikit-learn=0.23.2 numpy=1.19.2 matplotlib=3.3.2 seaborn=0.11.1 python-graphviz=0.15 xlrd=2.0.1`

Type 'y' and [Enter] when prompted.

2. Activate the environment:

`conda activate dspwp2`

3. Install the remaining packages:

`conda install -c conda-forge xgboost=1.3.0 shap=0.37.0`

Type 'y' and [Enter] when prompted.

4. You are ready to use the environment. To deactivate it when finished:

`conda deactivate`
