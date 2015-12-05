==================================
Nottingham Hackspace Rules - Draft
==================================

|docs|

http://rules.nottinghack.org.uk
This is the draft version of the new rules for nottingham hackspace


Contributing
============
The rules are written using reStructuredText for more info on the syntax please visit http://docutils.sourceforge.net/rst.html

The docs are built and hosted by Read The Docs http://readthedocs.org

If you wish to comment these rules please either open a `issue <https://github.com/NottingHack/rules/issues>`_ or a `pull request <https://github.com/NottingHack/rules/pulls>`_


Workflow for submitting text changes
====================================
We use pull request to suggest changes, these should be done with forks and pull requests. Once a pull request is submitted others can then discuss these changes before the are accepted into the rules.

To do a pull request start by forking this repository by clicking the fork button in the upper right corner.

Once forked github should take you to your copy of the rules, make sure your branch is set to 'rtd-draft', click onto the file for the rule you wish to edit.

You should now have a edit icon in the right hand corner (looks like a pencil), Click this and you can make your changes, at the bottom of the page is a area titled "Commit changes" Fill in the boxes with a meaningful comment about your change. Small changes and lots of commits are better than a single commit with a rewrite of the whole page.

Once you have a commit you can star a pull request, on the front page of you repository click the green 'New pull request' button , this will show a list of changes between your copy the hackspace, click the green 'Create pull request' button, add a suitable comment and click the green 'Create pull request'.


Building rendered version locally - Advanced
============================================

You will need python and to install the following dependencies

.. code:: bash

$ pip install sphinx
$ pip install sphinx_rtd_theme

Then you can build the html version with

.. code:: bash

$ make html

and open the index page at

.. code::

./build/html/index.html

.. |docs| image:: https://readthedocs.org/projects/nottingham-hackspace-ruless/badge/?version=latest
    :target: http://rules.nottinghack.org.uk/en/latest/?badge=latest
    :scale: 100%
    :alt: Documentation Status
