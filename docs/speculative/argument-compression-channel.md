# Argument Compression as an Information-Channel Model

**Status:** speculative research note; not part of the established method.

## Idea

A possible formalization of normative compression treats a published argument as a lossy representation of a more fully explicated argument.

\[
A^* \xrightarrow{f_\theta} Y \xrightarrow{g_\phi} \hat A
\]

where:

- \(A^*\) = a fully reconstructed argument, including enthymematic premises and normative bridges;
- \(f_\theta\) = the linguistic/conceptual operation by which an argument is rendered in published discourse;
- \(Y\) = the published text;
- \(g_\phi\) = reconstruction by a reader/annotator;
- \(\hat A\) = the reconstructed argument.

The possible empirical object is therefore not "shortness" but the difference between the inferential structure of \(A^*\) and the structure explicitly represented in \(Y\).

## Possible measurements

Candidate measures include:

- proportion of reconstructed premises absent from the published text;
- proportion of normative vs. descriptive inferential structure omitted;
- graph/edge deletion between \(A^*\) and \(Y\);
- conditional uncertainty \(H(A^* \mid Y)\);
- information shared between classifications and normative conclusions, \(I(C;N)\).

A candidate "normative compression" measure might compare the information or inferential structure of normative components in \(A^*\) and \(Y\).

These are **candidate operationalizations, not validated measures**.

## Annotation possibility

Annotators could reconstruct the published argument by identifying:

1. explicit propositions;
2. implicit/enthymematic premises;
3. normative principles;
4. inferential relations;
5. alternative plausible reconstructions.

Annotator disagreement should be retained rather than necessarily adjudicated into a single "true" argument.

## Signal-processing analogy

The analogy suggests treating conceptual/rhetorical expression as an encoding operation and interpretation as decoding. The useful question is whether different kinds of argumentative information are systematically filtered or compressed.

The analogy should not be treated as evidence for the phenomenon.

## Open questions

- Can "fully explicated argument" be defined with sufficient inter-annotator reliability?
- Is normative compression distinguishable from ordinary rhetorical abbreviation?
- Can information loss be measured without building the result into the annotation scheme?
- Does the proposed measure predict anything independently interesting?
- Is the signal-processing formalism explanatory, or merely metaphorical?

## Provenance

Developed as a speculative extension of the normative-compression project in conversation on 2026-08-22. The idea should be reconstructed from this note before being promoted into theory, methods, or hypotheses.
