=======================
Intro to Virtualization
=======================

'I herd U liked computers, so I put a computer in your computer so you can compute while you compute'

These are the slides for an introductory overview of virtualization, and demonstration and workshop using VirtualBox_ and Vagrant_.

Usage
=====

Generated HTML slides are excluded by the .gitignore in this repository, so they must be generated dynamically.

To use these slides:
  1. Install Sphinx_ and Hieroglyph_.
  2. Run either `make slides` if you are on a machine with 'make' installed, `make.bat` on Windows, or `sphinx-build -b slides . ./_build/slides`.
  3. Open _build/slides/index.html in a browser.

License
=======
This project is released under the Apache 2.0 license found in the LICENSE file.

Contributing
============

Presentation contents are in index.rst.
Use the latest stable versions of (currently) Python 2, Sphinx, and Hieroglyph, and make Pull Requests so the community benefits. Feel free to include additional content, but the target is 2 hours including the workshop.

.. _Hieroglyph: http://hieroglyph.io/
.. _Sphinx:     http://sphinx-doc.org/
.. _VirtualBox: http://www.virtualbox.org/
.. _Vagrant:    http://www.vagrantup.com
