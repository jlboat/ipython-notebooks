# ipython-notebooks
IPython notebooks used for interactive learning.

These IPython notebooks were created for educational/self-educational purposes.

Please, feel free to use/copy/modify/distribute these notebooks. I only ask
that you credit me with authorship.

## HTML

HTML files are provided for notebooks as some notebooks fail to render properly on GitHub.
To view these files, I recommend you:

    1. open http://htmlpreview.github.com/ 
    2. Right-click the HTML file and select "Copy Link Location"
    3. Paste this link into the search bar on http://htmlpreview.github.com/ 

Alternatively, you may download the HTML file and view it locally.

## Use

Most notebooks may be downloaded and viewed in their static HTML form for those unfamiliar with 
Jupyter/IPython notebooks. Alternatively, GitHub will automatically render all of the 
notebooks except for the InteractiveDistribution notebook.

These notebooks were made using Python 3.5, but most notebooks should work with
Python 2.7 as well.

At the time of writing this README, only InteractiveDistributions absolutely
requires a local jupyter notebook setup. 

To install jupyter, I recommend installing either Miniconda or Anaconda.
Detailed directions may be found here: https://conda.io/docs/user-guide/install/index.html

Installing Anaconda should provide all necessary dependencies, but an explicit list of 
dependencies used in the InteractiveDistributions notebook may be found in 'dependencies.txt'

Once conda is installed, installation of these dependencies is as easy as:

```
$ conda install --file dependencies.txt
```

