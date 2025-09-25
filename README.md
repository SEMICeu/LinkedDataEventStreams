# The Linked Data Event Streams specification

Linked Data Event Streams (LDES) is an initiative to, as a data publisher, find a balance between publishing your data using a as-complete-as-possible set of querying APIs and a data dump. We propose an event stream as the base API, and want to make it as light-weight as possible to host one.

LDES includes:
 * A [vocabulary](https://w3id.org/ldes) that introduces terms to talk about an `ldes:EventStream`
 * An example JSON-LD context that can be accessed from [here](https://w3id.org/ldes/context). It includes the JSON labels we recommend to use in JSON-LD documents. This document may however change over time and does not come with any waranties cfr. uptime. When building for a production environment, do thus not use this URL as an external context.
 * A [consumer oriented specification](https://w3id.org/specification). You can use this spec if you want to implement an LDES client or consumer pipeline.
 * A [server primer](https://w3id.org/ldes/server-primer) that you can consult when building an LDES as a data provider.

The LDES specification uses the W3C [TREE hypermedia specification](https://w3id.org/tree/specification) for creating paginated search tree of event stream pages.

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/) and then run `bikeshed watch eventstreams.bs`

## Contributions

 * [Create an issue](https://github.com/SEMICeu/LinkedDataEventStreams/issues/new/choose) first
 * Gather community input, either by asking input from the editors via email, either via the github issue, either via the [Matrix chat channel](https://matrix.to/#/#ldes:chat.semantic.works)
 * Open a pull request extending the specification

## Changelog

 * 2025-11-25: v1.0 launched: redesignd retention policies, a client algorithm, a server primer, etc.
 * 2021-03-15: v0.1 launched: an initial design of the vocabulary with retention policies

## Acknowledgements

This work is financed by the [Interoperable Europe (SEMIC) programme](https://joinup.ec.europa.eu/interoperable-europe) of the European Commission
