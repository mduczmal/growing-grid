# Growing grid
Pytorch implementation of 3-D Growing Grid (extension of [Kohonen Self-Organizing Map](https://en.wikipedia.org/wiki/Self-organizing_map)) with Gaussian neighbourhood function and exponentially decreasing learning rate. For a description of 2-D model see: *Growing Grid - a self-organizing network with constant neighborhood range and adaptation strength*, Fritzke, B. Neural Process Lett (1995) 2:9. <https://doi.org/10.1007/BF02332159>.

Code is based on Giannis Nikolentzos' [2-D SOM implementation](https://github.com/giannisnik/som), who modified Sachin Joglekar's [Tensorflow implementation](https://codesachin.wordpress.com/2015/11/28/self-organizing-maps-with-googles-tensorflow/).

As an example I use the model to perform voxel clustering of a single frame of a fMRI brain scan.

## Run
```
jupyter notebook growing_grid.ipynb
```

### Data for training was obtained from the [OpenfMRI](https://www.openfmri.org) database. Its accession number is ds000221.
