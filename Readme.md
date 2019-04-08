# ECI Aggregator Notebook
This repository contains [Jupyter](https://jupyter.readthedocs.io/en/latest/tryjupyter.html) `Notebook` for learning material about Spark. The content is very small and simple. We hope it's easy to understand. To run this `Notebook`, you need to install `Jupyter` and Scala Interpreter plugin for `Jupyter`: `Apache Toree`. Please follow the guide bellow:

## Add `SPARK_HOME` to environment variable
- Make sure you already have `Spark` installed.
- Edit your `.bashrc`( or `.zshrc` if you are using zsh)
- add `export SPARK_HOME=/path/to/your/spark/installation`. Example: `/home/dharmasaputra/Application/spark-2.4.0-bin-hadoop2.7`
- Save it.

## Installing Jupyter and Apache Toree
- `$ sudo apt install python-pip` // skip if you already have pip
- `$ sudo apt install python-dev`
- `$ sudo apt install ipython ipython-notebook`
- `$ pip install --upgrade pip` // upgrade pip to latest version
- `$ pip install jupyter`
- `$ pip install toree` // `Scala` kernel plugin for Jupyter
- `$ pip install --upgrade jsonschema`
- `$ pip install --upgrade jsonpointer`
- `$ jupyter toree install --spark_home=SPARK_HOME --interpreters=Scala` // enable Toree plugin

## Running Notebook
- `cd` to this project directory
- Run `jupyter notebook`
- A browser tab will opened automatically at http://localhost:8888/
- Please open `SparkNotebook.ipynb` in the browser.
- Now you can read the learning material and also you can change and run it interactively
-
## Issues, Questions and Ideas
Please create an issue to this repository. For idea and any improvement any PR are welcome
