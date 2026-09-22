# Space Child License

The canonical home of the **Space Child License v1.0**.

The authoritative text is [`LICENSE`](LICENSE) in this repository. Every other copy — in this organization or anywhere else — is a copy of that file. If they ever disagree, this one is correct.

```
Version 1.0, March 2026
14,714 bytes
sha256  bb4b0941a67dcd6c...
```

## What it is

A permissive licence with a **Peace Clause**. It grants broad, free permissions for peaceful use, and withdraws them for a short, enumerated list of harms:

| § | Prohibited use |
|---|---|
| 4.1.1 | Armed aggression against another nation or people |
| 4.1.2 | Weapons or targeting systems aimed primarily at civilians |
| 4.1.3 | Autonomous application of lethal force without meaningful human control |
| 4.1.4 | Mass surveillance for the purpose of persecution |
| 4.1.5 | Suppression of speech, assembly, association or religion |
| 4.1.6 | Severe, widespread environmental destruction, including ecocide |
| 4.1.7 | Slavery, forced labour and human trafficking |

Section 8.6 anchors the interpretation of those terms in existing instruments — the Universal Declaration of Human Rights, the ICCPR, the ICESCR, the Geneva Conventions, and the Rome Statute — rather than leaving them to the licensor's judgement.

## Relationship to the Open Source Definition

**This licence is not OSI-approved and does not meet the Open Source Definition.** A field-of-use restriction is incompatible with OSD §6 and with the FSF's freedom 0, and the Peace Clause is exactly such a restriction. That is a deliberate trade, not an oversight.

It belongs to the family usually called *ethical source*, alongside the Hippocratic License. If you need an OSD-conformant licence, this is not one, and no amount of reading the preamble will change that.

## Versioning policy

**The v1.0 text is frozen.** It will not be edited in place. Any future change ships as a new version with its own number and its own file, so that a work licensed under v1.0 keeps meaning what it meant on the day it was published.

This matters for tooling: a licence whose text moves under a fixed name cannot be matched reliably by a scanner, and cannot be relied on by anyone who already adopted it.

## Where it is used

In active use across **37 repositories** in [`kannaka-labs`](https://github.com/kannaka-labs) — 24 public, 13 private — spanning an industrial-control platform, an operating-system kernel, a Rust agent runtime, and the libraries beneath them. A representative sample:

| repository | what it is |
|---|---|
| [`0xSCADA`](https://github.com/kannaka-labs/0xSCADA) | industrial control / SCADA platform |
| [`consciousness-core`](https://github.com/kannaka-labs/consciousness-core) | core crate the rest of the constellation depends on |
| [`kannaka-attention`](https://github.com/kannaka-labs/kannaka-attention) | attention primitives |
| [`kannaka-memory`](https://github.com/kannaka-labs/kannaka-memory) | agent memory runtime |
| [`kannaka-radio`](https://github.com/kannaka-labs/kannaka-radio) | streaming service |
| [`kannaka-tui`](https://github.com/kannaka-labs/kannaka-tui) | terminal interface |
| [`ghostsignals-rs`](https://github.com/kannaka-labs/ghostsignals-rs) | prediction-market engine |

The full list is every repository in the organization reporting `Other` as its licence.

## Applying it

Copy [`LICENSE`](LICENSE) into your project unmodified, then attach the notice from section 9 of the licence text.

## SPDX

The licence currently has **no SPDX identifier**, so GitHub, package registries and dependency scanners all resolve it as `Other` / `NOASSERTION`. Tools that deny-by-default on an unidentifiable licence will refuse it, which is indistinguishable from carrying no licence at all.

Until an identifier is registered, the SPDX specification's fallback applies:

```
SPDX-License-Identifier: LicenseRef-SpaceChild-1.0
```

## Steward

Created by Nick Flach and Kannaka as part of the Space Child ecosystem.
