.. -*- mode: rst -*-

|

.. image:: https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue.svg
    :target: https://www.python.org/downloads/

.. image:: https://img.shields.io/github/license/raphaelvallat/entropy.svg
  :target: https://github.com/raphaelvallat/entropy/blob/master/LICENSE

.. image:: https://travis-ci.org/raphaelvallat/entropy.svg?branch=master
    :target: https://travis-ci.org/raphaelvallat/entropy

.. image:: https://codecov.io/gh/raphaelvallat/entropy/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/raphaelvallat/entropy

----------------

.. figure::  https://github.com/raphaelvallat/entropy/blob/master/docs/pictures/logo.png
   :align:   center

EntroPy is a Python 3 package providing several time-efficient algorithms for computing the complexity of time-series.
It can be used for example to extract features from EEG signals.

.. warning::
    EntroPy is now **DEPRECATED**. Please use the `AntroPy package <https://github.com/raphaelvallat/antropy>`_ instead!

Installation
============

EntroPy is now **DEPRECATED** because it could not be installed using pip (see below). Please use the `AntroPy package <https://github.com/raphaelvallat/antropy>`_ instead!

.. important::
  EntroPy **CANNOT BE INSTALLED WITH PIP OR CONDA**.
  There is already a package called *entropy* on the `PyPi repository <https://pypi.org/project/entropy/>`_,
  which should NOT be mistaken with the current package.

.. code-block:: shell

  git clone https://github.com/raphaelvallat/entropy.git entropy/
  cd entropy/
  pip install -r requirements.txt
  python setup.py develop

Development
===========

EntroPy was created and is maintained by `Raphael Vallat <https://raphaelvallat.com>`_. Contributions are more than welcome so feel free to contact me, open an issue or submit a pull request!

To see the code or report a bug, please visit the `GitHub repository <https://github.com/raphaelvallat/entropy>`_.

Note that this program is provided with **NO WARRANTY OF ANY KIND**. Always double check the results.

Acknowledgement
===============

Several functions of EntroPy were adapted from:

- MNE-features: https://github.com/mne-tools/mne-features
- pyEntropy: https://github.com/nikdon/pyEntropy
- pyrem: https://github.com/gilestrolab/pyrem
- nolds: https://github.com/CSchoel/nolds

All the credit goes to the author of these excellent packages.
