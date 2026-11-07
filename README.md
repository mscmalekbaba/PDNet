# PDNet

**Paper:** [PDNet: Exploring Pruning and Distillation for Real-Time Worker Activity Recognition in Industrial Assembly](https://doi.org/10.5220/0014477200004084)

PDNet explores resource-efficient video-based recognition of worker activities in industrial assembly. The paper investigates structured pruning and knowledge distillation to reduce model cost while retaining activity-recognition capability, using the MECCANO dataset and SlowFast-based video modeling.

## Abstract

Worker activity recognition from video can support understanding of industrial assembly workflows, but video models can be costly to deploy in real time. PDNet explores pruning and distillation for real-time worker activity recognition in industrial assembly. The work studies structured pruning to reduce model parameters and distillation-based retraining to recover performance in a compact model. Experiments use the MECCANO egocentric industrial-activity dataset and SlowFast-based video modeling. See the [published paper](https://doi.org/10.5220/0014477200004084) for the official abstract, complete method, experimental setup, and results.

## Paper and citation

- **Title:** PDNet: Exploring Pruning and Distillation for Real-Time Worker Activity Recognition in Industrial Assembly
- **Proceedings:** [Proceedings of the 21st International Conference on Computer Vision Theory and Applications](https://doi.org/10.5220/0014477200004084), pp. 624–630, 2026
- **DOI:** [10.5220/0014477200004084](https://doi.org/10.5220/0014477200004084)
- **Citation metadata:** [`CITATION.cff`](CITATION.cff)

```bibtex
@inproceedings{Baba_2026,
  title     = {PDNet: Exploring Pruning and Distillation for Real-Time Worker Activity Recognition in Industrial Assembly},
  url       = {https://doi.org/10.5220/0014477200004084},
  doi       = {10.5220/0014477200004084},
  booktitle = {Proceedings of the 21st International Conference on Computer Vision Theory and Applications},
  publisher = {SCITEPRESS - Science and Technology Publications},
  author    = {Baba, Malek and Thiyakesan Ponbagavathi, Thinesh and Roitberg, Alina},
  year      = {2026},
  pages     = {624--630}
}
```

## Data and methods

- **MECCANO dataset:** [official dataset repository](https://github.com/fpv-iplab/MECCANO). Obtain the data from its maintainers and follow their access terms; this repository does not redistribute dataset files.
- **SlowFast / PySlowFast:** [official implementation](https://github.com/facebookresearch/SlowFast).
- **SlowFast paper:** [SlowFast Networks for Video Recognition](https://arxiv.org/abs/1812.03982).
- **Related implementation:** [Master-Thesis-Resource-Efficient-PySlowFast](https://github.com/mscmalekbaba/Master-Thesis-Resource-Efficient-PySlowFast).

See [`data/`](data/README.md), [`methods/`](methods/README.md), and [`reproducibility/`](reproducibility/README.md) for dataset, method, and reproduction notes.
