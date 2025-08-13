# MIGRATED: https://codefloe.com/pat-s/alfred-r

# alfred-r

Alfred workflow for R

## Installation

Download the latest version of `r.alfredworklow` from the [GitHub release page](https://github.com/pat-s/alfred-r/releases/tag/1.1.0).
(Auto-updating is not yet supported)

## Command Description

### `r cran *`

- `r cran <package>`: Opens the CRAN website for a given R package
- `r cran dashboard`: Opens the CRAN incoming dashboard (https://lockedata.github.io/cransays/articles/dashboard.html)

### `r gh *`

- `r gh <package>`: Opens the GitHub website for a given R package (if one exists)
- `r gha <package>`: Opens the GitHub Actions website for a given R package (if one exists)
- `r ghi <package>`: Opens the GitHub Issues pane for a given R package (if one exists)
- `r ghp <package>`: Opens the GitHub Pull Request pane for a given R package (if one exists)

### `r switch *`

- `r switch <R version>`: Switch to a different R version (if installed)
- `r switch install`: Opens the website for downloading [RSwitch.app](https://rud.is/rswitch/)

### `r package *`

- `r package update all`: Update all installed R packages in the background (via `remotes::update_packages(upgrade = "always")`)
- `r package install`: Install a given R package in the background (via `install.packages()`)
- `r package news`: Install a given R package in the background (via `install.packages()`)

### `r install *`

- `r install <version>`: Installs or updates a specific R (minor) version (e.g. 4.0) via the official R installer (not homebrew).
  Currently only R >= 4.0 is supported.
- `r install dev`: Installs or updates R-devel via the official R installer (not homebrew)

### `r rstudio *`

- `r rstudio release`: Install/Update RStudio release via `brew cask reinstall rstudio`
- `r rstudio preview`: Install/Update RStudio preview via `brew cask reinstall rstudio-preview`
- `r rstudio daily`: Install/Update RStudio daily via `brew cask reinstall rstudio-daily`

### `r radian *`

- `r radian install`: Installs the python based [radian R interpreter](https://github.com/randy3k/radian) via pip
- `r radian update`: Updates the python based [radian R interpreter](https://github.com/randy3k/radian) via pip

### Misc

- `r home`: Open \$R_HOME in Finder
