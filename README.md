[![Documentation Status](https://readthedocs.org/projects/burnoutio-test/badge/?version=latest)](http://burnoutio-test.readthedocs.org/en/latest/?badge=latest)  [![Build Status](https://travis-ci.org/AaronSachs/burnout.io-test.svg?branch=master)](https://travis-ci.org/AaronSachs/burnout.io-test)  [![Join the chat at https://gitter.im/reignite/burnout.io](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/reignite/burnout.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Burnout.io](http://burnout.io) provides resources to prevent IT burnout.

## Contributing
We value your ideas! If you'd like to help improve Burnout.io, do whatever works best for you:
* Open an [issue](https://github.com/reignite/burnout.io/issues/new),
* [Fork](https://github.com/reignite/burnout.io/fork) the project and submit a PR,
* Send an [email](mailto:bemosior+burnoutio@gmail.com), or 
* Reach out on [twitter](https://twitter.com/BenjaminMosior).

###Things you should know:

* This project is written in [reStructuredText](http://docutils.sourceforge.net/docs/user/rst/quickstart.html)
* Hosted by [Read the Docs](http://readthedocs.org/)
* Tested by rendering in [Sphinx](http://sphinx-doc.org/) on [Travis CI](https://travis-ci.org)

This is the only Markdown file in the repository, as it's not meant to be
included in the documentation itself.

If you are looking to add content, fix formatting, syntax, typos or other
wonderful things, please follow this process:

* Install Sphinx: `easy_install Sphinx sphinx_rtd_theme` or `pip install -r requirements.txt`
* Fork the repository to your own account
* Check out a branch to make your changes on: `git checkout --branch <my_topic>`
* Execute `make html` to build the docs in to `_build/`
* Make your changes
* Execute `make html` again and verify your changes don't cause any
  warnings/errors
* Commit with a descriptive message, and submit a pull request from your branch
  to `master`
* We'll review the change, and either merge it or provide some feedback. Community review is also encouraged.
