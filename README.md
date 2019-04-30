# awesome-reproducible-R [![Awesome][awesome-badge]](https://github.com/sindresorhus/awesome)

An awesome list of resources for reproducible research in R, which includes a comparison table of different tools.

## Labels

This awesome list contains sections that qualify a list item based on it's __primary feature__.  However, some items might have multiple features or uncommon features.  In order to account for this, we have provided a system of acronyms that will be used to label each item.  Additionally, all of the primary feature acronyms describe the items as __proprietary__ or __native__ based on how closely they rely on existing R based technologies.  In the next section we list these qualifying acronyms, and give details on what they are meant to convey.

### Primary Features

* __Comprehensive Tools__ (_NCT/PCT_) - A suite of tools that accomplishes multiple tasks simultaneously.
* __Project Management__ (_NPM/PPM_) - Helps plan, organize, manage, and develope R projects.
* __Repository Management__ (_NRM/PRM_) - Creates or updates local or remote package repositories.
* __Package Management__ (_NPM/PPM_) - Automates the process of installing, upgrading, configuring, or removing R packages from the library path (_.libPath_).
* __R Installation__ (_NRI/PRI_) - Installs the R programming language or manage multiple version of the R programming language.
* __Repository__ (_NR/PR_) - Public storage locations for retrieving and installing R packages.

## Contents

- [Comprehensive Tools](#comprehensive-tools)
- [Package Management](#package-management)
- [Project Management](#project-management)
- [Data Management](#data-management)
- [Virtual Environment](#virtual-environment)

### Comprehensive Tools

These packages or frameworks incorporate package, project, and data management into one tool/

- [rrtools](https://github.com/benmarwick/rrtools) - The goal of rrtools is to provide instructions, templates, and functions for making a basic compendium suitable for writing reproducible research with R
- [RSuite](https://rsuite.io) - R Suite is an R package which together with R Suite CLI tool enables you to design deployment workflow that fits you and makes R your primary data science platform.

### Package Management

These tools are designed to manage packages or package repositories.

- [reproducible](https://github.com/PredictiveEcology/reproducible) – A set of tools for R that enhance reproducibility beyond package management.

### Project Management

These tools are designed to manage projects.

- [template](https://github.com/Pakillo/template) – A template for research projects structured as R packages.
- [workflowr](https://github.com/jdblischak/workflowr) -  Organize your project into a research website.
- [ProjectTemplate](https://github.com/KentonWhite/ProjectTemplate) - Automatically build a directory for a new R project with a standardized subdirectory structure.

### Data Management

These tools are designed to manage data.

- [DataPackageR](https://github.com/ropensci/DataPackageR) – An R package to enable reproducible data processing, packaging and sharing.
- [archivist](https://github.com/pbiecek/archivist) - An R package that stores copies of all objects along with their metadata

## Contribute

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the Datasnakes have waived all copyright
and related or neighboring rights to this work. See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
