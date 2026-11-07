# PDNet

**Project resources for the paper:** [arXiv:2610.26491](https://arxiv.org/abs/2610.26491)

PDNet explores resource-efficient video-based recognition of worker activities in industrial assembly settings. This repository is the project home for the paper, its external dataset and framework references, and the documentation needed to organize code and reproducibility materials as they are released.

## Abstract

Recognizing worker activities from video can support understanding of industrial assembly workflows, but video models can be expensive to train and run. PDNet investigates a resource-efficient approach to this problem, using spatiotemporal video modeling based on the SlowFast framework and the MECCANO egocentric industrial-activity dataset. The project focuses on the practical balance between recognition capability and computational cost, and documents model-efficiency techniques including structured pruning and knowledge distillation. This repository links the paper to its dataset and framework resources and provides a place to publish implementation details, evaluation protocols, and results. Please consult the paper for the precise method, experimental setup, and reported findings.

> This is a repository summary, not a verbatim abstract. See the [paper](https://arxiv.org/abs/2610.26491) for the authors' official abstract and results.

## Paper and citation

- **Paper:** [arXiv:2610.26491](https://arxiv.org/abs/2610.26491)
- **Citation metadata:** [`CITATION.cff`](CITATION.cff)

BibTeX starter entry (replace the author and title placeholders with the exact arXiv metadata before citing):

```bibtex
@misc{pdnet2026,
  title         = {PDNet},
  author        = {{AUTHORS}},
  year          = {2026},
  eprint        = {2610.26491},
  archivePrefix = {arXiv},
  url           = {https://arxiv.org/abs/2610.26491}
}
```

## Data and methods

- **MECCANO dataset:** [official dataset repository](https://github.com/fpv-iplab/MECCANO). Obtain the data from its maintainers and follow their terms. This repository does not redistribute dataset files.
- **SlowFast / PySlowFast:** [official implementation](https://github.com/facebookresearch/SlowFast).
- **SlowFast paper:** [SlowFast Networks for Video Recognition](https://arxiv.org/abs/1812.03982).
- **Related implementation:** [Master-Thesis-Resource-Efficient-PySlowFast](https://github.com/mscmalekbaba/Master-Thesis-Resource-Efficient-PySlowFast).

See [`data/`](data/README.md), [`methods/`](methods/README.md), and [`reproducibility/`](reproducibility/README.md) for how project materials are organized.

## Repository structure

```text
.
├── data/             Dataset references and setup notes (no dataset files)
├── methods/          Model, framework, and method references
├── paper/            Paper links and publication materials
└── reproducibility/  Environment, evaluation, and experiment documentation
```

## Status

This repository currently serves as a project landing page and resource index. Implementation code, detailed instructions, and experimental artifacts will be added when ready. For now, use the linked paper and related implementation repository as the authoritative sources; do not infer missing hyperparameters or results from this overview.
