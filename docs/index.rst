*************
HyperNOMAD
*************

HyperNOMAD is a Python package dedicated to the hyperparameter optimization of deep neural networks. The package contains a blackbox specifically designed for this problematic and provides a link with the NOMAD software used for the optimization. The blackbox takes as inputs a list of hyperparameters, builds a corresponding deep neural network in order to train, validate and test it on a specific data set before returning the test error as a mesure of performance. NOMAD is then used to minimize this error. The following appendix provides an overview of how to use the HyperNOMAD package.

   

.. image:: hypernomad_picture.jpg
   :scale: 50 %
   :alt: alternate text
   :align: center


.. toctree::
   :caption: Installation Guide
   :maxdepth: 1

   installation/prerequisites
   installation/stepbystep
   
   
.. toctree::
   :caption: User Guide
   :maxdepth: 1

   userguide/basicusage
   userguide/startingpoint
   userguide/personnaldataset
   
.. toctree::
   :caption: Examples
   :maxdepth: 1
   
   examples/mnist
   examples/cifar10
