Author: Kevin M. Loew
Contact: kevin.m.loew@gmail.com

Last Modified: July 23, 2019

This repository contains my analysis of the Kaggle Intel Image Classification dataset. 

The jupyter notebooks analyzes the data to compare the TensorFlow and PyTorch frameworks fro building a model as well as implementing transfer learning.


I used a conda enviroment to avoid jupyter kernel issues from virtualenv. To setup this enviroment use:

    conda create --name temp python=3.6 jupyter

To activate the enviroment:
    
    conda activate temp
    

Then run:

    conda install --file requirements_conda.txt
    
If you prefer virtualenv or pip you can setup with:

    pip install -r requirements_pip.txt

The final comparisons are presented in the TFvsPT.pdf slideshow.
