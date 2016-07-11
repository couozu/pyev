.. _examples:


.. title:: Examples

.. currentmodule:: pyev


Basic usage
***********

.. literalinclude:: basic_usage.py


An echo server
**************

This is a *simplified* example of how you could start building a socket server,
it is not meant to demonstrate performance (which is highly dependant on the
platform/backend used, for example: on Linux with ``epoll`` you shouldn't use
only one watcher for reading and writing events in the Connection object).

.. literalinclude:: echo_server.py
