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
