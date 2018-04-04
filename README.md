# phptrace
Start php-script in strace as if it where in the browser

## Getting started

Before start install php-cgi whith:

```
apt-get install php7.0-cgi
```
or
```
yum install php7-cgi
```
or something.

Start phptrace:

```
./phptrace -u http://www.test.com/var/www/test.php
```

Attention: script path in URL must point to the actual path to file ( /var/www/test.php or something )
