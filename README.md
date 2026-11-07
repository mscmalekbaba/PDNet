# PDNet

**Paper:** [PDNet: Exploring Pruning and Distillation for Real-Time Worker Activity Recognition in Industrial Assembly](https://doi.org/10.5220/0014477200004084)

## Abstract

In this work, we address real-time fine-grained human activity recognition (HAR) in industrial assembly and introduce PDNet, a new framework that jointly exploits structured pruning and knowledge distillation for 3D convolutional networks. We start by training a 3D-CNN backbone in a supervised manner. Then, PDNet applies channel-wise structured pruning to obtain a more compact network. In the third step, our method is optimized using knowledge distillation from the large unpruned teacher to recover accuracy lost due to pruning. On the challenging MECCANO dataset with an X3D-M backbone, the pruned model without distillation reaches a Top-1 accuracy of 25.54 %, while PDNet raises this to 39.46 %, with only 6.90 MB model size and 3.78 GFLOPs. These results show that distillation within PDNet is highly effective in restoring pruned model performance and highlight its high potential for resource-constrained HAR in industrial assembly.

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
