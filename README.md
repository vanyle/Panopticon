# Server Toy Project

A toy project to learn NestJS.
I'm going to be honest here: I am not very inspired for an idea of a
project that is only a backend, so I'm going to implement a monitoring system.

Features:

- CRUD API to add and remove "watch" target.
  A watch target is a hostname that we can ping. Example: google.com:80

- API to retreive stats about a target like uptime, ping, sitemap, etc...
- API to generate some cool SVG graph to show your friends the 99.999% uptime on homelab.

## Watch targets

Watch targets are made up of:

- A URL to watch.
- A list of properties to watch for like uptime, ping, etc...
- A list of paths
