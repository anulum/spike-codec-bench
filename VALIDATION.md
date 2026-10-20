<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SPIKE-CODEC-BENCH — repository foundation
-->

# Validation

This checkout's repository foundation is under qualification. No test or coverage result from another repository qualifies it. No model, codec, installed benchmark package, scientific method, physical clock/RSS protocol or benchmark is qualified here.

## Maintained scope

Python tools and their dedicated tests are enrolled in Ruff, formatting, strict mypy, NumPy-style documentation, statement and branch coverage. The target is full meaningful coverage of every maintained source file. Metadata, source attribution, workflow, dependency, documentation, inventory and preflight controls each have public entry points and success/refusal tests. The source-selected native bootstrap has its own real archive/file tests.

## Local and CI entry points

Use the exact selected interpreter and dependency locks from [Contributing](CONTRIBUTING.md). `make metadata`, `make source-provenance`, `make workflows`, `make dependencies`, `make docs`, `make inventory` and `make licence` check the corresponding named scope. Focused tests exercise the owning module. The full `make ci` and `make preflight` include all infrastructure tests and online checks and belong in CI or an explicitly admitted pre-push environment. A named partial preflight leaves omitted checks as not run and cannot clear whole acceptance.

## Evidence limits

Documentation rendering is separate from API completeness. Byte identities are separate from installed-package behaviour, build reproducibility and vulnerability findings. Static workflow acceptance is separate from actual hosted execution. No remote, hosted result, DOI, release, scientific claim or comparative performance is inferred from this source tree.
