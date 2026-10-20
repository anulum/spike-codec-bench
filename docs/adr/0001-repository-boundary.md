<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SPIKE-CODEC-BENCH — repository foundation
-->

# Decision: a separate codec-measurement boundary

## Context

Compression measurements need the same source population, representation, codec configuration and quality definitions. A payload size or a zero scalar distortion alone does not establish comparable or lossless behaviour.

## Decision

Spike Codec Bench owns measurement, adapters and independent metrics. It imports codecs from their actual source owner and uses the separately installed evidence provider. It does not vendor codec internals, invent a waveform decoder or parse vendor formats. The intended domain surface retains all six approved families, explicit failure/unavailability and independent consumer evidence.

## Consequences

Current repository tooling can be qualified independently of the future codec runner. That qualification cannot stand for actual codec/dataset/physical results. A source owner interface change requires an explicit adapter and consumer change before support is claimed.
