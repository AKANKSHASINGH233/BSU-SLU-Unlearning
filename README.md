# BSU-SLU-Unlearning
# Binding Subspace Unlearning for Selective Capability Removal in End-to-End Spoken Language Understanding

Official project page for the INTERSPEECH paper:

**Selective Capability Unlearning in End-to-End Spoken Language Understanding**

This work studies selective capability unlearning in end-to-end spoken language understanding (SLU). We show that suppressing the marginal probability of a target intent is insufficient in autoregressive SLU models, because the associated slot-generation behavior can remain recoverable when the target intent prefix is externally supplied. We refer to this failure mode as **capability persistence**.

To address this problem, we propose **Binding Subspace Unlearning (BSU)**, a representation-level framework that identifies intent-conditioned binding directions through covariance contrast and attenuates model sensitivity along these directions. BSU is designed to reduce forced-prefix slot recoverability while preserving retained-intent performance.

## Status

Code release: coming soon.

The implementation, training scripts, evaluation protocol, and configuration files will be released after final cleanup and reproducibility checks.

## Paper

**Selective Capability Unlearning in End-to-End Spoken Language Understanding**
Akanksha Singh and Vinod Kumar Kurmi
Indian Institute of Science Education and Research Bhopal, India
INTERSPEECH 2026

## Abstract

Modern spoken language understanding systems are increasingly deployed in settings where specific functionalities may need to be removed due to policy or safety constraints. In SLU, a functionality corresponds to an intent and its associated slot-generation behavior. However, in autoregressive models, suppressing a target intent does not eliminate the conditional mapping that generates slots conditioned on that intent. When the intent prefix is externally supplied, the model can reconstruct the original intent-slot structure. We identify this structural failure as capability persistence. We propose Binding Subspace Unlearning (BSU), a representation-level framework that isolates and attenuates intent-conditioned directions underlying this mapping.

## Citation

```bibtex
@inproceedings{singh2026selective,
  title     = {Selective Capability Unlearning in End-to-End Spoken Language Understanding},
  author    = {Singh, Akanksha and Kurmi, Vinod Kumar},
  booktitle = {Proceedings of INTERSPEECH 2026},
  year      = {2026}
}
```

## License

License information will be added with the code release.
