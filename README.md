# Three assistants, three personas: private 1:1, groups, and multi-soul

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23213594.svg)](https://doi.org/10.5281/zenodo.23213594)

**Juan Manuel Fraga Sastrías** · ORCID [0000-0002-9255-278X](https://orcid.org/0000-0002-9255-278X) · [docfraga.com](https://www.docfraga.com)

Technical note · version 1.1 · 2026-10-07 · License [CC BY 4.0](LICENSE)

## Abstract

A side-by-side account of three production conversational agents built by a physician: a personal assistant with more than 60 tools, a 1:1 public-support agent on WhatsApp, and a multi-persona agent for WhatsApp groups. It covers persona design, layered memory, tool use, model routing with fallback, and reliability engineering. Its centerpiece is governance: irreversible actions are gated in code rather than in the prompt, an irreversible-action classifier runs in production, and a tool-use evaluation in which a local model deleted a record in 6 of 10 attempts motivated the code-level gate. A technical appendix documents the architecture, memory constraints, governance design, and reliability cases. Examples are anonymized.

## Files

| File | Language |
|---|---|
| [`clinical-agents-governance-en.pdf`](clinical-agents-governance-en.pdf) | English |
| [`clinical-agents-governance-es.pdf`](clinical-agents-governance-es.pdf) | Español |

Web versions: [English](https://www.docfraga.com/en/whitepapers/asistentes-multi-alma) · [Español](https://www.docfraga.com/whitepapers/asistentes-multi-alma)

## How to cite

Fraga-Sastrías JM. *Three assistants, three personas: private 1:1, groups, and multi-soul*. Technical note, version 1.1. 2026.
https://doi.org/10.5281/zenodo.23213594

- All versions (concept DOI, always resolves to the latest): [10.5281/zenodo.23213594](https://doi.org/10.5281/zenodo.23213594)
- Version 1.1: [10.5281/zenodo.23214650](https://doi.org/10.5281/zenodo.23214650)
- Version 1.0: [10.5281/zenodo.23213595](https://doi.org/10.5281/zenodo.23213595)

## Changelog

- **1.1** (2026-10-07): Governance appendix (D1) adds the second arena that confirms the code-level gate: the abliterated version of the same model nearly doubled critical failures (40 % → 77 %) and broke permissions and clinical confidentiality. DOI printed in the header.
- **1.0** (2026-10-07): first release.
