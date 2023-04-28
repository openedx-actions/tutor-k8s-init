# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Version 1.0.9 (2023-04-28)

- version bumps
- add test status
- add sponsorship solicitation

## Version 1.0.8 (2023-03-28)

- add kubectl-version
- add tutor-mfe-version

## Version 1.0.7 (2023-03-24)

- bump kubectl to 1.25/stable
- revert to installing tutor solo to avoid tutor-mfe image pull issues when not installing latest
- refactor yq installation
- add a whoami step

## Version 1.0.6 (2023-03-24)

THIS VERSION WAS YANKED.

- bump kubectl to 1.25/stable
- switch to installing yq with snap
- switch to installing tutor[full] instead of solo

## Version 1.0.5 (2023-02-04)

- bump kubectl to version 1.24/stable
- install and enable tutor-mfe plugin

## Version 1.0.4 (2022-09-03)

- mask TUTOR_OPENEDX_MONGODB_PASSWORD

## Version 1.0.3 (2022-07-13)

- Add an input `tutor-version` and default to "14.0.2"

## Version 1.0.2 (2022-06-23)

- ADD masks for sensitive data generated and echoed to the console by tutor during config, build and deploy operations

## Version 1.0.0 (2022-06-16)

- General production release.

## Version 0.0.1 (2022-06-01)

**Experimental. Do not use in production.**

- Initial Git import
