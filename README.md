# Big Data Bowl

Historical research by Eric Matthew Rupinski. Reconstruction status: **partial; original empirical findings have not been re-estimated**. Original research history is preserved.

## Research question and value

What does player spacing at kick reception reveal about return outcomes? Recovering this work demonstrates spatial feature engineering and disciplined model interpretation.

## Data and methodology

Original files remain the source of historical methodology. `data/requirements.json` inventories detected input filenames and packages; it is an incomplete static manifest, not a locked environment. Raw files are absent from this repository. Reacquire them through their original authorized sources; competition and third-party licenses must be checked before reuse.

## Audit and implemented changes

The .r file is actually notebook JSON. A truncated fitControl call prevents extracted code from parsing. Feature transformations are fitted before CV and independently fitted on prediction data. Actual return-direction fields need availability review.

Recovered a valid R notebook and parseable R export; preserved original bytes and hash.

## Findings and validation

No new empirical finding or revised performance score is asserted. Unit checks use small constructed inputs to verify the repaired mathematics and data contracts. Parsing verifies syntax only; it does not execute an analysis. Available original illustrations are historical outputs, not independently regenerated evidence.

## Reproduce the supported checks

R 4.5.2 was used for the base-R checks.

```sh
Rscript --vanilla -e 'invisible(parse("R/analysis.R"))'
# Notebook format: python -m pip install nbformat; python -c <validation>
```

The original dependency set is not fully available or version locked. Successful helper tests do not establish successful execution of the original model.

## Practical applications and limits

No raw data included. End-to-end results and generalization claims remain unverified; preprocessing and outcome-derived features require full rebuild.

## Next work

Recover input data with provenance and variable timing; declare the observational unit; isolate complete games/matches chronologically; fit transformations on training folds; compare against a simple baseline; regenerate figures and revise findings from held-out evidence. Retain old conclusions as historical until then.
