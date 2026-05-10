# The Linked Data Event Streams specification

<p align="right">
  <img src="https://semiceu.github.io/LinkedDataEventStreams/assets/logo-ldes.svg" alt="Linked Data Event Streams" width="140">
</p>

Linked Data Event Streams (LDES) is an initiative that helps data publishers balance rich, queryable APIs with data dumps. We propose an event source published over HTTP as the base API and aim to make it as lightweight as possible to host one.

LDES includes:
 * A [vocabulary](https://w3id.org/ldes) that introduces terms for describing an `ldes:EventStream`
 * An example JSON-LD context, available [here](https://w3id.org/ldes/context). It includes the JSON labels we recommend for JSON-LD documents. This document may change over time and does not come with any uptime warranties. When building for a production environment, do not use this URL as an external context.
 * A [consumer-oriented specification](https://w3id.org/ldes/specification). You can use this specification to implement an LDES client or consumer pipeline.
 * A [server primer](https://w3id.org/ldes/server-primer) for building an LDES as a data provider.

The LDES specification uses the W3C [TREE hypermedia specification](https://w3id.org/tree/specification) for creating a paginated search tree of event stream pages.

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/) and then run `bikeshed watch eventstreams.bs`.

## Release strategy

The `master` branch is published to the `workingdraft/` folder on the `gh-pages` branch. The documents in that folder reflect the current state of `master` and use release-local links such as `context.jsonld`, `vocabulary.html`, and `server-primer.html`.

Official releases are created by the SEMIC team by creating a tag. Tagged versions are published under `releases/<tag>/`. Each release contains a snapshot of the generated specification, vocabulary, server primer, JSON-LD context, vocabulary Turtle file, and shared assets. The root files on `gh-pages` redirect to the latest tagged release, while the root `context.jsonld` and `vocabulary.ttl` files are symlinks to the latest release copies.

## Contributions

 * [Create an issue](https://github.com/SEMICeu/LinkedDataEventStreams/issues/new/choose) first
 * Gather community input by contacting the editors via email, using the GitHub issue, or joining the [Matrix chat channel](https://matrix.to/#/#ldes:chat.semantic.works)
 * Open a pull request extending the specification

## Changelog

 * 2026-05-10: editorial and publication improvements: added the SEMIC template, author/owner metadata, cross-links between latest, working draft, and archived releases, automated pipelines for stable releases and release overview pages, archived release assets, and updated UML/vocabulary diagrams.
 * 2025-11-25: release 1.0.0-alpha launched: redesigned retention policies, a client algorithm, a server primer, etc.
 * 2021-03-15: release 0.0.1 launched: an initial design of the vocabulary with retention policies

## Acknowledgements

This work is financed by the European Commission's [Interoperable Europe (SEMIC) programme](https://joinup.ec.europa.eu/interoperable-europe).
