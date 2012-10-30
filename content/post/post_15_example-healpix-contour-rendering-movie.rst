Example HEALpix Contour Rendering Movie
=======================================

.. author: Sam Skillman <samskillman@gmail.com>

.. date: 1298290861

In response to Matt's `post <http://blog.enzotools.org/yt-development-healpix-
and-contour-tree>`_ on the HEALpix rendering update, I thought it would be
worth posting an example movie.  This shows the all-sky rendering of an
observer moving from the front face of a simulation through the volume to the
back face.  The test simulation is 32 Mpc/h on a side with 64^3 root grid cells
and up to 4 levels of refinement.  At the start it looks like a disc because
the entire simulation is in front of the camera and by the end it is all around
the sides, indicating the simulation is behind the camera.  Enjoy!

:attachment:`all_sky.mov|Download movie`
