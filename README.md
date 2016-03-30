mosquitto-auth-plugin-http
==========================

A simple authentication plugin for the Mosquitto MQTT broker (http://mosquitto.org) which makes a
POST to an HTTP server for both username/password checks and ACL checks.

Inspired by the rabbitmq-auth-backend-http (https://github.com/simonmacmullen/rabbitmq-auth-backend-http)
and the mosquitto-auth-plugin-keystone (https://github.com/brc859844/mosquitto-auth-plugin-keystone).

### Requirements
Please install development headers of mosquitto and of json-c.
