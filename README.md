PROTOTYPE / WIP

# Setting up the environment

1. Install nginx
1. Install Etherpad
1. ``cd etherpad-lite && git checkout socket-padid-in-header``
1. Bring up one Etherpad instance on localhost:9001
1. Bring up one Etherpad instance on localhost:9002
1. Copy this config into your nginx config ``cp etherpad /etc/nginx/sites-enabled``
1. Reload nginx ``/etc/init.d/nginx reload``

# License

Apache 2
