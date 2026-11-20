# Cartograph Labs

We test what language models actually compute, and when an evaluation can tell.

Cartograph Labs is a two-person research group at the University at Buffalo:
[Vaishak G Kumar](https://github.com/Gustav-Proxi) and [Sanika Vilas Najan](https://github.com/Sanika0212).
Every paper is joint work with equal contribution.

## Projects

| Project | Question | Code |
| --- | --- | --- |
| **When Can a Rewiring Control Test LLM Weight Readers?** | When LLMs predict a network's outputs from its raw weights, do they compute, or recognise weight-space fingerprints? We introduce C2, a readout-permutation control, and the conditions under which it can decide. | `c2-weight-readers` |
| **Planted Answers, Plausible Reasoning** | Do diffusion language models (LLaDA, Dream) write reasoning that produces their answer, or reasoning that fits an answer they have already fixed? | `planted-answers` |
| **dlm-lens** | TransformerLens-style hooks for masked diffusion LMs: step-aware hook points, a commit-logging sampler, activation patching, logit and commit lens. | `dlm-lens` (PyPI release soon) |

## How we work

- **Committed before data.** Each experiment's protocol is written before its data; confirmatory studies are registered externally.
- **Every number regenerable.** Each repository recomputes the paper's statistics from its raw records.
- **Controls first.** Before claiming what a model does, we ask whether the test could have shown otherwise.
