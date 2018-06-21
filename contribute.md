Contribute
==========

We value your ideas! If you'd like to help improve Burnout.io, do
whatever works best for you:

-   Open an [issue]
-   [Fork] the project and submit a PR
-   Send an [email]
-   Reach out on [twitter]

Info for Contributing to Burnout.io
-----------------------------------

-   This project is written in [reStructuredText]
-   Hosted by [Read the Docs]
-   Tested by rendering in [Sphinx] on [Travis CI]

If you are looking to add content, fix formatting, syntax, typos or
other wonderful things, please follow this process:

-   Install Sphinx: `easy_install Sphinx sphinx_rtd_theme` or
    `pip install -r requirements.txt`
-   Fork the repository to your own account
-   Check out a branch to make your changes on:
    `git checkout --branch <my_topic>`
-   Execute `make html` to build the docs in to `_build/`
-   Make your changes
-   Execute `make html` again and verify your changes don't cause any
    warnings/errors
-   Commit with a descriptive message, and submit a pull request from
    your branch to `master`
-   We'll review the change, and either merge it or provide some
    feedback. Community review is also encouraged.

A quick note if you're adding a new heading:

Sphinx will error out if your title text is longer than the title
underline. For example:
`/projects/burnout.io/resources.rst:12: WARNING: Title underline too short.`

And when you look at the title, you see:

    This title is quite long...
    -----

Which will cause the error. Corrected, the tite would be more like:

    This title is quite long...
    -----------------------------------

Which will correct the issue. For any other issues you run into, hop
into the Gitter channel and one of us will help out.

[![Gitter Channel]]

Current Build Status
--------------------

[![Documentation Status]]

[![Travis Build Status]]

  [issue]: https://github.com/reignite/burnout.io/issues/new
  [Fork]: https://github.com/reignite/burnout.io/fork
  [email]: mailto:bemosior+burnoutio@gmail.com
  [twitter]: https://twitter.com/BenjaminMosior
  [reStructuredText]: http://docutils.sourceforge.net/docs/user/rst/quickstart.html
  [Read the Docs]: http://readthedocs.org/
  [Sphinx]: http://sphinx-doc.org/
  [Travis CI]: https://travis-ci.org
  [Gitter Channel]: https://badges.gitter.im/Join%20Chat.svg
  [![Gitter Channel]]: https://gitter.im/reignite/burnout.io
  [Documentation Status]: https://readthedocs.org/projects/burnoutio/badge/?version=latest
  [![Documentation Status]]: http://burnoutio.readthedocs.org/en/latest/?badge=latest
  [Travis Build Status]: https://travis-ci.org/reignite/burnout.io.svg
  [![Travis Build Status]]: https://travis-ci.org/reignite/burnout.io