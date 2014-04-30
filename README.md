CSProxy
=======
CSProxy is high performance socket proxy written in C#. It is an ideal candidate for implementing load-balancing for custom socket based applications. Currently it implements round-robin distribution algorithm. It supports node health monitoring, hot-addition/removal of nodes, reattempt to register bad-nodes and custom stat collection for logging.

It is known to pass over 1M requests to 20 nodes with under 20MB footprint.
