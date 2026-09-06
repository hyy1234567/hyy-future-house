# Example — Figure Decision Under URS

## User request

> Make a bar chart for three independent treatment groups, n = 8 per group, continuous outcome.

## URS interpretation

The user needs a scientifically defensible visualization of a small-n continuous outcome. “Bar chart” is treated as an initial candidate, not a fixed method.

## Diagnosis

- Outcome: continuous
- Groups: 3 independent groups
- n: 8/group
- Primary goal: compare distributions and group-level differences
- Key risk: a bar chart may hide individual observations, skew, and outliers

## Candidate comparison

### Candidate A — Bar + SEM

Pros: familiar and compact.

Cons: hides distribution and individual observations; summary-only display is weak for small n.

### Candidate B — Box plot + raw points

Pros: exposes observations and distributional structure.

Cons: box summaries can be unstable with very small samples.

### Candidate C — Raw dot plot + median/IQR or model-compatible estimate/CI

Pros: maximal transparency; preserves individual observations; easy to align with the actual inferential analysis.

## Primary recommendation

`PRIMARY RECOMMENDATION: Raw dot plot with an appropriate summary and uncertainty representation matched to the statistical analysis.`

## Rejected option

`REJECTED: Bar + SEM as the default publication figure because it unnecessarily hides the underlying small-n data.`

## QC

Before finalization, verify axis units, group labels, statistical annotation, uncertainty definition, color accessibility, final-size readability, and agreement between the figure and the statistical model.
