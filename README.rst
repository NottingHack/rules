==========================
Nottingham Hackspace Rules
==========================

|docs|

http://rules.nottinghack.org.uk

Contributing
============
The rules are written using reStructuredText for more info on the syntax please visit http://docutils.sourceforge.net/rst.html

The docs are built and hosted by Read The Docs http://readthedocs.org

If you wish to comment these rules please either open a `issue <https://github.com/NottingHack/rules/issues>`_ or a `pull request <https://github.com/NottingHack/rules/pulls>`_

Building Locally
================

You will need pyton and to install the following dependencies

.. code:: bash

$ pip install sphinx
$ pip install sphinx_rtd_theme

Then you can build the html version with

.. code:: bash

$ make html

and open the index page at

.. code::

_buld/html/index.html

.. |docs| image:: https://readthedocs.org/projects/nottingham-hackspace-rules/badge/?version=latest
:target: https://readthedocs.org/projects/nottingham-hackspace-rules/?badge=latest
:scale: 100%
:alt: Documentation Status