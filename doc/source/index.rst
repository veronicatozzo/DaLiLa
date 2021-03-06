.. dalila documentation master file, created by
   sphinx-quickstart

=====================================
DALILA (DictionAry LearnIng LibrAry)
=====================================

**DALILA** is a Dictionary Learning Library whose purpose is to find a
decomposition of an input matrix **X** into two other matrices **D** and **C**
which are respectively the *dictionary* which contains the basic atoms and the
*coefficients* that are weights for the atoms. The linear combination of
the atoms weighted with the coefficients give an approximation of the original
signal.
It offers also methods for Representation Learning which is a related method
that given the dictionary **D** and the signal matrix **X** finds the
coefficients.

We propose a generic optimization algorithm that can optimize the functional
with different penalties both on the dictionary and on the coefficients.

The library allows to run some of its computationally expensive parts in parallel
on the same machine or distributing the tasks with dask
(http://dask.pydata.org/en/latest/index.html).

User documentation
==================
.. toctree::
   :maxdepth: 2

 tutorial.rst

.. _api:

***********************
API
***********************

.. toctree::
   :maxdepth: 1


Classes
-----------------------------

.. automodule:: dalila.dictionary_learning
   :members:

.. automodule:: dalila.representation_learning
   :members:

Parameter research utils
-----------------------------

.. automodule:: dalila.parameters_research
   :members:
   
Plotting functions
-----------------------------

.. automodule:: dalila.plot
   :members:


Dataset generator
-----------------------------

.. automodule:: dalila.dataset_generator
   :members:


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`

