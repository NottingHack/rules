==================================
Nottingham Hackspace Rules - Draft
==================================

|docs|

http://rules.nottinghack.org.uk
This is the draft version of the new rules for nottingham hackspace


Contributing
============
The rules (and this README) are written using reStructuredText which is a way of formatting a plain text file whilst keeping it human-readable.

For more info on the reStructuredText syntax please visit http://docutils.sourceforge.net/rst.html.  If you are new to this type of documentation, have a look at `the Primer <http://docutils.sourceforge.net/docs/user/rst/quickstart.html>`_ and `Quick reStructuredText <http://docutils.sourceforge.net/docs/user/rst/quickref.html>`_.  If you have used something like this before (for example, Markdown), you should be able to get away with just the `Cheat Sheet <http://docutils.sourceforge.net/docs/user/rst/cheatsheet.txt>`_.

The finsihed documents are built and hosted by Read The Docs http://readthedocs.org and are available at http://rules.nottinghack.org.uk.  When a change is merged into this GitHub repository, the documents are automatically regenerated and available at that site in a couple of minutes.

We will use GitHub for contributions to the rules, using `issues <https://github.com/NottingHack/rules/issues>`_ for simple comments and suggestions if you don't want to get into the nitty gritty, and `pull requests <https://github.com/NottingHack/rules/pulls>`_ for more complex chnages.

All members are welcome to do either, or none.  Both issues and pull requests have the functionality to allow you to comment on them, so please make your feelings known.


Workflow for submitting changes
-------------------------------

If you can, please use a pull request for a change.  This will cut down the amount of work required to integrate multiple issues.

To do this, you will need to fork (make a personal copy of) this repository into your personal account.  Once you have done that, navigate to your fork and select the 'rtd-draft' branch.

You can then work on that in your browser (or your editor of choice) to make the changes you want and commit them to your fork.  You can edit in browser by clicking on the file you wish to change and clicking on the edit icon (pencil) in the top right hand corner. At the bottom of the page is a area titled "Commit changes" Fill in the boxes with a meaningful comment about your change. Small changes and lots of commits are better than a single commit with a rewrite of the whole page.

Now you can then open a pull request to the main repository - on the front page of your fork click the green 'New pull request' button, this will show a list of changes between your copy the main repository. Click the green 'Create pull request' button, add a suitable comment and click the green 'Create pull request'.

Please keep each pull request fairly small - it should be one chanege to the rules.  It is fine for it to span multiple rules, but should be all-or-nothing changes.


Workflow for making suggestions
-------------------------------

If you have a suggestion that isn't quite a change, or you can't work out how to make changes, please raise an `issue <https://github.com/NottingHack/rules/issues>`_. An issue is generally to raise a point or start a discussion.

Simply click 'New Issue' from that page, give it a title and a description, including as much detail as you can, and click 'Submit new issue'.

Commenting
----------

You can make comments on both `pull requests <https://github.com/NottingHack/rules/pulls>`_ and `issues <https://github.com/NottingHack/rules/issues>`_.  We will leave these active for at least a few weeks, so please go in and comment on them, even if that is only to say you agree with the change.


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
