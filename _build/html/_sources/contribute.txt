#####################
Contribute
#####################

We value your ideas! If you'd like to help improve Burnout.io, do whatever works best for you:

* Open an `issue <https://github.com/reignite/burnout.io/issues/new>`_ 
* `Fork <https://github.com/reignite/burnout.io/fork>`_ the project and submit a PR
* Send an `email`_
* Reach out on `twitter <https://twitter.com/BenjaminMosior>`_ 

Info for Contributing to Burnout.io
------------------------------------------

* This project is written in `reStructuredText <http://docutils.sourceforge.net/docs/user/rst/quickstart.html>`_
* Hosted by `Read the Docs <http://readthedocs.org/>`_
* Tested by rendering in `Sphinx <http://sphinx-doc.org/>`_ on `Travis CI <https://travis-ci.org>`_

If you are looking to add content, fix formatting, syntax, typos or other
wonderful things, please follow this process:

* Install Sphinx: ``easy_install Sphinx sphinx_rtd_theme`` or ``pip install -r requirements.txt``
* Fork the repository to your own account
* Check out a branch to make your changes on: ``git checkout --branch <my_topic>``
* Execute ``make html`` to build the docs in to ``_build/``
* Make your changes
* Execute ``make html`` again and verify your changes don't cause any
  warnings/errors
* Commit with a descriptive message, and submit a pull request from your branch
  to ``master``
* We'll review the change, and either merge it or provide some feedback. Community review is also encouraged.

A quick note if you're adding a new heading:  

Sphinx will error out if your title text is longer than the title underline. For example:
``/projects/burnout.io/resources.rst:12: WARNING: Title underline too short.``

And when you look at the title, you see:

.. code-block:: rst

    This title is quite long...
    -----

Which will cause the error. Corrected, the tite would be more like:

.. code-block:: rst

    This title is quite long...
    -----------------------------------

Which will correct the issue.  For any other issues you run into, hop into the Gitter channel and one of us will help out.

.. image:: https://badges.gitter.im/Join%20Chat.svg
   :target: https://gitter.im/reignite/burnout.io
   :alt: Gitter Channel

Current Build Status
---------------------------

.. image:: https://readthedocs.org/projects/burnoutio-test/badge/?version=latest
    :target: http://burnoutio-test.readthedocs.org/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://travis-ci.org/AaronSachs/burnout.io-test.svg
    :target: https://travis-ci.org/AaronSachs/burnout.io-test
    :alt: Travis Build Status

.. _email: mailto:bemosior+burnoutio@gmail.com 