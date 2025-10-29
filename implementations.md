# Implementations

## Overview

This page points to implementations of OGC API Publish-Subscribe Workflow.

## Implementations:

* [pycsw](#pycsw)
* [ldproxy](#ldproxy)

## pycsw

[pycsw](https://pycsw.org) is an OGC API - Records and CSW server implementation written in Python.

Part 1 is implemented on any transactions, publishing messages via MQTT using the following:
- autodiscovery as per Requirements Class Discovery
- message payload as per Requirements Class Message Payloads — CloudEvents (JSON)
- channels as per Clause 9: Channels (Informative)

Landing page:

* https://demo.pycsw.org/cite

More information can be found in the [documentation](https://docs.pycsw.org/en/latest/pubsub.html).

## ldproxy

[ldproxy](https://github.com/ldproxy/ldproxy) allows you to quickly set up Web APIs that make geospatial data available to others or to your own applications via HTTP.

PubSub support is implemented as a module to publish feature changes via MQTT.

More information can be found in the [documentation](https://docs.ldproxy.net/services/building-blocks/pubsub.html).
