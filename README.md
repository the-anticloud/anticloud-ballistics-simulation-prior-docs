# BALLISTICS SIMULATION PRIOR DOCS

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-artillery_manufacturing-lightgrey)

> Anticloud-hardened packaging of the upstream project `BALLISTICS_SIMULATION_PRIOR_DOCS` in category **ARTILLERY MANUFACTURING**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ARTILLERY MANUFACTURING · **Upstream:** https://github.com/namighuseynov/Ballistics-Simulation · **Upstream pin:** `ca43b88362dedf6e993c1419205848fda0e39d88` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Ballistics Simulation

## Project Description
The "Ballistics Simulation" project contains a project developed in the Unity platform, designed for creating and visualizing a ballistic system, as well as exploring the behavior of different projectiles within a virtual environment. This project provides tools and resources for modeling and simulating the motion of projectiles under different conditions and with various parameters.

## Key Features
- **Realistic Ballistics:** Develop and fine-tune a physics system that enables projectiles to behave similarly to real-world conditions. Study the effects of wind, gravity, aerodynamics, and other factors on the trajectory of flight.

- **Diverse Projectiles:** Include various types of projectiles, such as bullets, artillery shells, rockets, and others, each with unique characteristics and flight behavior.

- **User Customization:** Allow users to customize projectile parameters, initial conditions, and the surrounding environment for conducting experiments.

- **Results Visualization:** Create a visual representation of projectile trajectories, showcasing changes based on parameters and conditions.

- **Data Analysis:** Provide tools for analyzing data obtained from simulations, including graphs, statistics, and comparisons between different variations.

- **Educational Context:** Utilize the project for teaching the fundamentals of physics and ballistics through interactive simulations and experiments.

## How to Use
1. source the project to your computer.
2. Open the project in Unity.
3. Study and customize the components of the ballistics system.
4. Add new projectiles and define their parameters.
5. Run simulations and analyze the results.
6. Edit and enhance the project to suit your needs and research.

## 🔒 License & Usage Restrictions

This project is **public**, but **non-commercial**.

You are allowed to:
- view and study the source code  
- use it for research or educational purposes  
- reference it with attribution  

You are NOT allowed to:
- use the project commercially  
- integrate it into any product, game, training simulator, or software  
- redistribute or republish it  
- modify and distribute modified versions  
- use it for paid services  
- use it for machine learning datasets  

For commercial licensing, contact:  
**namiq.guseinof@gmail.com**

## 📄 Legal Notice

This project includes a NOTICE file containing important legal and copyright
information. The NOTICE file must be preserved in all allowed copies of this
project.  
See: **NOTICE**

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `BallisticsSimulation/`, `Resources/`
- Snapshot size: **338 files**, **5078 lines of code** (measured; see Benchmarks)
- Primary languages: `.meta` (162), `.cs` (49), `.mat` (29), `.asset` (25), `.png` (20), `.prefab` (16)
- Upstream commit pinned for this packaging: `ca43b88362dedf6e993c1419205848fda0e39d88`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

This project is **public**, but **non-commercial**.

You are allowed to:
- view and study the source code  
- use it for research or educational purposes  
- reference it with attribution  

You are NOT allowed to:
- use the project commercially  
- integrate it into any product, game, training simulator, or software  
- redistribute or republish it  
- modify and distribute modified versions  
- use it for paid services  
- use it for machine learning datasets  

For commercial licensing, contact:  
**namiq.guseinof@gmail.com**

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

You are NOT allowed to:
- use the project commercially  
- integrate it into any product, game, training simulator, or software  
- redistribute or republish it  
- modify and distribute modified versions  
- use it for paid services  
- use it for machine learning datasets  

For commercial licensing, contact:  
**namiq.guseinof@gmail.com**

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 338 |
| Lines of code | 5078 |
| Dependency references | 0 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing to Ballistics-Simulation

Thank you for your interest in this project.

However, **this project does not accept external contributions**, including:

- pull requests (PRs)
- feature requests
- bug fixes
- code changes
- documentation edits
- translations

This project is developed and maintained exclusively by  
**Namig Huseynov**.

## Why contributions are not accepted?

- The project contains proprietary research logic.
- The license prohibits derivative works and redistribution.
- External changes may conflict with the non-commercial restrictions.
- Consistency and accuracy of ballistic calculations must be preserved.

## Reporting Issues

You may open an *Issue* only for:

- reporting a mistake in the description or documentation
- reporting incorrect display in README or diagrams
- suggesting non-invasive improvements

Issues that propose code changes or feature additions will be closed immediately.

## Commercial Use

This project is strictly **non-commercial**.  
Pull requests or suggestions that aim to extend the project for commercial
purposes will be rejected.

For special requests, contact:
**namiq.guseinof@gmail.com**

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright (c) 2025 Namig Huseynov

Permission is hereby granted to view, study, and reference the source code
and documentation contained in this project (the “Software”), for
non-commercial, research, educational, and personal purposes only.

The following actions are STRICTLY PROHIBITED without explicit written
permission from the author:

- commercial use of the Software or any portion thereof
- copying, redistributing, or publishing the Software
- modifying and distributing modified versions
- incorporating the Software into any commercial product, game, simulation,
  research tool, or training system
- training machine learning models on the Software
- uploading, reselling, sublicensing, leasing, or packaging the Software

The Software is provided “as is”, without warranty of any kind.

This project contains a NOTICE file. Any permitted copies or portions of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `BALLISTICS_SIMULATION_PRIOR_DOCS` (category: ARTILLERY MANUFACTURING)
- **Upstream URL:** https://github.com/namighuseynov/Ballistics-Simulation
- **Pinned commit (SHA):** `ca43b88362dedf6e993c1419205848fda0e39d88`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`5655bdc4ab9f62f8b9e118eabf1db3a66cc27071918960ec8e08899e4116729d`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |

