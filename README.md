<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SPIKE-CODEC-BENCH — repository foundation
-->

# Spike Codec Bench

Spike Codec Bench is being built to measure the payload size, distortion, encode/decode latency and memory cost of spike-compression codecs under explicit source and measurement protocols. This checkout currently contains repository validation tooling and documentation. Full foundation qualification is in progress. There is no installed benchmark package, executable codec runner, public benchmark command or measured benchmark result.

## Boundary

Codec algorithms and decoders remain in SC-NeuroCore. This project owns the planned input registry, adapters, independent metrics, matrix runner and reports. Shared evidence operations belong to the separately installed Evidence Manifest Toolkit. Vendor-format conversion belongs to Spike Format Bridge; the owned input formats are SPIKE-LOG and NPY.

The planned population retains six codec families and two baselines across five dataset families. The current parent registry has five raster codecs. Its separately exported waveform codec consumes analogue samples and has no public decoder in the selected source. Missing support must remain an explicit failed/inconclusive cell, never a fabricated round trip or omitted result.

## Current tooling

The seven repository controls cover metadata, source attribution, workflows, dependency alignment, documentation, inventory and preflight orchestration. The selected native-tool bootstrap verifies named development executables. Their source is present; complete qualification of this checkout remains open. The descriptor declares architecture-only maturity and empty implemented capability and claim inventories.

Use the development environment described in [Contributing](CONTRIBUTING.md). Then the named entry points are `make metadata`, `make source-provenance`, `make workflows`, `make dependencies`, `make docs`, `make inventory` and `make licence`. Full CI/preflight execution is reserved for its supported CI or admitted compute environment. See [Validation](VALIDATION.md) for scope and limits.

## Documentation and support

[Architecture](ARCHITECTURE.md), [support](SUPPORT.md), [security reporting](SECURITY.md) and [citation metadata](CITATION.cff) describe this checkout's boundaries. No hosted service, package release, DOI, public CI status or performance advantage is claimed.

## Licence

The source is licensed under [AGPL-3.0-or-later](LICENSE). A commercial licence is available through the contact in [NOTICE](NOTICE.md).

## Text and data mining reservation
The rightsholder, Miroslav Šotek (ANULUM), expressly reserves the use of the
works in this repository for text and data mining, including the collection of
this content for, and its use in, training, fine-tuning or evaluating machine
learning and artificial intelligence models, in accordance with Article 4(3) of
Directive (EU) 2019/790 and the national provisions transposing it.

No permission for such use has been granted beyond what the licence in
`LICENSE` grants. This reservation does not change that licence: uses the
licence permits remain permitted on its terms, including its attribution and
share-alike conditions.

Reservation made on 2026-10-19. Requests for permission: contact the
rightsholder through the contact listed in this repository.
