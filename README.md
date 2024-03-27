# Bloomreach API Specifications

## Overview

This repository houses the OpenAPI 3.1.0 specification (OAS) files for Bloomreach's Discovery APIs in YAML format. It
serves as the central source for managing and maintaining the API specifications used across various Bloomreach products
and services.

By centralizing the OpenAPI specifications in this repository, we aim to:

- Automate the documentation process, ensuring that the Discovery APIs are accurately represented and up to date on the
  [Readme](https://readme.com/) platform.
- Streamline the generation and maintenance of the Bloomreach Discovery API Postman Collection, incorporating necessary
  default values for a smoother developer onboarding experience.
- Encourage contributions from partners and external developers by keeping the Postman collection open for improvements.

Through GitHub Actions, these specifications are automatically uploaded and synchronized with the documentation
platform, [Readme](https://readme.com/), leveraging the [rdme GitHub action](https://github.com/readmeio/rdme). This
automation extends to updating the
[Bloomreach Discovery API Postman Collection](https://documentation.bloomreach.com/discovery/reference/postman-collections-welcome-kit)
by importing the OAS file into the workspace.

## How to Contribute

We welcome contributions from the community, including partners and external developers. To contribute:

1. **Fork the Repository:** Start by forking this repository to your GitHub account.
2. **Make Your Changes:** Add or update the OAS files according to your enhancements or fixes.
3. **Submit a Pull Request:** Once you've made your changes, submit a pull request to merge your updates into the main
   branch. Please ensure your changes are well-documented and follow the OpenAPI 3.1.0 specification guidelines.

## Automated Workflows

- **Documentation Sync:** Utilizes GitHub Actions to automatically sync the OAS files with the Readme documentation
  platform.
- **Postman Collection Update:** Automatically imports the updated OAS file into the Bloomreach Discovery API Postman
  workspace, ensuring alignment with the latest API specifications.

## Contact

For any queries or assistance regarding the API specifications or the contribution process, please reach out to the
project maintainers.

## License

This project is licensed under the Apache 2.0 license - see the [LICENSE](LICENSE) file for details.
