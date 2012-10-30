Gmaps-ify your data!
====================

.. author: Matthew Turk <matthewturk@gmail.com>

.. date: 1307671728

A couple of us have been working on a comprehensive notebook web GUI for yt.
It's not ready yet.

BUT!  In advance of that, we've rolled a portion of that into something called
the 'mapserver' into the development branch.  This is a small, standalone
webapp that implements a rendered-on-the-fly google maps interface in yt.  To
run it, just go into a directory that has some data, and run:

.. code:: bash

   yt mapserver DD0054/DD0054

(where 'DD0054/DD0054' is the same thing you'd feed to 'load' in a script.)
You can run with ``--help`` to see some options, but what it comes down to is that
this will slice, but if you want to project, just do ``-p`` like so:

.. code:: bash

   yt mapserver -p DD0054/DD0054

This will spawn a webserver on port 8080 which you can then hit in a browser.
You'll have to forward an SSH tunnel if you're on a remote machine, but that's
just a matter of logging in with ``ssh -L 8080:localhost:8080``.  When you're
done, just hit Ctrl-C and it'll quit.

.. attachment-image:: yt_mapserver.png

Anyway, I think this is pretty cool, and hopefully you will too.  If you run
into any bugs, report them either with 'yt bugreport' or by going to
`http://hg.enzotools.org/yt/issues/new <http://hg.enzotools.org/yt/issues/new>`_ .

