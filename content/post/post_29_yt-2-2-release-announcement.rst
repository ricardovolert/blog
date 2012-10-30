yt-2.2 Release Announcement
===========================

.. author: Cameron Hummels <chummels@gmail.com>

.. date: 1314964560


(Please feel encouraged to forward this message to any other interested parties.)


We are proud to announce the release of yt version 2.2.  This release includes
several new features, bug fixes, and numerous improvements to the code base and
documentation.  At the new yt homepage, http://yt-project.org/ , an
installation script, a cookbook, documentation and a guide to getting involved
can be found.  We are particularly proud of the new GUI, entitled "Reason,"
which allows real-time exploration of datasets, and which can be used (locally
or remotely over SSH) with no dependencies other than a web browser.  A basic
demonstration of its usage can be found at:
http://vimeo.com/groups/ytgallery/videos/28506477 .

yt is a community-developed analysis and visualization toolkit for
astrophysical simulation data.  yt provides full support for Enzo, Orion, Nyx,
and FLASH codes, with preliminary support for the RAMSES, ART, and Maestro
codes.  It can be used to create many common types of data products such as:

   * Slices
   * Projections
   * Profiles
   * Arbitrary Data Selection
   * Cosmological Analysis
   * Halo finding
   * Parallel AMR Volume Rendering
   * Gravitationally Bound Objects Analysis

There are a few major additions since yt-2.1 (Released April 8, 2011), including:

   * New web GUI "Reason," designed for efficient remote usage over SSH tunnels
   * Command-line submission to the yt Hub (http://hub.yt-project.org/)
   * Absorption line spectrum generator for cosmological simulations
   * Support for the Nyx code
   * An order of magnitude speed improvement in the RAMSES support
   * Experimental interoperability with ParaView
   * Quad-tree projections, speeding up the process of projecting by up to an
     order of magnitude and providing better load balancing
   * "mapserver" for in-browser, Google Maps-style slice and projection
     visualization
   * Many bug fixes and performance improvements

With this release, we also unveil the yt Hub, an astrophysical
simulation-specific location for sharing scripts, analysis and visualization
tools, documents and repositories used to generated publications.  The yt Hub
has been designed to allow programmatic access from the command line, and we
encourage you to browse the current offerings and contribute your own.  The yt
Hub can be found at http://hub.yt-project.org/ .

Documentation: http://yt-project.org/doc/

Installation:http://yt-project.org/doc/advanced/installing.html

Cookbook: http://yt-project.org/doc/cookbook/recipes.html

Get Involved: http://yt-project.org/doc/advanced/developing.html

If you can’t wait to get started, install with:

.. code:: bash

   $ wget http://hg.yt-project.org/yt/raw/stable/doc/install_script.sh
   $ bash install_script.sh

Development has been sponsored by the NSF, DOE, and University funding.  We
invite you to get involved with developing and using yt!

Please forward this announcement to interested parties.

Sincerely,

The yt development team

