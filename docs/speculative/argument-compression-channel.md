# Argument Compression as an Information-Channel Model

**Status:** speculative research note; not part of the established method.

## General idea

Treat conceptual/rhetorical expression as an information transformation rather than assuming that it specifically compresses normative material.

A useful starting model is:

\[
X \xrightarrow{f} Y
\]

where \(X\) is an argument or other information-bearing representation and \(Y\) is its linguistic realization. Candidate quantities include information preserved \(I(X;Y)\), residual uncertainty \(H(X\mid Y)\), and representation/graph differences.

"Normative compression" can then be treated as a possible specialization: after the transformation is measured neutrally, ask whether normative, descriptive, empirical, inferential, or other components are disproportionately transformed.

## Corpus idea: naturally paired representations

Rather than beginning by reconstructing hidden premises, seek episodes in which the same political actor produces both:

\[
W \leftrightarrow S
\]

- \(W\) = an official written public position;
- \(S\) = that actor's spoken intervention on the same proposal/issue.

This is preferable to assuming speech is a decompression of writing: \(S\) may omit material from \(W\) **and add material absent from \(W\)**. The latter permits investigation of phenomena such as "saying the quiet part out loud" without presupposing that they occur.

For each pair, independently annotate argument structure:

\[
G_W,\;G_S
\]

using an established high-IAA scheme such as Stab & Gurevych. Then examine preserved, omitted, and speech-added argumentative structure:

\[
G_W\cap G_S,\quad G_W-G_S,\quad G_S-G_W.
\]

Only later should missing structure be interpreted as enthymematic, normative, conceptual, etc.

## Methodological sequence

1. Use established argument annotation to measure observable textual structure.
2. Find naturally paired written/spoken representations of the same political act.
3. Measure the transformation without privileging normative content.
4. Classify transformed material by type.
5. Test whether particular kinds of information are systematically affected.
6. Only then investigate enthymemes or normative compression as hypotheses.

A controlled corpus in which a known structured argument is rendered into prose would also be useful, but a naturally occurring written/spoken parallel corpus may provide a stronger initial test because both representations are produced by real actors rather than constructed by researchers.

## Open questions

- Can suitable matched written/spoken political episodes be assembled at scale?
- How reliably can independently annotated argument graphs be aligned across modalities?
- What transformation measures are justified without assuming a theory of "lost" information?
- Are speech-added propositions systematic, and what kinds are they?
- Does any apparent normative compression exceed ordinary cross-channel transformation?

This note is a speculative research direction, not a validated method or established claim.

## Provenance

Developed as a speculative extension of the normative-compression project in conversation on 2026-08-22. The idea should be reconstructed from this note before being promoted into theory, methods, or hypotheses.
