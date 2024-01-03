# Try Out Development Containers: R

This repository contains some example Dev Container definitions for R and can be run on GitHub Codespaces (click on the badges!).

## Dev Container Definitions

### [Combination of r-rig and rstudio-server](.devcontainer/example-rig-rstudio)

[![Open Combination of r-rig and rstudio-server in GitHub Codespaces](https://img.shields.io/badge/Open-example--rig--rstudio-blue?logo=github)](https://codespaces.new/rocker-org/devcontainer-try-r?devcontainer_path=.devcontainer%2Fexample-rig-rstudio%2Fdevcontainer.json)

It is configured to install [`ghcr.io/rocker-org/devcontainer-features/r-rig`](https://github.com/rocker-org/devcontainer-features/tree/main/src/r-rig)
and [`ghcr.io/rocker-org/devcontainer-features/rstudio-server`](https://github.com/rocker-org/devcontainer-features/tree/main/src/rstudio-server)
on top of [`mcr.microsoft.com/devcontainers/base:ubuntu`](https://github.com/devcontainers/images/tree/main/src/base-ubuntu).
Initially, the latest release version of R is installed,
but [`rig`](https://github.com/r-lib/rig) makes it easy to install a different version of R and switch between these.

RStudio Server is configured to run immediately after container startup.

### [R (rocker/r-ver base) template](.devcontainer/template-r-ver)

[![Open R (rocker/r-ver base) in GitHub Codespaces](https://img.shields.io/badge/Open-template--r--ver-blue?logo=github)](https://codespaces.new/rocker-org/devcontainer-try-r?devcontainer_path=.devcontainer%2Ftemplate-r-ver%2Fdevcontainer.json)

A simple template that runs a Docker image [`ghcr.io/rocker-org/devcontainer/r-ver`](https://rocker-project.org/images/devcontainer/images.html)
configured to be used as a Dev Container.
Many R packages are already installed.

It is just a download of the Dev Container Template
[`ghcr.io/rocker-org/devcontainer-templates/r-ver`](https://github.com/rocker-org/devcontainer-templates/tree/main/src/r-ver).

### [R (r2u and bspm configured) template](.devcontainer/template-r2u)

[![Open R (r2u and bspm configured) in GitHub Codespaces](https://img.shields.io/badge/Open-template--r2u-blue?logo=github)](https://codespaces.new/rocker-org/devcontainer-try-r?devcontainer_path=.devcontainer%2Ftemplate-r2u%2Fdevcontainer.json)

It is configured to install [`ghcr.io/rocker-org/devcontainer-features/r-apt`](https://github.com/rocker-org/devcontainer-features/tree/main/src/r-apt)
on top of [`mcr.microsoft.com/devcontainers/base:ubuntu`](https://github.com/devcontainers/images/tree/main/src/base-ubuntu).
Installing many R packages quickly thanks to [`r2u`](https://eddelbuettel.github.io/r2u/).

It is just a download of the Dev Container Template
[`ghcr.io/rocker-org/devcontainer-templates/r2u`](https://github.com/rocker-org/devcontainer-templates/tree/main/src/r2u).
