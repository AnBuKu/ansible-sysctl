Changelog
=========

.. include:: includes/all.rst

**debops.sysctl**

This project adheres to `Semantic Versioning <http://semver.org/spec/v2.0.0.html>`__
and `human-readable changelog <http://keepachangelog.com/en/0.3.0/>`__.

The current role maintainer_ is ypid_.


`debops.sysctl master`_ - unreleased
---------------------------------------------

.. _debops.sysctl master: https://github.com/debops/ansible-sysctl/compare/v0.1.0...master


debops.sysctl v0.1.0 - 2016-09-04
---------------------------------

Added
~~~~~

- Moved sysctl parts from debops.console_ to the separate ``debops.sysctl``
  role. [ypid_]

- Ignore errors about unknown kernel parameters when ``cap_sys_admin`` is not
  in the Linux capability list to allow to configure container with the role.
  [ypid_]
