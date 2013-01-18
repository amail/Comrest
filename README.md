Comrest
=======

RESTful services for PHP. Used in various Web API's at Comfirm.

##### Background

At Comfirm we build a lot of Web API's.

For high-performance (high throughput/low memory/low latency) we've built a custom HTTP/API-server in C.
This is very specific and performs great for it's mission critical purpose, but it's a pain for productivity.

So for day-to-day development and for non mission critical API's, we needed something else...
Say hello to Comrest! A RESTful library for PHP that makes life easier. With just a few lines, it does what you want it to do!

Easily....

  * Add routes. Map routes to resources. Use namespacing and stop repeating yourself!
  * Add filters. Format, log or apply custom authentication schemes to routes. Apply filters to namespaces!
  * Map parameters from routes and easily pass data from the HTTP-request to your resource.
  * Create unit tests.
