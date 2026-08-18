# Graph Model

The first formal model represents arguments as directed graphs.

## Expanded form

```text
P1 ─────┐
P2 ─────┼──> Classification ──> Normative Principle ──> Conclusion
P3 ─────┘
```

## Candidate compressed form

```text
P1 ─────┐
P2 ─────┼──> Classification ──> Conclusion
P3 ─────┘
```

The hypothesis is that some information represented by the missing normative node(s) is carried by the classification node or its conventional inferential role.

## Variables to explore

- V: number of vertices;
- E: number of edges;
- L: shortest/weighted path length;
- N: number of explicit normative nodes;
- C: classification centrality;
- D: description length of the graph;
- R: recoverable implicit normative content.

## Simulation requirement

Before corpus analysis, generate synthetic graphs with known compression levels. Verify that proposed metrics recover the known levels and do not mistake ordinary short arguments for compressed arguments.
