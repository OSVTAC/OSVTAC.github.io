Site Maintenance
================

This document contains instructions for maintaining the site.

The site uses [GitHub Pages](https://pages.github.com/) with a slightly
customized version of GitHub's
["slate"](https://github.com/pages-themes/slate) theme.


Setup
-----

Install a current version of [Ruby](https://www.ruby-lang.org).
As of August 2017, the latest stable version was 2.4.1.

We recommend using [rvm](https://rvm.io/) to install and manage the
versions of Ruby installed on your machine.

You can check what version of Ruby you are currently using by running:

    $ ruby --version

With rvm, you can list all of your installed Ruby versions with:

    $ rvm list

From the repository root--

    $ bundle install

The above installs the version of each needed gems (project dependency),
as specified in `Gemfile.lock`.


Running Locally
---------------

To run and preview the site locally, run the following from the
repo root:

    $ bundle exec jekyll serve

This writes the generated pages to a subdirectory called `_site`.


Deploying
---------

Pushing new commits to the master branch will automatically update
the rendered page on GitHub pages.

You can see whether this was successful by looking for a green
check mark next to the commit in GitHub's UI.
