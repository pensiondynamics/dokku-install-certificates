# dokku-install-certificates

[![Build Status](https://travis-ci.org/pensiondynamics/dokku-install-certificates.svg?branch=master)](https://travis-ci.org/pensiondynamics/dokku-install-certificates)

Installs root ca to ```/usr/local/share/ca-certificates```. Useful for self-signed dev environments, or non-public production environments.

Place any \*.crt file in the ```/home/dokku/APP/install-certificates``` directory.

For example:

Save the contents of your root ca to ```/home/dokku/APP/install-certificates/your-ca.crt```.

Note the crt extension.
