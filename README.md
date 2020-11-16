PROTOTYPE / WIP

# Setting up the environment

1. Install nginx
1. Install Etherpad
1. ``cd etherpad-lite && git checkout referer-restriction-removal``
1. Bring up one Etherpad instance on localhost:9001
1. Bring up one Etherpad instance on localhost:9002
1. Copy this config into your nginx config ``cp etherpad /etc/nginx/sites-enabled``
1. Reload nginx ``/etc/init.d/nginx reload``
1. Visit http://yournginxip/p/one - edits should land on 9001
1. Visit http://yournginxip/p/two - edits should land on 9002

# TODO
- [ ] Debug why websocket isn't working and it's falling back to polling
- [ ] Map and sticky for sharding


# License

Apache 2
