==========================
Cellular Genetic Algorithm
==========================

This repository contains a simple, parallel C++ implementation of a `Cellular
genetic Algorithm`_. The algorithm uses MPI for interprocess communication.

The MPI version has been tested on the OneMax problem. A more complicated
implementation of training an artificial neural network for digit
classification has been implemented as well (without MPI) [KU1995]_.

.. _Cellular Genetic Algorithm: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.43.3205

.. [KU1995] K. W. C. Ku, M. W. Mak, and W. C. Siu. A cellular genetic algorithm for
   training recurrent neural networks. In Proceedings of the International
   Conference on Neural Networks and Signal Processing, pages 140--143, 1995.
   <http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.43.3205>

