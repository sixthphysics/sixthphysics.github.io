# SixthPhysics Licensing & Required Notices

Required Notice: Copyright (c) 2024-2026 SixthPhysics / Dmitrii Burkov (https://github.com/sixthphysics/sixthphysics)

## Three-Tier Licensing Scope

SixthPhysics separates licensing across its source code, compiled educational content, and open-weight language models so that students, teachers, schools, and researchers can use everything freely for non-commercial education while preventing unauthorized commercial redistribution by paid revision platforms.

| Asset | Scope | License |
| --- | --- | --- |
| **Source Code** | Deterministic TypeScript physics solvers (`lib/visuals/`), non-leaking SVG renderers, bank generation pipeline (`lib/bank-pipeline/`), benchmark & verification harness (`lib/benchmark/`, `lib/live-generator/`), Next.js practice desk & PDF paper studio (`app/`, `components/`, `lib/sixthphysics-web/`), and scripts (`scripts/`, `training/`) | **[PolyForm Noncommercial License 1.0.0](LICENSE.md)** (`PolyForm-Noncommercial-1.0.0`) |
| **Question Bank, Datasets & Rendered SVGs** | Compiled question items, stems, options, distractor explanations, worked solutions, mark schemes, synthetic distillation traces, and rendered SVG physics diagrams (published on `sixthphysics.co.uk` and `d4ydy/sixthphysics-bench-and-bank`) | **[CC BY-NC-SA 4.0](LICENSE-CONTENT.md)** (`CC-BY-NC-SA-4.0`) |
| **Fine-Tuned Model Weights** | `Qwen/Qwen3.5-9B` LoRA adapter (`d4ydy/sixthphysics-qwen3.5-9b-lora`) and merged GGUF quantizations (`d4ydy/sixthphysics-qwen3.5-9b-GGUF`) | **Apache License 2.0** (`Apache-2.0`, matching `Qwen/Qwen3.5-9B`) |

## Commercial Licensing

Commercial use of the SixthPhysics source code (including the deterministic TypeScript physics solvers, SVG figure renderers, or running them internally to pre-generate diagrams/questions for a commercial service) or of the compiled question bank and rendered SVG figures is **not permitted** under the non-commercial licenses above.

For commercial licensing inquiries (such as EdTech platforms, paid study services, or commercial publishing), please contact the SixthPhysics maintainers via [github.com/sixthphysics/sixthphysics](https://github.com/sixthphysics/sixthphysics).

## Effective Date & Prior Releases

This licensing schedule takes effect on **2026-11-21** for this commit and all subsequent releases, builds, and derivative distributions. Historical commits published prior to this change remain governed by the license in effect at the time of their publication.

## Independence & Copyright Notice

SixthPhysics is an independent, unofficial synthetic-data project not affiliated with, endorsed by, or trained on copyrighted past papers or official materials from the IB, AQA, Pearson Edexcel, OCR, Cambridge, WJEC, or NCUK. No copyrighted material from IB, UK A-Level awarding bodies, or NCUK is used in training or distribution.
