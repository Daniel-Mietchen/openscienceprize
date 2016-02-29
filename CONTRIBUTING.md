# Contributing

`openscienceprize` is an open source project, and we welcome contributions of all kinds

To report a bug, open an issue on our [issue tracker][issues].

Contributors to the project are required to follow the [code of
conduct](CONDUCT.md).

By contributing, you are agreeing that we may redistribute your work under
[these licenses][license].

We use the [fork and pull][gh-fork-pull] model to manage changes. More information
about [forking a repository][gh-fork] and [making a Pull Request][gh-pull].

To contribute to this repository:

1. fork [the project repository](https://github.com/everpub/openscienceprize/).
   Click on the 'Fork' button near the top of the page. This creates a copy of
   the code under your account on the GitHub server.
2. clone this copy of the repository to your local disk:

        $ git clone git@github.com:YourLogin/openscienceprize.git
        $ cd openscienceprize

2. create a new branch in your clone `git checkout -b my-new-branch`. Never
   work in the ``master`` branch!
4. Work on this copy on your computer using Git to do the version
   control. When you're done editing, do:

          $ git add modified_files
          $ git commit

   to record your changes in Git, then push them to GitHub with:

          $ git push -u origin my-new-branch

Finally, go to the web page of your fork of the `openscienceprize` repo,
and click 'Pull request' to send your changes to the maintainers for
review. This will send an email to the committers.

There is one additional rule: no one can merge their own pull requests, someone
else has to press the button.

[issues]: https://github.com/everpub/openscienceprize/issues
[license]: LICENSE
[gh-fork]: https://help.github.com/articles/fork-a-repo/
[gh-pull]: https://help.github.com/articles/using-pull-requests/
[gh-fork-pull]: https://help.github.com/articles/using-pull-requests/#fork--pull
