# gloop-client

**gloop-client** is a core component of the **Gloop** freeware software suite, designed to centralize and automate software deployment across Windows 10 and 11 workstations.

## Overview

The `gloop-client` is installed on individual workstations and is responsible for managing software operations, including:

- **Installation**
- **Uninstallation**
- **Updating**

It relies on [Chocolatey](https://chocolatey.org/) under the hood to perform package management tasks, but Chocolatey does **not** need to be pre-installed. If missing, `gloop-client` can automatically install it.

## Key Features

- Seamless integration with the **Gloop server**
- No pre-requirements: handles Chocolatey installation if absent
- Lightweight client with centralized configuration
- Supports Windows 10 and 11

## Requirements

- Windows 10 or Windows 11
- Network access to a running **Gloop server**

## Update

Updating existing clients on workstations is done automatically by updating the **gloop-server** Docker container to a newer version. The installation file provided by this repository is only used for installing new clients.

It is recommended to use the version of **gloop-manager** that corresponds to your **gloop-server** version in order to benefit from the latest features.

## Changelog

### v0.5.0
- **Major update** with new features
- Added expert mode with debug and simulation capabilities
- Added client workstation shutdown scheduling functionality

### v0.4.0
- Bug fixes and stability improvements

### v0.2.0
- Initial public release

## License

This project is part of the **Gloop** freeware suite. 


