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
