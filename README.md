## Abdulrahman Neamah

Pharmacy undergraduate at Mustansiriyah University, Iraq. I work on computational protein
design — de novo binders, structure prediction, and the question of when a confidence score
deserves to be trusted.

Most of what's here comes from the **Adaptyv Bio × Anthropic protein design competition**
(Sep–Nov 2026), where I entered three of five challenges. Lab results are pending; design
sequences are withheld until they publish. Everything is run on free tooling — Tamarind Bio
and Google Colab.

---

**[kras-g12d-pmhc-binder](https://github.com/Abdulrahman-Neamah/kras-g12d-pmhc-binder)** — Mutation-specific binder to the KRAS G12D neoantigen on HLA-A\*11:01, discriminating against both the wild-type peptide and the empty MHC. A charge-biased ProteinMPNN redesign built an interface the parent scaffold did not have. The fullest writeup of the three, and the place to start.

**[egfr-conditional-binder](https://github.com/Abdulrahman-Neamah/egfr-conditional-binder)** — pH-conditional EGFR binder (Challenge 1), plus two negative results worth more than the positive one: the TNF-α challenge I abandoned, and a top-ranked TfR1 design that turned out to be threaded through its target at 0.41 Å while scoring well on every confidence metric available.

**[glp1r-agonist-binder-design](https://github.com/Abdulrahman-Neamah/glp1r-agonist-binder-design)** — De novo groove binders against full-length GLP-1R, designed against the whole receptor rather than the isolated extracellular domain. Includes an honest account of what the method cannot do: no predictor tells you whether a binder activates a receptor.

**[amp-design-colab](https://github.com/Abdulrahman-Neamah/amp-design-colab)** — Starter pipeline for antimicrobial peptide design in Colab. Work in progress.

---

A theme across these: confidence metrics are easy to over-read. ipTM and ipSAE disagreed on
15 of 20 designs in the KRAS work, and none of the standard interface scores contains a
steric term — which is how a physically impossible design came first in an earlier round.
Each repository states what was predicted, what was measured, and what neither establishes.

Interested in peptide and protein therapeutics, and in moving this kind of work from
prediction into the lab.
