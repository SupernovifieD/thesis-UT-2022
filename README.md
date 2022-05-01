# Master's Thesis - May 2022
![Downloads](https://img.shields.io/github/downloads/SupernovifieD/thesis-UT-2022/total?style=flat-square)
![License]()
![Issues]()
![Size]()
Hi. It's Yasin. This repo contains my master's thesis files. It's a single Jupyter Notebook file, that contains the program with explanations of code blocks. And also, there are two `data` files that are used to run the code. I studied mining engineering for my master's at University of Tehran, in Iran, and defended my thesis in May 2022.

This project was aimed at developing a data-driven tool with python for mineral potential mapping. This tool can be used by geoscientists who'd like to integrate several evidential layers of geochemical data. The method used here is based on a study by [Mahyar Yousefi and Emmanuel Carranza](https://doi.org/10.1016/J.CAGEO.2015.03.007). They have used Prediction-Area plots and Concentration-Area fractal analysis to classify and evaluate evidential maps. Their approach is semi-data-driven as there are still instances where the user has to arbitrarily navigate functions and set value to some variables.

I have tried to code their work with python. Python is an agile, efficient, and practical tool both for research and business. So, I chose python as my programming language of choice. I have tried to use easy-to-use libraries including `pandas`, `numpy`, `scipy`, and `matplotlib`, as much as possible so the user can easily use and modify the code. This program is my very first engagement with the world of programming as my prior academic studies were only limited to mining engineering. Please reach out via `issue` if you see any point for improving this piece for higher usability and readability.

## How to install and run the project?
As of this moment, this project is only available in a Jupyter Notebook, which is very much practical for geoscientists and novice users. In the future, this notebook will be developed into several scripts.

You need to have[ installed python 3.x](https://www.python.org/downloads/) on your local machine if you look to run the code on your machine. The simplest way to open `.ipynb` files is using Jupyter Notebook itself. You can download and install it using `conda`. [Please follow their instructions on their website for installation](https://docs.anaconda.com/anaconda/install/index.html). You also need to have the given libraries and packages installed. Otherwise, you could follow the instructions in the notebook to install and use them.

So, for now, you could just simply open the file, read, modify, and execute the code on spot. In order to do so, you could `download` the notebook on your local machine and use the given `data` files, one as the main dataset and another as known mineral occurrences, to run the code. There is no need to download the `data` files, unless you want to take a closer look at the files.

## How to use the project?
This project has been designed for ease of use for geoscientists and developers alike. First, the user should have a fair bit of knowledge in regards with geochemistry and terminology used in here. Second, the user needs to know their way around with python to see how they could modify the could to satisfy their needs. There are instances that the user want the code to work differently. In situations like that, a modest amount of programming insight can be helpful.

This program takes `csv` files. `Part 1` of the code, as explained in the notebook, provides useful functions to pre-process the data, and also, examine the data statistically. `Part 2` is the core of the work where most of the processing takes place. The results in this part are mostly images. These images could be saved on your local machine in the same directory as the notebook file if you used `plt.savefig()` command. But for now, they're just shown to the user within the command lines of the Jupyter Notebook.
