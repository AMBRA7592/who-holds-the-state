# Who Holds the State?

**A Framework for Testing Claims After Support Ends**

This repository contains the launch release of *Who Holds the State?*, a working paper by Amadeus Brandes, and its companion launch registry, *State Claim Registry v0.1*.

## Core idea

State claims are often measured while the support relation that produces them is still present, then priced or governed as if the state had transferred. The custody framework tests such claims by naming the claim class, inventorying the support relation, specifying withdrawal at the claim's implied horizon, measuring what survives, assigning the holder of continuity, and comparing that assignment to what was promised.

A claim matches custody when the promised continuity is supported by the holder, state-path, and evidence standing. Otherwise it is mismatched, opaque, or unprobed. The framework does not punish dependence; it exposes dependence sold as transfer, durability, independence, or ownership.

## Contents

paper/
  who-holds-the-state-v1.0.md
  who-holds-the-state-v1.0.pdf
  who-holds-the-state-v1.0-styled-source.md
  whs_template.tex
  who-holds-the-state-v1.0.release.sha256

registry/
  state-claim-registry-v0.1.md
  state-claim-registry-v0.1.csv

CHANGELOG.md
LICENSE
README.md

## Paper

**Who Holds the State? A Framework for Testing Claims After Support Ends**
Version: v1.0
Date: 2026-05-26
Author: Amadeus Brandes, Independent Researcher, Germany

Cite as:

> Brandes, Amadeus. 2026. *Who Holds the State? A Framework for Testing Claims After Support Ends*. Version 1.0. 2026-05-26. https://doi.org/10.5281/zenodo.20404429

## Registry

**State Claim Registry v0.1**
Schema: SCR-v0.1
Date: 2026-05-26

The registry applies the State Claim Record to twelve launch cases across clinical, financial, household, software, media, biological, and cosmetic claims.

Rows are citable as SCR-v0.1-001 through SCR-v0.1-012.

Cite as:

> Brandes, Amadeus. 2026. *State Claim Registry*. Version 0.1, schema SCR-v0.1. 2026-05-26.

## Registry schema

The machine-readable CSV uses these columns: row_id, schema_version, row_status, row_version, date, q, kappa, support_withdrawal_horizon, holder, state_path, evidence_standing, verdict, remedy, challenge_condition, notes.

## Verification

The release includes a SHA256 manifest for the paper package:

    cd paper
    shasum -a 256 -c who-holds-the-state-v1.0.release.sha256

## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See LICENSE.

## Links

- GitHub Pages: https://ambra7592.github.io/who-holds-the-state/
- Zenodo (v1.0): https://doi.org/10.5281/zenodo.20404429
- Zenodo (all versions): https://doi.org/10.5281/zenodo.20404428
- SSRN: TBD (pending submission)
- SocArXiv / OSF: TBD (pending submission)
