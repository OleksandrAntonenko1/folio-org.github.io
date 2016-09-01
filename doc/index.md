---
layout: page
title: Documentation
---

Documentation for the various components of FOLIO is in continuous
development. Since the system is composed of many separate components,
each component is documented individually. The best place to start is
with the early chapters of the
[Okapi Guide and Reference](https://github.com/folio-org/okapi/blob/master/doc/guide.md),
which describe the system as a whole and explain how the parts fit
together.

In the context of those early chapters, you may then wish to go on to:

## Core Code

Most important is the 
[Okapi Guide and Reference](https://github.com/folio-org/okapi/blob/master/doc/guide.md),
which after the introductory sections already described goes into
detail about the Okapi API Gateway that controls a FOLIO system.

The
[contribution guidelines](https://github.com/folio-org/okapi/blob/master/CONTRIBUTING.md)
for Okapi also pertain to FOLIO more broadly, and explain how to get involved.

## Modules

[The Folio-Sample-Modules
guide](https://github.com/folio-org/folio-sample-modules/blob/master/README.md)
contains an explanation of FOLIO modules, a "getting started" guide,
and some sample module code.

The
[_Further reading_ section of that document](https://github.com/folio-org/folio-sample-modules/blob/master/README.md#further-reading)
contains links to other in-progress modules whose documentation may be
of interest.

## User Interface

The FOLIO user-interface toolkit is called Stripes. It is described in
[Stripes: a modular toolkit for user
interfaces](https://github.com/folio-org/stripes-experiments/blob/master/stripes-core/OVERVIEW.md)
and instruction for running a Stripes-based UI can be found in
[the Stripes Core README file](https://github.com/folio-org/stripes-experiments/blob/master/stripes-core/README.md).

Related to this,
[okapi-stripes](https://github.com/folio-org/okapi-stripes/blob/master/README.md)
describes a special Okapi module used to generate Stripes-based UIs
for individual FOLIO tenants.

## API reference

These API specification are automatically generated from the relevant
[RAML](http://raml.org/) files, and specify how client modules may
access the functionality provided by these important core modules.

* [Patrons API](http://foliodocs.s3-website-us-east-1.amazonaws.com/raml/dist/patrons.html)
* [Bib API](http://foliodocs.s3-website-us-east-1.amazonaws.com/raml/dist/bibs.html)
* [Configurations API](http://foliodocs.s3-website-us-east-1.amazonaws.com/raml/dist/config.html)
* [Item API](http://foliodocs.s3-website-us-east-1.amazonaws.com/raml/dist/items.html)

Related to this is the [repository of RAML
files](https://github.com/folio-org/raml), including JSON Schemas,
traits and resource types centralized for re-usability.



<!--
TODO add link to Stripes docs
-->


