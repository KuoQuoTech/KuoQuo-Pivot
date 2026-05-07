# License

## Overview

This project uses a **dual-license model** for software and hardware components.

The goal of this licensing structure is to:

1. Allow free and open community usage
2. Preserve open-source and open-hardware improvements
3. Support commercial adoption
4. Provide proprietary licensing options for organizations that require closed-source usage


## Software Licensing

The software components of this project are licensed under either:

1. **GNU Affero General Public License v3.0 (AGPLv3)** for open/community use
2. A separate **Commercial Proprietary License** for closed-source or proprietary usage

This applies to, but is not limited to:

* firmware
* backend services
* frontend applications
* SDKs and APIs
* automation scripts
* AI integrations
* embedded software
* tooling and utilities


### Software License Option A — Community / Open Use License

We recommend using the **GNU Affero General Public License v3.0 (AGPLv3)**.

#### Why AGPLv3?

AGPLv3 is an established copyleft license that requires users who modify and deploy the software over a network to provide source code of their modified version.

This means:

* Personal use: allowed
* Educational use: allowed
* Research use: allowed
* Commercial use: allowed **if the deployed derivative work is open source under AGPLv3**
* SaaS / hosted use: source code sharing required for modified versions

#### AGPLv3 Requirements

If you distribute or deploy modified versions of the software:

* modified source code must be made available
* derivative works must remain under AGPLv3
* copyright and license notices must be preserved
* network-accessible deployments must provide source access

[GNU Affero General Public License v3.0](./LicenseGNUGPLv3.md)


### Software License Option B — Commercial Proprietary License

Organizations that want to:

* keep modifications closed source
* embed into proprietary products
* distribute without AGPL obligations
* use internally without copyleft disclosure risk
* integrate into commercial SaaS platforms without source disclosure

must obtain a separate **Commercial License Agreement** from KuoQuo.

#### Commercial Software License Includes

* Closed-source usage rights
* Proprietary deployment rights
* OEM / white-label rights (optional)
* Redistribution rights (optional)
* Priority support (optional)
* Custom negotiated terms

[KuoQuo Commercial Software License](./LicenseCommercial.md)


## Hardware Licensing

The hardware components of this project are licensed under either:

1. **CERN Open Hardware Licence Version 2 — Strongly Reciprocal (CERN-OHL-S-2.0)** for open hardware use
2. A separate **KuoQuo Hardware Commercial License** for proprietary or closed-source hardware usage

This applies to, but is not limited to:

* schematics
* PCB layouts
* fabrication files
* Gerber files
* CAD models
* enclosure designs
* mechanical designs
* BOMs
* manufacturing documentation
* assembly files


### Hardware License Option A — Open Hardware License

We recommend using the **CERN Open Hardware Licence Version 2 — Strongly Reciprocal (CERN-OHL-S-2.0)**.

#### Why CERN-OHL-S-2.0?

CERN-OHL-S-2.0 is an established copyleft hardware license specifically designed for open-source hardware projects.

It requires users who modify and distribute hardware designs or manufactured derivatives to provide corresponding design source files under the same license.

This means:

* Personal use: allowed
* Educational use: allowed
* Research use: allowed
* Commercial manufacturing: allowed **if derivative hardware designs remain open under CERN-OHL-S-2.0**
* Distribution of modified hardware: corresponding design files sharing required

#### CERN-OHL-S-2.0 Requirements

If you distribute modified hardware designs or manufactured derivatives:

* modified design files must remain under CERN-OHL-S-2.0
* corresponding design sources must be provided
* attribution and license notices must be preserved
* derivative hardware documentation must remain open

[CERN Open Hardware Licence Version 2](./LicenseCERN-OHL-S-2.0.md)


### Hardware License Option B — Commercial Proprietary Hardware License

Organizations that want to:

* keep hardware modifications closed source
* manufacture proprietary derivative hardware
* distribute hardware without CERN-OHL reciprocal obligations
* integrate designs into closed commercial products
* avoid disclosure of manufacturing or design changes

must obtain a separate **KuoQuo Hardware Commercial License** from KuoQuo.

#### Commercial Hardware License Includes

* Closed-source hardware usage rights
* Proprietary manufacturing rights
* OEM / white-label rights (optional)
* Redistribution rights (optional)
* Custom negotiated terms
* Priority engineering support (optional)

[KuoQuo Hardware Commercial License](./LicenseCommercial.md)


## Practical Summary

| Use Case                                | AGPLv3 Software | CERN-OHL-S-2.0 Hardware | Requires Commercial License |
| --------------------------------------- | ---------------- | ------------------------ | --------------------------- |
| Hobby / Personal Use                    | :material-check: | :material-check:         | :material-close:            |
| Student / Research Use                  | :material-check: | :material-check:         | :material-close:            |
| Open-source startup product             | :material-check: | :material-check:         | :material-close:            |
| Commercial manufacturing with open mods | :material-check: | :material-check:         | :material-close:            |
| SaaS with private backend modifications | :material-close: | N/A                      | :material-check:            |
| Proprietary enterprise integration      | :material-close: | :material-close:         | :material-check:            |
| Closed-source hardware derivative       | N/A              | :material-close:         | :material-check:            |
| Proprietary firmware distribution       | :material-close: | N/A                      | :material-check:            |
| Closed-source consumer hardware product | :material-close: | :material-close:         | :material-check:            |


## Disclaimer

This software, hardware designs, documentation, and related materials are provided **"as is"** without warranty of any kind, either express or implied.

To the maximum extent permitted by applicable law, KuoQuo and its contributors disclaim all warranties, including but not limited to:

* merchantability
* fitness for a particular purpose
* non-infringement
* accuracy or completeness of results
* manufacturability or production suitability
* reliability
* security
* regulatory compliance

In no event shall KuoQuo or its contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages, including but not limited to:

* loss of data
* loss of profits
* hardware failure
* manufacturing defects
* device malfunction
* regulatory non-compliance
* personal injury
* business interruption
* cybersecurity incidents
* certification failure
* product recalls

arising from the use of, inability to use, manufacture of, or distribution of this project and related materials, even if advised of the possibility of such damages.

Users assume **full responsibility** for all risks associated with:

* use
* manufacturing
* testing
* deployment
* certification
* regulatory approval
* integration into products or systems
* safety validation
* production and distribution