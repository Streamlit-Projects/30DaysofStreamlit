# Setting up a local development environment <br><br/>

A local development environment allows you to use your own machine to run your website, instead of using one provided by a web hosting (opens in new tab) company.
Before you start building Streamlit apps, you first have to set up a development environment. 
<br><br/>

### Install conda
Conda is an open-source package management system and environment management system that runs on Windows, macOS, and Linux.
Conda quickly installs, runs, and updates packages and their dependencies. Conda easily creates, saves, loads, and switches between environments on your local computer.

It was created for Python programs but it can package and distribute software for any language.

To install `conda`:
- go to [conda website](https://docs.conda.io/en/latest/miniconda.html) and choose your operating system
- download and run the installer 
<br><br/>

### Create a new conda environment
Next step is to create a conda environment for managing all the Python library dependencies.
To create a new environment with Python 3.10, we have to run the following command in Anaconda Prompt:

`conda create -n stenv python=3.9`
<br><br/>

### Activate the conda environment
To be able to use a conda enironment created earlier we need to activate it. We do so by running the following command line:

`conda activate stenv`
<br><br/>

### Install the Streamlit library
We now need to install the streamlit library:

`pip install streamlit`
<br><br/>


### Launching the Streamlit demo app
To launch the Streamlit demo app:

`streamlit hello`
<br><br/>

### Welcome to Streamlit app
After running **streamlit hello** command, we launch the following app:

<p align="center">
<img width="650em" src="" align = "center"/>
</p>