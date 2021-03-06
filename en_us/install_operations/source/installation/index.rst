.. _Installing and Starting the Open edX Platform:

######################################################
Installing and Starting the Open edX Platform
######################################################

This section provides information about options for installing and
starting the Open edX platform.
There is one production-like installation option, referred to as Native,
and a pair of development environment installation options
which install the Open edX software using Docker.

*************
Prerequisites
*************

These installation options require an understanding of the
following items.

* Basic terminal usage. If you are using a Mac computer, see
  `Introduction to the Mac OS X Command Line`_.
* Diagnosing and fixing failures may involve many different technologies and
  skills. It will help to know these things.

  - The basics of how Python web applications are built, installed, and
    deployed.

  - How to manage a Linux system, including supervisor.

  - The basics of configuration management and automation.  We use `Ansible`_
    to automate the installation process.

*******************
Native Installation
*******************

The Native installation installs the Open edX software on your own Ubuntu 16.04
machine in a production-like configuration. Details are at the `Open edX
Native Installation`_ page on the edX wiki.

********
Devstack
********

Devstack is a deployment of the Open edX platform within a set of Docker 
containers designed for local development. Running the Open edX platform 
locally allows you to discover and fix system configuration issues early in 
development.

Devstack simplifies certain production settings to make development more
convenient. For example, `nginx`_ and `gunicorn`_ are disabled in Devstack;
Devstack uses Django's ``runserver`` instead.

You can install the Open edX developer stack (just known as **Devstack**)
or the Open edX analytics developer stack (**Analytics Devstack** or just **Analyticstack**).

=====================
Devstack Installation
=====================

To run either Devstack or Analytics Devstack, see the `devstack`_ repository.

You can run Devstack or Analytics Devstack on Linux or macOS. See the
`Docker`_ downloads page for information about the operating systems and
architectures on which you can run Docker.
Devstack using `Docker for Windows`_ has not been tested and it is not
supported.
For more information about Docker, see the `Docker documentation`_.

==================
Analytics Devstack
==================

Some users might want to develop Analytics features on their instance of the
Open edX platform. Because of the large number of dependencies needed to
develop extensions to Analytics, edX has created a modified version of Devstack
that provides the services and tools needed to modify the
Open edX Analytics Pipeline.

For information on running Analytics Stack,
see the `Getting Started on Analytics`_ document in the devstack repository.

Insights and the Analytics Data API are currently not included in
Analytics Devstack.

.. include:: ../../../links/links.rst
