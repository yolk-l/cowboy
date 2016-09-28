Cowboy
======

Cowboy is a small, fast and modular HTTP server written in Erlang.

Goals
-----

Cowboy aims to provide a **complete** HTTP stack in a **small** code base.
It is optimized for **low latency** and **low memory usage**, in part
because it uses **binary strings**.

Cowboy provides **routing** capabilities, selectively dispatching requests
to handlers written in Erlang.

Because it uses Ranch for managing connections, Cowboy can easily be
**embedded** in any other application.

Cowboy is **clean** and **well tested** Erlang code.

Sponsors
--------

The project is currently sponsored by
[Sameroom](https://sameroom.io).

The original SPDY implementation was sponsored by
[LeoFS Cloud Storage](http://leo-project.net/leofs/).
It has since been superseded by HTTP/2.

Online documentation
--------------------

 *  [User guide](http://ninenines.eu/docs/en/cowboy/2.0/guide)
 *  [Function reference](http://ninenines.eu/docs/en/cowboy/2.0/manual)

Offline documentation
---------------------

 *  While still online, run `make docs`
 *  Function reference man pages available in `doc/man3/` and `doc/man7/`
 *  Run `make install-docs` to install man pages on your system
 *  Full documentation in Markdown available in `doc/markdown/`
 *  Examples available in `examples/`

Getting help
------------

 *  Official IRC Channel: #ninenines on irc.freenode.net
 *  [Mailing Lists](http://lists.ninenines.eu)
 *  [Commercial Support](http://ninenines.eu/support)
