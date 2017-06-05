nginx
=====

NGINX is a free, open-source, high-performance HTTP server and reverse proxy,
as well as an IMAP/POP3 proxy server. NGINX is known for its high performance,
stability, rich feature set, simple configuration, and low resource consumption.

Samples
-------
```
include nginx
```
```
class { 'nginx':
  ensure => 'latest'
}
```

License
-------
GPL3

Contact
-------
breauxaj AT gmail DOT com