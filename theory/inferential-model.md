# Inferential Model

The project needs an explicit representation of claims before it can test compression.

## Basic argument graph

Represent a passage as a directed graph:

`premise nodes → classification node(s) → normative premise(s) → conclusion`

Alternative compressed graph:

`premise node(s) → classification node → conclusion`

The missing nodes in the compressed graph are the object of investigation. They may be absent because they are genuinely unnecessary, pragmatically recoverable, conventionally encoded, or simply omitted.

## Candidate graph variables

- node count;
- edge count;
- path length from empirical premises to normative conclusion;
- number of normative nodes;
- centrality of classificatory nodes;
- proportion of required premises explicit vs implicit;
- number of boundary-repair operations;
- number of competing classifications considered.

## Caution

Graph topology is not itself an argument analysis. The project must develop annotation rules for premise/conclusion identification and test interannotator agreement. Large-language-model extraction may assist discovery but should not be treated as ground truth.

## Key comparison

The primary contrast is not simply:

`long argument vs short argument`

but:

`explicit normative warrant vs normative warrant carried by classification`.

A short argument can be non-compressed; a long argument can be highly compressed if the classification carries the missing normative premises.
