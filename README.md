# HippoEDIT Dictionaries

Canonical source repository for HippoEDIT spell-check dictionaries.

The distributable source tree lives under `resources/`. Dictionary identity and locale metadata remain in each dictionary's `package-info.xml`; there is no separate duplicate locale registry.

The HippoEDIT website repository owns publication orchestration and runtime delivery, but it is not the source of truth for dictionary payloads. Published artifacts are built from an exact commit of this repository and record that source SHA in their provenance metadata.
