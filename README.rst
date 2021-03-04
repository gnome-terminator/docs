Terminator Manual (GTK3)
========================

Fully fleshed-out manual for Terminator.

The main Terminator icon was created by Cory Kontros, and provided under the `CC-BY-SA`_ licence.

This Manual and included images are wholly new pieces created by the current maintainer Steve Boddy, and are distributed under the `CC-BY-SA`_ licence, as are the horrific attempts by yours truly at using Cory’s icon to provide page identities.

How to Build
------------

* Install the shinx package and the ReadTheDocs theme ``pip3 install sphinx sphinx-rtd-theme`` 
* Clone this repository
* ``cd docs/source``
* Build the HTML pages: ``make html``

For Python2.X:
~~~~~~~~~~~~~~

* serve up the web pages: ``cd _build/html && python -m SimpleHTTPServer 4000``
* Review the results at http://localhost:4000

For Python3.X:
~~~~~~~~~~~~~~

* serve up the web pages: ``cd _build/html && python3 -m http.server 4000``
* Review the results in your browser at http://localhost:4000

Imported from Launchpad: https://code.launchpad.net/~gnome-terminator/terminator/manual-gtk3

.. _CC-BY-SA: http://creativecommons.org/licenses/by-sa/4.0/

