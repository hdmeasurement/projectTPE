# CRAN Submission Comments — projectTPE 0.1.0

## Test Environments

* Windows 11, R 4.4.1 (local)
* Ubuntu 22.04, R 4.4.1 (GitHub Actions)
* macOS Ventura, R 4.4.1 (GitHub Actions)

## R CMD check results

0 errors | 0 warnings | 0 notes

## Downstream dependencies

None — this is a new package.

## Notes to CRAN

* The package includes a Shiny application launched via `run_app()`.
  The app requires internet access only for the hosted version;
  local deployment works fully offline.
* Built-in simulated dataset replicates the structure of Indonesian
  Rapor Pendidikan data (composite dimension scores, 4 waves).
  No actual personal data is included.
* All functions include complete roxygen2 documentation with `@examples`.
