# extra-packages-openmamba

> **Note:** This project is currently **WORK IN PROGRESS** and is **NOT officially affiliated** with openMamba GNU/Linux.

## Overview

Extra Packages for openMamba is an unofficial community-driven repository providing additional software packages for openMamba GNU/Linux users. We curate and maintain both open-source (OSS) and non-open-source software options.

## Purpose & Scope

This project aims to:
- Provide additional packages not available in official openMamba repositories
- Maintain both free/open-source and proprietary software options
- Support users who need specialized tools and applications
- Foster community contributions and package maintenance
- Port packages from upstream sources to openMamba

## Available Packages

### Open Source Software (OSS)
Our collection includes various open-source applications and utilities covering:
- Development tools and libraries
- Productivity applications
- Media and graphics software
- System utilities
- And more...

### Non-Open Source Software
We also maintain select proprietary/non-OSS packages that users may require, including:
- Commercial applications
- Proprietary utilities
- Licensed software
- Industry-specific tools

## Installation Instructions

### For openMamba Users

1. **Add the repository**
   ```bash
   sudo dnf5 config-manager --add-repo=https://runnertechhype.github.io/extra-packages-openmamba/
   ```

2. **Update your package manager**
   ```bash
   sudo dnf5 update
   ```

3. **Install packages**
   ```bash
   # Example: Install a package from the repository
   sudo dnf5 install <package-name>
   ```

## Usage Guidelines

### Installing Packages
- Detailed installation guides for specific packages (coming soon)

### Package Management
- Repository management best practices (coming soon)

### Troubleshooting
- Common issues and solutions (coming soon)

## Important Notice

⚠️ **This project is unofficial and NOT affiliated with openMamba GNU/Linux**

- Use packages at your own discretion
- Always verify package integrity and licensing
- Check compatibility with your openMamba version
- Community support only (not official openMamba support)

## Credits & Attribution

This project sources and ports packages from the following upstream projects with respect and gratitude:

- **[Fedora Project](https://fedoraproject.org/)** (EPEL - Extra Packages for Enterprise Linux)
- **[Packman Team](https://packman.team/)** (Multimedia and additional packages for openSUSE)
- **[Arch Linux](https://archlinux.org/)** (AUR - Arch User Repository)

We thank these communities for their excellent work and package maintenance. This project adapts and ports their packages to be compatible with openMamba GNU/Linux.

## Status

🚧 **WORK IN PROGRESS** - This repository and documentation are actively being developed. More packages and documentation will be added soon.

## Contributing

Contributions are welcome! Please check back for contribution guidelines (coming soon).

## License

See LICENSE file for details on individual package licensing. Each package retains its original license from its upstream source.

---

For more information about openMamba GNU/Linux, visit: [openMamba Official Website](https://www.openmamba.org/)
