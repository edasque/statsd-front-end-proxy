statsd-front-end-proxy
======================

websocket communications based functional proxy to statsd
--

The goal is to offer a javascript front-end API that mimicks the Java statsd API and communicates through websocket to a proxy server that forwards the requests to a statsd server, all with non blocking calls.

  - Type some Markdown text in the left window
  - See the HTML in the right
  - Magic

Version
----

0.1

TODO
-----------

* create a client side API rather than relying on direct websocket calls
* handle parameter verifications on the server side
* add unit testing