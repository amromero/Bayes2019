## Material for Nuclear TALENT course in York, UK, June 10-28, 2019

This repository contains the learning material for the Nuclear TALENT course
Learning from Data: Bayesian Methods and Machine Learning, in York, UK, June 10-28, 2019 

Students are encouraged to install python and the required modules before the start of the school.


### Installation

Download the repo from github and enter the directory which should have been created on your computer:

    git clone https://github.com/NuclearTalent/Bayes2019.git
    cd Bayes2019

The notebooks that we will be using depend on several scientific python modules (see the list in environment.yml) and require a python3.x installation. 

These python modules and their dependencies are best installed using ``conda`` by creating
a virtual environment:

    conda env create
    conda activate talent-env

To deactivate the virtual environment:

    conda deactivate

Note that earlier versions of conda used 'source' instead of 'conda' to activate environments.

You are encouraged to enter the intro directory and start the jupyter notebook:

    cd intro
    jupyter notebook bayesTALENT_intro.ipynb
