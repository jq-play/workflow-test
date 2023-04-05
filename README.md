# MODL: Modular Ontology Design Library

https://dase.cs.wright.edu/content/modl-modular-ontology-design-library

DOI for v1.0 [![DOI](https://zenodo.org/badge/178051913.svg)](https://zenodo.org/badge/latestdoi/178051913)

v2.0 forthcoming.

## MODL

Here be OWLs.

### The Patterns

-   Causal Event
-   Data Transformation
-   Event
-   Explicit Typing
-   Hierarchical Cell Features
-   Identifier
-   Name Stub
-   Participant Role
-   Part-whole
-   Provenance
-   Quantities
-   Reification
-   Sequence
-   Spatial Extent
-   Spatiotemporal Extent
-   Stub
-   Temporal Extent
-   Trajectory
-   Tree

### OPLa Ontology

MODL is described by a top level OPLa ontology. It can be found [here](./modl/modl.owl).

## Documentation

The documentation itself is structured as follows.

1. Motivation
2. Overview
3. Patterns
4. Schema Diagram
5. Summary
6. Axiomatization
7. Explanations
8. Competency Questions

### Git Hook

In order for the git hook to work properly, this command needs to be executed:

```bash
git config --local core.hooksPath .githooks/
```

This will ONLY WORK on git version 3.9.1 and above. (3.09 to be more specific, so 3.10 and above is fine)
