# Gavia
[![License](http://img.shields.io/:license-mit-blue.svg)](http://octopress.mit-license.org) ![Version](https://img.shields.io/badge/version-0.0.1-orange.svg) ![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-green.svg) 

Python package for processing science data from the Gavia Autonomous Underwater Vehicle

## Usage
Click <a href="https://github.com/brett-hosking/gavia/blob/master/examples/Examples.md" target="_blank">here </a> for usage examples

## Install and setup virtualenv:

### Install **pip** first

    sudo apt-get install python3-pip

### Then install **virtualenv** using pip3

    sudo pip3 install virtualenv 

### Create virtualenv using Python3
    virtualenv -p python3 myenv

### Instead of using virtualenv you can use this command in Python3
    python3 -m venv myenv

>you can use any name insted of **myenv**

## Activate virtual environment

    source myenv/bin/activate

>the environment can be deactivated with the **deactivate** command

## Install Package using **pip** (recomended)
    pip install gavia 

### OR

## Install Package locally
    git clone https://github.com/brett-hosking/gavia.git

### Install requirements from file 
    pip install -r requirements.txt


### Run pip to install package (locally)
    pip install . 

### Upgrade Package locally
    git pull
    pip install . --upgrade