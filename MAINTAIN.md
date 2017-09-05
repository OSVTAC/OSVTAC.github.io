Site Maintenance
================

This document contains instructions for maintaining the site.

The site uses [GitHub Pages](https://pages.github.com/) with a slightly
customized version of GitHub's
["slate"](https://github.com/pages-themes/slate) theme.

Running and previewing the site locally requires installing
[Jekyll][jekyll-github] (a command-line tool), which in turn requires
having [Ruby][ruby].


Setup
-----

Install a current version of [Ruby][ruby]. As of August 2017, the latest
stable version was 2.4.1.

We recommend using [rvm](https://rvm.io/) to install and manage the
versions of Ruby installed on your machine.

You can check what version of Ruby you are currently using by running:

    $ ruby --version

With rvm, you can list all of your installed Ruby versions with:

    $ rvm list

From the repository root--

    $ bundle install

The command above installs each of the needed Ruby gems (project
dependencies), using the version numbers specified in `Gemfile.lock`.


Cloning the repository
----------------------

To clone a copy of the repository:

    $ git clone git@github.com:OSVTAC/OSVTAC.github.io.git
    $ git submodule update --init --recursive

The `git submodule` command is needed because the site uses Git
[submodules][git-submodules] to include things like binary files (e.g. PDF's)
and the committee's approved project recommendations, which live in a
[separate repository][recommendations-repo].

Running Locally
---------------

To run and preview the site locally, run the following from the
repo root:

    $ bundle exec jekyll serve

This writes the generated pages to a subdirectory called `_site`.

Then browse to: [http://127.0.0.1:4000](http://127.0.0.1:4000).


Deploying
---------

Pushing new commits to the master branch will automatically update the
rendered page on GitHub pages.

You can see whether this was successful by looking for a green check mark
next to the commit in GitHub's [commit history][site-commits] UI.

[git-submodules]: https://git-scm.com/book/en/v2/Git-Tools-Submodules
[jekyll-github]: https://jekyllrb.com/docs/github-pages/
[recommendations-rendered]: https://osvtac.github.io/recommendations/index
[recommendations-repo]: https://github.com/OSVTAC/project-recommendations
[ruby]: https://www.ruby-lang.org
[site-commits]: https://github.com/OSVTAC/OSVTAC.github.io/commits/master
