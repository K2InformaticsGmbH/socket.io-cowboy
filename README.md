socket.io-cowboy
================

### Overview

[![Build Status](https://travis-ci.com/K2InformaticsGmbH/socket.io-cowboy.svg?branch=master)](https://travis-ci.com/K2InformaticsGmbH/socket.io-cowboy)
[![Coverage Status](https://coveralls.io/repos/github/K2InformaticsGmbH/socket.io-cowboy/badge.svg?branch=master)](https://coveralls.io/github/K2InformaticsGmbH/socket.io-cowboy?branch=master)

This project is an open-source Erlang implementation of [Socket.IO](http://socket.io/) server. Based on [Cowboy](https://github.com/extend/cowboy).

Licensed under the Apache License 2.0.

### Feauters

* Partial Supports 0.7+ version of [Socket.IO-client](https://github.com/LearnBoost/socket.io-client) up to latest - 0.9.6 (doesn't support ack and events)
* Supports xhr-polling transport
* Supports websocket transport
* Supports SSL

#Usage example

The example you can find in demo directory. Just make and execute start.sh script. Url to check: http://localhost:8080/index.html
