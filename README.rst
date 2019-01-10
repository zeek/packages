.. _zeek/packages repository: https://github.com/zeek/packages
.. _Zeek Package Manager: https://github.com/zeek/package-manager
.. _Zeek package: https://docs.zeek.org/projects/package-manager/en/stable/package.html
.. _package index file: https://docs.zeek.org/projects/package-manager/en/stable/source.html#package-index-files

Zeek Package Source
===================

This is the default package source for the `Zeek Package Manager`_.

Package Submission Process
--------------------------

Use the following process to submit packages (please only submit your
own work/packages):

#. Create a `Zeek package`_.  Make sure to set the ``tags``
   and ``description`` metadata fields to help people discover
   your package.
#. Host your package's git repository at a public location.
   E.g. put it on GitHub.
#. Fork this `zeek/packages repository`_ on GitHub.
#. Create a directory within your fork that with a name that uniquely
   identifies you.  E.g. if you're hosting packages on GitHub, name
   the directory the same as your GitHub username.  If you're hosting
   it somewhere else, you could use a domain name or organization name
   for the directory.
#. Put a `package index file`_ within the directory you just made.
#. Commit/push the changes you made to your fork.
#. Submit a *pull request*.
