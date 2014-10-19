Academic citations entity resolution
====================================

After cloning the repository, run:

```
git submodule init
```

Then, run the IPython notebooks in order. A few notes:

* The first notebook, which downloads all the citation data, may take
  several hours to complete.
* The second notebook will (temporarily) need about 10 gigabytes of
  disk space. When it is completely finished, it will only need about
  150 megabytes.
* The last notebook, which calculates similarity, relies on IPython
  parallel. To use IPython parallel, go to the "Clusters" tab on the
  IPython notebook dashboard and start the number of engines that you
  want. Then, run the notebook. Depending on how many cores you
  allocate to it, this may also take several hours to complete.

Links to the notebooks on nbviewer:

* [1 - Download citation data](http://nbviewer.ipython.org/github/jhamrick/citation-entity-resolution/blob/master/1%20-%20Download%20citation%20data.ipynb)
* [2 - Extract author information](http://nbviewer.ipython.org/github/jhamrick/citation-entity-resolution/blob/master/2%20-%20Extract%20author%20information.ipynb)
* [3 - Make buckets](http://nbviewer.ipython.org/github/jhamrick/citation-entity-resolution/blob/master/3%20-%20Make%20buckets.ipynb)
* [4 - Calculate author name similarity](http://nbviewer.ipython.org/github/jhamrick/citation-entity-resolution/blob/master/4%20-%20Calculate%20author%20name%20similarity.ipynb)
