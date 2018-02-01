# http-batch
HTTP request batching library for the client &amp; server

Client-server communication responsiveness can be drastically improved by reducing the client-server roundtrips.
However, sometimes it's just to possible to have fewer HTTP endpoints.

`http-batch` is a solution for optimizing the client-server transport by grouping together on the client side 
multiple requests into a single batch and providing and APIBatchingGateway server that knows how to execute the batched
requests and return the aggregated response.
