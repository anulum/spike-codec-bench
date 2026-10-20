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

This repository is preparing a measurement harness for spike-compression codecs. Its current executable surface is repository validation tooling. It has no installed benchmark package, public benchmark runner or qualified codec/physical result.

The planned workflow binds source data and codec behaviour before measurement, retains every failed/inconclusive matrix cell, and uses independent references for distortion. The separate waveform capability has no public decoder in the selected parent source; it is not a sixth raster round-trip implementation.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
