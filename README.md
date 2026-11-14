# AKRM-RIR

**Transcendental Critical Refusal Method – Recursive Instability Regulation**

Inference-time control layer for hallucination-aware language model generation.

- Epistemic reliability score: μ ∈ [0, 1]
- Instability functional: \( K(\mu) = 4\mu(1-\mu) \) (peaks at μ = 0.5)
- Refusal Gate + Recursive Smoothing + Proper Exit Trigger

**Motto:** Refusal eternal, şafak graded.  
**Author:** Av. Enes Akın (@NsaTcrm)  
**Status:** v1.0 – Zenodo preprint + prototype based

## Core Idea
Hallucination is treated as measurable instability during decoding, not only confidence failure. When K(μ) exceeds threshold → refuse, smooth, or Proper Exit.

## Structure
- `src/` – core AKRM-RIR implementation
- `examples/` – inference wrappers
- `docs/` – architecture notes
- `benchmarks/` – evaluation data

## Related
- Zenodo: AKRM-RIR reproducibility package
- Philosophy: Transcendental Critical Refusal Method (AKRM)

## License
MIT (code)