# Windstorm-Labs

**Experimental code and reproducibility infrastructure for the Windstorm Institute paper series.**

This organization contains runnable experiments, raw data, and analysis code supporting research on information-theoretic constraints in serial decoding systems.

---

## Series Index

| # | Repository | Status | Compute | Key Result |
|---|------------|--------|---------|------------|
| 1 | [fons-constraint](https://github.com/Windstorm-Labs/fons-constraint) | ✅ Published | — | 64-codon derivation |
| 2 | [receiver-limited-floor](https://github.com/Windstorm-Labs/receiver-limited-floor) | ✅ Complete | ~8 hrs RTX 5090 | 1,749 models, BPT ⊥ vocab |
| 3 | [throughput-basin](https://github.com/Windstorm-Labs/throughput-basin) | ✅ Published | Meta-analysis | 31 systems |
| 4 | [dissipative-decoder](https://github.com/Windstorm-Labs/dissipative-decoder) | ✅ Published | ~6 hrs RTX 5090 | 27-model energy benchmark |
| 5 | [serial-decoding-basin](https://github.com/Windstorm-Labs/serial-decoding-basin) | ✅ Published | — | τ = 4.16 ± 0.19 bits |
| 6 | [inherited-constraint](https://github.com/Windstorm-Labs/inherited-constraint) | ✅ Published | ~4 hrs RTX 5090 | 7-corpus shuffling |
| 7 | [agi-extensions](https://github.com/Windstorm-Labs/agi-extensions) | 🚧 In Progress | 32-56 hrs RTX 5090 | 6 new experiments |

Legend: ✅ Complete (paper + code) | ✅ Published (paper on Zenodo) | 🚧 In Progress

---

## Quick Links

- **Paper Publications:** https://github.com/Windstorm-Institute
- **Institute Website:** https://windstorminstitute.org
- **Principal Investigator:** Grant Lavell Whitmer III

---

## Reproducibility

All experiments designed for:
- **Hardware:** NVIDIA RTX 5090 (32GB VRAM)
- **OS:** Ubuntu 24.04
- **Python:** 3.11+

See individual repository READMEs for:
- Quick start instructions
- Exact dependency versions
- Runtime estimates
- Results validation

---

## Contributing

Found an issue? [Open a ticket](../../issues)  
Want to extend? Fork and submit a PR  
Questions? Contact via institute website

---

*Code: MIT License | Data: CC BY 4.0*
