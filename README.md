# OpenShift Memcached Cartridge

The `memcached` cartridge provides [Memcached](http://www.memcached.org/) on OpenShift, to install  create your app and run:

	rhc cartridge add https://raw.githubusercontent.com/Microtronic/openshift-cartridge-memcached/master/metadata/manifest.yml --app [APP]

## Environment Variables

The `memcached` cartridge provides following environment variables:

    OPENSHIFT_MEMCACHED_HOST         The Memcached IP address
    OPENSHIFT_MEMCACHED_PORT         The Memcached port
