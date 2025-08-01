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


## License

This project is part of the **Gloop** freeware suite. 


