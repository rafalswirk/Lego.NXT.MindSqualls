# MindSqualls (.NET 4.8+ fork)

This repository is a maintained fork of the original **MindSqualls** library for controlling LEGO MINDSTORMS NXT robots over Bluetooth and USB.

## Project origin

- **Original project**: MindSqualls
- **Original author**: **Niels K. Handest**
- **Original sources**:
  - http://www.mindsqualls.net/
  - https://github.com/NybbleLynx/MindSqualls (archived/uploaded with permission)

This fork keeps the original library available and updated for modern .NET development.

## Current fork

- **Fork maintainer**: Rafał Świrk
- **Fork repository**: https://github.com/rafalswirk/Lego.NXT.MindSqualls
- **Primary goal**: modernize and publish the library via NuGet while preserving original functionality.

## Roadmap

1. ✅ Update projects to **.NET Framework 4.8**
2. 🔜 Prepare package and publish on **NuGet**
3. 🔜 Continue modernization toward **.NET 10**

## NuGet publication notes

This code is under **LGPL-3.0-or-later**, which allows NuGet publication.

To stay compliant and publication-ready, this fork includes:

- package metadata with attribution to original author and fork maintainer,
- SPDX license metadata (`LGPL-3.0-or-later`),
- repository/project URLs,
- package README and LICENSE inclusion.

Potential obstacle to verify before first release:

- `NKH.MindSqualls` references `WinUsbWrapper` as a project dependency. Ensure packaging includes all required runtime assemblies and that package contents are validated from a clean consumer project.

## License

This project is licensed under the **GNU Lesser General Public License v3.0 or later (LGPL-3.0-or-later)**.
See [LICENSE](LICENSE).

Original work copyright © Niels K. Handest.
Fork maintenance changes copyright © Rafał Świrk.

## Trademarks

LEGO and MINDSTORMS are registered trademarks of the LEGO Group, which does not sponsor, authorize, or endorse this project.
