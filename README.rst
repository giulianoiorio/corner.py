corner.py
=========

.. image:: http://img.shields.io/travis/dfm/corner.py/master.svg?style=flat
    :target: https://travis-ci.org/dfm/corner.py
.. image:: https://coveralls.io/repos/github/dfm/corner.py/badge.svg?branch=master&style=flat
    :target: https://coveralls.io/github/dfm/corner.py?branch=master&style=flat
.. image:: http://img.shields.io/badge/license-BSD-blue.svg?style=flat
    :target: https://github.com/dfm/corner.py/blob/master/LICENSE
.. image:: https://zenodo.org/badge/4729/dfm/corner.py.svg?style=flat
    :target: https://zenodo.org/badge/latestdoi/4729/dfm/corner.py
.. image:: http://joss.theoj.org/papers/10.21105/joss.00024/status.svg?style=flat
    :target: http://dx.doi.org/10.21105/joss.00024


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
This version
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
This version of corner is a slighly modified version forked from the original `repo <https://github.com/dfm/corner.py>`_.
The main additions are the keywords prior(=None by default) and prior_color(='gray' by default) to the function corner in corner.py.
If prior is not None it has to be a an array with dimendion N,k where k is the number of parameters containing a sample of N data from the prior
of the fitted parameters. The prior distributions are plotted in the corner plots as dashed histrograms with the color indicated in prior_color.



++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Read `the documentation <http://corner.readthedocs.io/>`_.
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

If you make use of this code, please cite `the JOSS paper
<http://dx.doi.org/10.21105/joss.00024>`_:

.. code-block:: tex

    @article{corner,
        Author = {Daniel Foreman-Mackey},
        Doi = {10.21105/joss.00024},
        Title = {corner.py: Scatterplot matrices in Python},
        Journal = {The Journal of Open Source Software},
        Year = 2016,
        Volume = 24,
        Url = {http://dx.doi.org/10.5281/zenodo.45906}
    }
