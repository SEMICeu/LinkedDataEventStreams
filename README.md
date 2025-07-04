# The Linked Data Event Streams specification

A Linked Data Event Stream is a collection of immutable objects (such as version objects, sensor observations or archived representation). Each object is described in RDF.

The objective of a Linked Data Event Stream is to allow consumers to replicate all of its items and to stay in sync when items are added.

The HTML specification can be accessed from [here](https://w3id.org/ldes/specification).

An example JSON-LD context can be accessed from [here](https://w3id.org/ldes/context). It includes the JSON labels we recommend to use in JSON-LD documents. This document may however change over time and does not come with any waranties cfr. uptime. When building for a production environment, do thus not use this URL as an external context.

This specification uses [TREE](https://w3id.org/tree/specification) for its collection and fragmentation features, which in its turn is compatible to other specifications such as Activity Streams, DCAT-AP, LDP or Shape Trees.

If you are new to the concept of Linked Data Event Stream or Linked Data, [this short training](https://academy.europa.eu/courses/publishing-data-with-linked-data-event-streams-why-and-how) introduces the main concepts.

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/) and then run `bikeshed watch eventstreams.bs`

## Contributions

 * [Create an issue](https://github.com/SEMICeu/LinkedDataEventStreams/issues/new/choose) first
 * Gather community input, either by asking input from the editors via email, either via the github issue, either via the [Matrix chat channel](https://matrix.to/#/#ldes:chat.semantic.works)
 * Open a pull request extending the specification

## Changelog

In 2025 the LDES specification is being rewritten from a consumer oriented perspective, while adding functionalities. Check the releases for changelogs.

## Acknowledgements

This work is financed by the [Interoperable Europe (SEMIC) programme](https://joinup.ec.europa.eu/interoperable-europe) of the European Commission
