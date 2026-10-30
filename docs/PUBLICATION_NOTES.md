# Publication notes

This repository publishes Zehua Wang's personal Lab1 experiment snapshot. It continues the existing repository README and `.gitignore`; the code and outputs come from the author's original executed notebook, which matches the notebook attached in the earlier project chat byte for byte.

## Changes made while preparing the public snapshot

- Added explanatory Markdown sections covering preprocessing, controlled comparisons, model selection, negative results and limitations.
- Preserved all 82 non-empty code cells in their original order, their source and execution counts. Preserved all output values except replacement of local absolute path strings with `[local-path]`.
- Preserved 14 embedded PNG plots; extracted four PNG files directly from the saved outputs without redrawing them.
- Exported an HTML reading copy without executing the notebook.
- Preserved the initial personal logbook and appended a table distinguishing initial timings from those in the currently saved notebook.
- Added Chinese documentation, top-level version pins and the original course dependency snapshot with an explanation of its provenance.
- Clarified dataset SHA-256 values for LF and CRLF line endings. The two files have identical CSV content.

## Verification scope

Preparation checked notebook schema, code-cell source equality, execution counts, output equality after path redaction, plot count, absence of saved error outputs, relative documentation links and dataset line-ending hashes. Python code cells were checked for syntax using IPython's transformation of notebook syntax. No experiment was retrained and no clean-environment installation was performed.

Raw data, model weights, per-epoch histories, original handouts and other group members' files are excluded. A complete notebook execution generates the local checkpoints and histories needed by the recovery section; running that section alone in a fresh clone requires those files and prior imports.

R9 remains the model selected from validation results. Test-set metrics are reported for the fixed comparison, not used for further tuning. Single-seed findings should not be interpreted as robust multi-seed benchmarks.
