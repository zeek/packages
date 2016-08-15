.. _bro/packages repository: https://github.com/bro/packages
.. _Bro Package Manager: https://github.com/bro/package-manager
.. _Bro package: http://bro-package-manager.readthedocs.io/en/stable/package.html
.. _package index file: http://bro-package-manager.readthedocs.io/en/stable/source.html#package-index-files

Bro Package Source
==================

This is the default package source for the `Bro Package Manager`_.

Package Submission Process
--------------------------

To submit a `Bro package`_ use the following process (please only
submit your own work/packages):

#. Host your package's git repository at a public location.
   E.g. put it on GitHub.
#. Fork this `bro/packages repository`_ on GitHub.
#. Create a directory within your fork that with a name that uniquely
   identifies you.  E.g. if you're hosting packages on GitHub, name
   the directory the same as your GitHub username.  If you're hosting
   it somewhere else, you could use a domain name or organization name
   for the directory.
#. Put a `package index file`_ within the directory you just made.
   See the `Suggested Package Tags`_ section for ideas on what to put
   in the package index ``tags`` field.
#. Commit/push the changes you made to your fork.
#. Submit a *pull request*.

Suggested Package Tags
----------------------

- bro scripting

  - intel
  - geolocation
  - file analysis
  - sumstats
  - input
  - logging
  - notices

- *<network protocol name>*

- *<file format name>*

- signatures

- bro plugin

  - protocol analyzer
  - file analyzer
  - bifs
  - packet source
  - packet dumper
  - input reader
  - log writer

- broctl plugin

