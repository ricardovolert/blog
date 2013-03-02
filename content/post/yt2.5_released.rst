yt 2.5 released!
================

.. author: John ZuHone <jzuhone@gmail.com>

.. date: 1362200264

We’re proud to announce the release of version 2.5 of the yt Project, http://yt-project.org/. The new version includes many new features, refinements of existing features, and numerous bugfixes.  We encourage all users to upgrade to take advantage of the changes.

yt is a community-developed analysis and visualization toolkit, primarily directed at astrophysical hydrodynamics simulations.  It provides full support for output from the Enzo, FLASH, Orion, and Nyx codes, with preliminary support for several others.  It provides access to simulation data using an intuitive python interface, can perform many common visualization tasks, and offers a framework for conducting data reductions and analysis of simulation data.

The most visible changes with the 2.5 release include:

   * Testing has been greatly expanded, including unit tests and answer testing.

   * The capabilities of the “Stream” frontend have been expanded. Uniform grid and   
      AMR-based data can be read into memory, and particle fields can be initialized.
   * The install script now provides for the optional installation of SciPy and the 
      Rockstar halo finder.
   * Surfaces can now be extracted and examined, as well as uploaded to 
     Sketchfab.com for interactive visualization in a web browser.
   * Support for the Athena code has been added.
   * Many, many improvements to PlotWindow.
   * Coordinate transformations have been sped up and streamlined, as well as 
     cylindrical and spherical fields.
   * Increased support for the IPython notebook.
   * Improved support for FLASH particle fields.
   * The volume rendering backend has been updated to use an alpha channel, fixing 
     parallel opaque volume renderings.
   * The AMRKDTree has been rewritten, allowing parallelism with other than 
     power-of-2 MPI processes, arbitrary sets of grids, and splitting of unigrids.

For a complete list of changes in this release, please visit the Changelog (http://yt-project.org/docs/2.5/changelog.html).

Information about the yt project, including installation instructions, can be found on the homepage: http://yt-project.org/

Development of yt has been sponsored by the NSF, the DOE, and various universities.  We develop yt in the open and encourage contributions from users who extend and improve the code.  We invite you to get involved with developing and using yt!
