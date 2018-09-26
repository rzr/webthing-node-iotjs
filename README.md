# WEBTHING-IOTJS #

[![license](https://img.shields.io/badge/license-MPL--2.0-blue.svg)](LICENSE)
[![GitHub forks](https://img.shields.io/github/forks/rzr/webthing-iotjs.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/rzr/webthing-iotjs/network/)
[![Build Status](https://travis-ci.org/rzr/webthing-iotjs.svg?branch=master)](https://travis-ci.org/rzr/webthing-iotjs)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frzr%2Fwebthing-iotjs.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Frzr%2Fwebthing-iotjs?ref=badge_shield)


## DISCLAIMER: ##

Webthing-iotjs is derived of webthing-node project (supporting Node.js)
but adapted for IoT.js runtime (based on JerryScript engine for constrained devices).

This downstream project plans to keep aligned to upstream and only focus on IoT.js port.

New contributions should be submitted to webthing-node first
and then should land here (once rebased on webthing-node's master branch).


## BASIC USAGE: ##

After installing IoT.js program on your system,
you can get started by running the "Simplest Thing"
which is just simulating an actuator (LED, switch, relay...).

```
iotjs -h

iotjs example/simplest-thing.js 
# Usage:
# 
# iotjs example/simplest-thing.js [port]
# 
# Try:
# curl -X PUT -H 'Content-Type: application/json' --data '{"on": true }' http://localhost:8888/properties/on
```

Then thing can be connected to Mozilla IoT gateway using the Thing Web URL adapter.


## GUIDE: ##

For more insights and details please guide:

* https://github.com/rzr/webthing-iotjs/wiki


## REFERENCES: ##

* https://github.com/mozilla/webthing-node
* https://github.com/rzr/webthing-iotjs/wiki
* https://s-opensource.org/2018/06/21/webthing-iotjs/


## LICENSE: ##

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frzr%2Fmastodon-lite.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Frzr%2Fmastodon-lite?ref=badge_large)