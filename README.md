# The Linked Data Event Streams specification

A Linked Data Event Stream is a collection of immutable objects (such as version objects, sensor observations or archived representation). Each object is described in RDF.

The objective of a Linked Data Event Stream is to allow consumers to replicate all of its items and to stay in sync when items are added.

The HTML specification can be accessed from [here](https://w3id.org/ldes/specification).

The JSON-LD context can be accessed from [here](https://w3id.org/ldes/context).

This specification uses [TREE](https://w3id.org/tree/specification) for its collection and fragmentation features, which in its turn is compatible to other specifications such as Activity Streams, DCAT-AP, LDP or Shape Trees.

If you are new to the concept of Linked Data Event Stream or Linked Data, [this short training](https://academy.europa.eu/courses/publishing-data-with-linked-data-event-streams-why-and-how) introduces the main concepts.

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/) and then run `bikeshed watch eventstreams.bs`

## Contributions

 * [Create an issue](https://github.com/SEMICeu/LinkedDataEventStreams/issues/new/choose) first
 * Gather community input, either by asking input from the editors via email, either via the github issue, either via the [Matrix chat channel](https://matrix.to/#/#ldes:chat.semantic.works)
 * Open a pull request extending the specification

## Changelog

 * 2023-04-28 - Point in Time retention policy has been added
 * 2022-07-01 - tree:ViewDescription was introduced as a concept


## Acknowledgements

This work is financed by the [Interoperable Europe (SEMIC) programme](https://joinup.ec.europa.eu/interoperable-europe) of the European Commission
