# Statistical Model — Draft

The final model will be selected after pilot work and metric validation.

## Candidate structure

For passage/argument `i`, a compression outcome could be modeled as a function of:

`compression_i ~ classification_type + normative_profile + boundary_policing + genre + length + discipline + year + advocacy + controls`

Potential hierarchical structure:

`passage nested in document nested in source/venue`

Random effects may be required for author, venue, discipline, or document depending on the corpus.

## Key interaction

The strongest mechanistic test is likely an interaction between:

`boundary challenge × threat to downstream normative inference`

with boundary-policing response as the outcome.

## Pre-analysis requirements

- define outcome before confirmatory testing;
- specify transformations and missing-data treatment;
- specify multiple-comparison strategy;
- distinguish exploratory from confirmatory estimates;
- report effect sizes and uncertainty, not only significance;
- retain negative results.

No statistical model is final at repository initialization.
