# Dify Plugin npm Registry

## Overview

The npm Registry plugin provides a way to search and retrieve information about npm packages. It allows users to find or search for npm packages by name, version, and other criteria.

This plugin offers a simple interface to interact with the npm Registry API in Dify.

## Configuration

No configuration is required to use this plugin.

## Tools

### npm Registry Search

- **Description**: Search for npm packages using a query.
- **Parameters**:
    - `query` (string, required): Search keyword used to find npm packages related to the keyword, such as "react", "vue", "typescript", etc.
- **Returned Results**:
    - Please check `tools/client.py:SearchResponse`

### npm Registry Get

- **Description**: Retrieve detailed information about an npm package.
- **Parameters**:
    - `package_name` (string, required): The name of the package to retrieve details for, such as "react", "lodash", etc.
    - `version` (string): Optional parameter to specify the package version. Defaults to "latest" (latest version).
- **Returned Results**:
    - Please check `tools/client.py:PackageInfo` and `tools/client.py:VersionInfo`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Please follow [npm policy and guidelines](https://github.com/npm/documentation/tree/main/content/policies) when using this plugin. The npm Registry API is a public API provided by npm, Inc. and is subject to their terms of service.

The npm logo is a registered trademark of npm, Inc. All rights to the logo and trademark are owned by npm, Inc.