# Project organization

We use the `dev` branch for development and the `main` branch for stable
releases.  Contributions must be made with pull request to `base:dev`. 

## Data

All data files are stored in the `data` directory

### `outcomes.csv`
Comma-separated file containing the outcome variable `y`, subject identifier
`id`, and observation number `num`

### `covariates.csv`
Comma-separated file containing covariate information: `a` binary treatment, `x`
continuous baseline covariates, subject identifier `id`, and observation number `num`

## Code 

All source code are stored in the `code` directory and should comply to the code
styles defined in `.editorconfig` (and `.lintr` for R-specific code)

# Tasks

The following data analysis must be saved as a script in the `code` directory.

1. Combine the covariate and outcome data sets
2. Create basic summary statistics or visualizations of the data
3. Analyze the association between the response and treatment. Interpret
   results. Are there any signs of confounding or effect modification?
4. Commit the changes and create a pull request to the
   github repository.
---
5. Optional task. Simulate from the model used in step 3 (same parameter
   estimates and sample size). Summarize the small-sample properties of the
   applied estimator.
