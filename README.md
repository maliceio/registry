registry
========

> Malice Plugin Registry

___

This contains all of the registered Malice plugins available for download.

Plugin Submission Process
-------------------------

Use the following process to submit packages (please only submit your own work/packages):

1. Create a Malice plugin. Make sure to add a  `settings.toml`.
2. Host your package's git repository at a public location. E.g. put it on GitHub.
3. [Fork](https://github.com/maliceio/registry#fork-destination-box) this **maliceio/registry** repository on GitHub.
4. Create a directory within your fork named your GitHub username. If you're hosting it somewhere else, you could use a domain name or organization name for the directory.
5. Put a `plugin.index` file within the directory you just made.
6. Add a line for every `plugin repo` **url** along with the latest `git commit` **sha256** hash AND `docker image` version **tag**
6. Commit/push the changes you made to your fork.
7. Submit a [pull request](https://github.com/bro/packages/compare).
