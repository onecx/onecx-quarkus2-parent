## OneCx Quarkus2 parent

Maven parent for all Quarkus2 OneCx application.

[![License](https://img.shields.io/github/license/onecx/onecx-quarkus2-parent?style=for-the-badge&logo=apache)](https://www.apache.org/licenses/LICENSE-2.0)
[![Supported JVM Versions](https://img.shields.io/badge/JVM-17-brightgreen.svg?style=for-the-badge&logo=Java)](https://openjdk.org/projects/jdk/17/)
[![GitHub Actions Status](https://img.shields.io/github/actions/workflow/status/onecx/onecx-quarkus2-parent/build.yml?logo=GitHub&style=for-the-badge)](https://github.com/onecx/onecx-quarkus2-parent/actions/workflows/build.yml)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/release/onecx/onecx-quarkus2-parent?display_name=tag&sort=semver&logo=github&style=for-the-badge)](https://github.com/onecx/onecx-quarkus2-parent/releases/latest)

### Definition

This parent contains:
* version of the `Quarkus 2.x.x`
* default dependencies:
  * Lombook 
  * MapStruct
  * [tkit-quarkus](https://github.com/1000kit/tkit-quarkus)
* plugin to build the application
* plugins for testing the application
* plugin to sort imports
* plugin to validate format

### Profiles

#### openapi
mvn clean install -Popenapi
OpenApi generate an openapi.yaml in the target directory

### How to ...

Check the [latest release](https://github.com/onecx/onecx-quarkus2-parent/releases/latest) page for details.
