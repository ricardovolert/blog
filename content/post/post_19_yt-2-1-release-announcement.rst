yt 2.1 Release Announcement
===========================

.. author: Sam Skillman

.. date: 1302256620

We are proud to announce the release of yt version 2.1.  This release includes
several new features, bug fixes, and numerous improvements to the code base and
documentation.  At the yt homepage, `http://yt.enzotools.org/
<http://yt.enzotools.org/>`_ , an installation script, a cookbook,
documentation and a guide to getting involved can be found.

yt is an analysis and visualization toolkit for Adaptive Mesh Refinement data.
yt provides full support for Enzo, Orion, and FLASH codes, with preliminary
support for RAMSES, ART, Chombo, CASTRO and MAESTRO codes.  It can be used to
create many common types of data products such as:

   * Slices
   * Projections
   * Profiles
   * Arbitrary Data Selection
   * Cosmological Analysis
   * Halo finding
   * Parallel AMR Volume Rendering
   * Gravitationally Bound Objects Analysis

There are a few major additions since yt-2.0 (Released January 17, 2011), including:

   * Streamlines for visualization and querying
   * A treecode implementation to calculate binding energy
   * Healpix / all-sky parallel volume rendering
   * A development bootstrap script, for getting going with modifying and contributing
   * CASTRO particles
   * Time series analysis

Documentation: `http://yt.enzotools.org/doc/ <http://yt.enzotools.org/doc/>`_

Installation: `http://yt.enzotools.org/doc/advanced/installing.html#installing-yt <http://yt.enzotools.org/doc/advanced/installing.html#installing-yt>`_ 

Cookbook: `http://yt.enzotools.org/doc/cookbook/recipes.html <http://yt.enzotools.org/doc/cookbook/recipes.html>`_

Get Involved: `http://yt.enzotools.org/doc/advanced/developing.html#contributing-code <http://yt.enzotools.org/doc/advanced/developing.html#contributing-code>`_
 
If you can't wait to get started, install with: 

.. code:: bash

   $ wget http://hg.enzotools.org/yt/raw/stable/doc/install_script.sh
   $ bash install_script.sh

Development has been sponsored by the NSF, DOE, and University
funding.  We invite you to get involved with developing and using yt!
