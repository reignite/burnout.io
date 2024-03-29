[![Documentation Status](https://readthedocs.org/projects/burnoutio/badge/?version=latest)](http://burnoutio.readthedocs.org/en/latest/?badge=latest)  [![Build Status](https://travis-ci.org/reignite/burnout.io.svg?branch=master)](https://travis-ci.org/reignite/burnout.io)  [![Join the chat at https://gitter.im/reignite/burnout.io](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/reignite/burnout.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Burnout.io provides resources to prevent IT burnout. It has moved to: [burnoutio.readthedocs.io](https://burnoutio.readthedocs.io/en/latest/)

# Contributing

We value your ideas! If you'd like to help improve Burnout.io, do whatever works best for you:

* Open an [issue](https://github.com/reignite/burnout.io/issues/new),
* [Fork](https://github.com/reignite/burnout.io/fork) the project and submit a PR

## Things you should know:

* This project is written in [reStructuredText](http://docutils.sourceforge.net/docs/user/rst/quickstart.html) and Markdown
* Hosted by [Read the Docs](http://readthedocs.org/)
* Tested by rendering in [Sphinx](http://sphinx-doc.org/) on [Travis CI](https://travis-ci.org)

The only RST file in the project is the [`index.rst`](index.rst) file. All pages are written in Markdown.

If you are looking to add content, fix formatting, syntax, typos or other
wonderful things, please follow this process:

* Clone the project
* Install Sphinx: `pip install -r requirements.txt`
* Check out a branch to make your changes on: `git checkout --branch <my_topic>`
* Execute `make html` to build the docs in to `_build/`
* Make your changes
* Execute `make html` again and verify your changes don't cause any
  warnings/errors
* Commit with a descriptive message, and submit a pull request from your branch
  to `master`
* We'll review the change, and either merge it or provide some feedback. Community review is also encouraged.
