ipython-notebooks
=================

### installing ipython in Ubuntu

... is described [here](http://ipython.org/install.html).


### viewing an ipython notebook online

You can paste the URL for an ipython notebook hosted on github, here:

http://nbviewer.ipython.org/

And it will generate a link for sharing the notebook, as well as a link to the github repo.

- Try it: you can view the .ipynb file in this directory by navigating to:

http://nbviewer.ipython.org/github/OpenWaterProject/ipython-notebooks/blob/master/RiffleTest1.ipynb


### generating html from an ipython notebook

Converting ipython notebooks to other formats is described [here](http://ipython.org/ipython-doc/1/interactive/nbconvert.html).

To generate html:

> ipython nbconvert --to html --template basic

generates simplified HTML, useful for embedding in webpages, blogs, etc.
