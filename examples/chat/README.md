Cortex is a Django extension designed to (hopefully) make
realtime Django painless.

The goal is to establish a one-to-one correspondence between
Backbone.js models and Django models and allow changes to be
synced between client and server in realtime.

Most of the ideas are inspired by Now.js ( http://nowjs.com ) but
translated into Pythonic API.

Directions:
===========

Build your virtualenv:

    $ cd cortex
    $ virtualenv --no-site-packages env
    $ source env/bin/activate

Install neccesary packages:

    $ pip install -r requirements.txt 

Run:
    
    $ python run.py

Point your browser to localhost:8080

Credits:
========

* Capsule - HenrikJoreteg ( https://github.com/andyet/Capsule )
* backbone, underscore - Jeremy Ashkenas ( https://github.com/jashkenas )
* gevent-socketio - Jeffrey Gelens ( https://bitbucket.org/Jeffrey/gevent-socketio )

Capsule is modified from the original, the server side code is
stripped.

And yes, the name is Firefly reference.