## v1.4.0 (2025-04-27)

### Feat

- enable weekly security scan
- add trivy to build pipeline

### Fix

- **deps**: updating python dependencies
- **deps**: updating python to 3.13.3
- correcting the license configuration
- attempting to fix dependabot
- **deps**: bump python from `f3614d9` to `8f3aba4`
- **deps**: bump commitizen-tools/commitizen-action from 0.23.1 to 0.24.0
- **deps**: bump python from 3.13.1-slim-bookworm to 3.13.2-slim-bookworm
- **deps**: bump python from `1127090` to `026dd41`
- remove unused files
- add license file to docker image
- **deps**: bump python from `f41a75c` to `1127090`
- **deps**: updating poetry version and cleaning up docker
- updating build scripts, readme, python dependencies
- updating python version to 3.13 and various actions updates
- remove merge workflow entirely
- do not put anything into this workflow file
- fixing merge workflow
- fixing name of workflow
- remove option causing warnings
- get version number from a clean build
- put application version into the dockerfile
- enable error handling in entrypoint script
- **deps**: updating commitizen pre-commit hook
- **deps**: bumping python docker container version to 3.12.8
- allow poetry to install the package into the venv
- **deps**: bump softprops/action-gh-release from 2.0.9 to 2.1.0
- **deps**: bump commitizen-tools/commitizen-action from 0.21.0 to 0.22.0
- **deps-dev**: bump pytest from 8.3.3 to 8.3.4
- **deps**: bump flask from 3.0.3 to 3.1.0
- update python and docker dependencies
- removing deprecated safety tool
- **deps**: updating commitizen pre-commit hook
- **deps**: bump softprops/action-gh-release from 2.0.8 to 2.0.9
- **deps-dev**: bump pytest-cov from 5.0.0 to 6.0.0
- **deps**: updating base docker image
- **deps**: bump werkzeug from 3.0.4 to 3.0.6 in the pip group
- updating dockerfile to use new base python image
- updating pre-commit configuration
- **deps**: bump python from `15bad98` to `ad48727`
- **deps-dev**: bump pytest from 8.3.2 to 8.3.3
- **deps**: update base image
- remove pre-commit from deps, update dependencies

## v1.3.0 (2024-09-02)

### Feat

- correctly set version on build

## v1.2.0 (2024-09-02)

### Feat

- testing package releases
- disable mypy
- change formatting to use black instead of yapf

### Fix

- **deps**: bump python from `105e9d8` to `59c7332`
- updating gunicorn for vuln
- fixing license reference
- shellcheck changes

## v1.1.1 (2024-08-09)

### Fix

- run mypy tests from Makefile
- minor fixes to container build

## v1.1.0 (2024-08-08)

### Feat

- convert from quart to flask (#22)
- adding mypy and cov requirements (#21)
- enable the safety pipeline (#20)

### Fix

- **deps**: bump python from `f11725a` to `740d94a` (#18)
- **deps-dev**: bump pre-commit from 3.7.1 to 3.8.0 (#19)

## v1.0.0 (2024-07-29)

## v0.4.0a0 (2024-07-29)

### Feat

- test tag number in builds (#16)

## v0.3.0 (2024-07-29)

### Feat

- adding more examples for building containers (#15)

## v0.2.0 (2024-07-28)

### Feat

- configure release triggering (#13)

## v0.1.0 (2024-07-28)

### Feat

- the initial application
