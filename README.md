# Three assistants, three personas: private 1:1, groups, and multi-soul

**Juan Manuel Fraga Sastrías** · ORCID [0000-0002-9255-278X](https://orcid.org/0000-0002-9255-278X) · [docfraga.com](https://www.docfraga.com)

Technical note · version 1.0 · 2026-10-07 · License [CC BY 4.0](LICENSE)

## Abstract

A side-by-side account of three production conversational agents built by a physician: a personal assistant with more than 60 tools, a 1:1 public-support agent on WhatsApp, and a multi-persona agent for WhatsApp groups. It covers persona design, layered memory, tool use, model routing with fallback, and reliability engineering. Its centerpiece is governance: irreversible actions are gated in code rather than in the prompt, an irreversible-action classifier runs in production, and a tool-use evaluation in which a local model deleted a record in 6 of 10 attempts motivated the code-level gate. A technical appendix documents the architecture, memory constraints, governance design, and reliability cases. Examples are anonymized.

## Files

| File | Language |
|---|---|
| [`clinical-agents-governance-en.pdf`](clinical-agents-governance-en.pdf) | English |
| [`clinical-agents-governance-es.pdf`](clinical-agents-governance-es.pdf) | Español |

Web versions: [English](https://www.docfraga.com/en/whitepapers/asistentes-multi-alma) · [Español](https://www.docfraga.com/whitepapers/asistentes-multi-alma)

## How to cite

Fraga-Sastrías JM. *Three assistants, three personas: private 1:1, groups, and multi-soul*. Technical note, version 1.0. 2026.
A DOI will be listed here once the release is archived in Zenodo.
