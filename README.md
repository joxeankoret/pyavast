PyAvast
=======

Python bindings for the "new linux Avast server product line for 2014".
See this URL for more details about this version:

   http://forum.avast.com/index.php?topic=145973.0

The bindings require the Linux Avast daemon to be running in the same
machine. They will connect to the local Unix socket /var/run/avast/scan.sock
where the Avast daemon is listening for client connections.

Features
========

The current bindings offer the following features:

 * Scanning files and/or directories.
 * Checking URLs.
 * Get and set the list of enabled or disabled compressors.
 * Set the files or paths to exclude.

Contact
=======

Copyright (c) 2014 Joxean Koret, <joxeankoret AT yahoo DOT es>
