.. _installsphinx:

--------------
Install Sphinx
--------------

Why install Sphinx local?
+++++++++++++++++++++++++

To check your created documents for Sphinx, and to be pushed on to the nutanixworkshop.com, you can install Sphinx compiler.

Installation
++++++++++++

.. note:: This document assumes the pre-requisite package Python has been installed

1. Open a commandline

2. Install Homebrew using:

   ``/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``

3. After the installation has been successful, run the command ``brew install sphinx-doc`` to get the the basics for sphinx

4. run the following commands and provide the logged in user's password

* sudo pip3 install sphinx

* sudo pip3 install sphinxcontrib-fulltoc

* sudo pip3 install sphinx-bootstrap-theme

* sudo pip3 install sphinx_fontawesome


After this installation, you can use the command sphinx-build to generate the HTML version of the created pages.
