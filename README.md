# Paper List Template

This template makes it easy for you to manage papers.

## Table of Contents

- [Paper List Template](#paper-list-template)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)


## Getting Started
1. Add paper information by `./add_paper_info.sh` or  `./add_paper_info.sh <name>`
2. Run `./refresh_readme.sh`

<details><summary><b>sparsegpt.prototxt</b></summary>
<p>

```
paper {
  title: "SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot."
  abbr: "SparseGPT"
  url: "https://arxiv.org/pdf/2301.00774.pdf"
  authors: "Elias Frantar"
  authors: "Dan Alistarh"
  institutions: "IST Austria"
  institutions: "Neural Magic"
}
pub {
  where: "arXiv"
  year: 2023
}
code {
  type: "Pytorch"
  url: "https://github.com/IST-DASLab/sparsegpt"
}
note {
  url: "SparseGPT.md"
}
keyword {
  words: "sparsity"
}
```

</p>
</details>



## Paper List

<details open><summary>

### keyword
</summary> 
<p>

<details open><summary><b>Distributed</b></summary> 
<p>

|    | meta                                         | title                                                                      | publication   |   year | code                                                        | note   | cover   |
|---:|:---------------------------------------------|:---------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------------|:-------|:--------|
|  0 | [Decentralized_FM](./meta/WD3EMM1O.prototxt) | [Decentralized_FM_alpha](https://github.com/DS3Lab/Decentralized_FM_alpha) | Github        |   2022 | [Pytorch](https://github.com/DS3Lab/Decentralized_FM_alpha) |        |         |</p>
</details>
<details open><summary><b>Quantization</b></summary> 
<p>

|    | meta                         | title                                                                                                            | publication   |   year | code                                            | note   | cover   |
|---:|:-----------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------|:-------|:--------|
|  0 | [RPTQ](./meta/RPTQ.prototxt) | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM) |        |         |</p>
</details>
<details open><summary><b>Sparse/Pruning</b></summary> 
<p>

|    | meta                                                | title                                                                                                                                                                                                                                    | publication   |   year | code                                                 | note                                   | cover                                                            |
|---:|:----------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-----------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [Deep Compression](./meta/deepcompression.prototxt) | Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding                                                                                                                                 | ICLR          |   2016 |                                                      |                                        |                                                                  |
|  1 | [OpenVINO](./meta/OpenVINO.prototxt)                | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |                                                      |                                        |                                                                  |
|  2 | [abbr](./meta/22C0A4RH.prototxt)                    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                                                                           | ICLR          |   2023 |                                                      |                                        |                                                                  |
|  3 | [abbr](./meta/9O673CMS.prototxt)                    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                                                                                     | ICLR          |   2023 |                                                      |                                        |                                                                  |
|  4 | [MVUE](./meta/2U5DXO7C.prototxt)                    | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj)                                                                                                                             | ICLR          |   2023 |                                                      |                                        |                                                                  |
|  5 | [abbr](./meta/4IT9WPPA.prototxt)                    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                                                                                  | ICLR          |   2023 |                                                      |                                        |                                                                  |
|  6 | [abbr](./meta/GEZARAUL.prototxt)                    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                                                                                   | ICLR          |   2023 |                                                      |                                        |                                                                  |
|  7 | [SMC](./meta/EHWNTP1V.prototxt)                     | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp)                                                                                                                    | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench) |                                        |                                                                  |
|  8 | [SparseGPT](./meta/sparsegpt.prototxt)              | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf)                                                                                                                         | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt)   | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
</p>
</details>

<details><summary>

### year
</summary> 
<p>

<details><summary><b>2016</b></summary> 
<p>

|    | meta                                                | title                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:----------------------------------------------------|:---------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [Deep Compression](./meta/deepcompression.prototxt) | Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding | ICLR          |   2016 |        |        |         |</p>
</details>
<details><summary><b>2021</b></summary> 
<p>

|    | meta                                 | title                                                                                                                                                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [OpenVINO](./meta/OpenVINO.prototxt) | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |        |        |         |</p>
</details>
<details><summary><b>2022</b></summary> 
<p>

|    | meta                                         | title                                                                      | publication   |   year | code                                                        | note   | cover   |
|---:|:---------------------------------------------|:---------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------------|:-------|:--------|
|  0 | [Decentralized_FM](./meta/WD3EMM1O.prototxt) | [Decentralized_FM_alpha](https://github.com/DS3Lab/Decentralized_FM_alpha) | Github        |   2022 | [Pytorch](https://github.com/DS3Lab/Decentralized_FM_alpha) |        |         |</p>
</details>
<details><summary><b>2023</b></summary> 
<p>

|    | meta                                   | title                                                                                                                                                                             | publication   |   year | code                                                  | note                                   | cover                                                            |
|---:|:---------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [abbr](./meta/BU38BOQE.prototxt)       | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  1 | [abbr](./meta/SP5UN1RF.prototxt)       | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  2 | [abbr](./meta/Q3S45CWC.prototxt)       | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  3 | [abbr](./meta/JBRI286F.prototxt)       | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  4 | [abbr](./meta/22C0A4RH.prototxt)       | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  5 | [abbr](./meta/TVCZSVZY.prototxt)       | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  6 | [abbr](./meta/ZHVKFNSL.prototxt)       | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  7 | [abbr](./meta/9O673CMS.prototxt)       | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  8 | [abbr](./meta/Q0PKEEPI.prototxt)       | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |                                        |                                                                  |
|  9 | [abbr](./meta/AZKA1WRH.prototxt)       | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 10 | [abbr](./meta/RR92I0FK.prototxt)       | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 11 | [abbr](./meta/CSUM4GXD.prototxt)       | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 12 | [MVUE](./meta/2U5DXO7C.prototxt)       | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj)                                                                      | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 13 | [NTK-SAP](./meta/HYTID4WD.prototxt)    | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 14 | [OTOv2](./meta/QBBMHBHQ.prototxt)      | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |                                        |                                                                  |
| 15 | [abbr](./meta/1EZ5JYL3.prototxt)       | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 16 | [abbr](./meta/4IT9WPPA.prototxt)       | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 17 | [abbr](./meta/GEZARAUL.prototxt)       | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 18 | [m](./meta/0I1IQIH6.prototxt)          | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 19 | [abbr](./meta/DLHYYZU1.prototxt)       | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 20 | [SMC](./meta/EHWNTP1V.prototxt)        | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp)                                                             | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench)  |                                        |                                                                  |
| 21 | [m](./meta/RRGOXITB.prototxt)          | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 22 | [abbr](./meta/MTKTZE3N.prototxt)       | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 23 | [m](./meta/R4X91L5N.prototxt)          | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |                                        |                                                                  |
| 24 | [RPTQ](./meta/RPTQ.prototxt)           | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf)                                                                  | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM)       |                                        |                                                                  |
| 25 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf)                                                                  | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt)    | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
</p>
</details>

<details><summary>

### publication
</summary> 
<p>

<details><summary><b>Github</b></summary> 
<p>

|    | meta                                         | title                                                                      | publication   |   year | code                                                        | note   | cover   |
|---:|:---------------------------------------------|:---------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------------|:-------|:--------|
|  0 | [Decentralized_FM](./meta/WD3EMM1O.prototxt) | [Decentralized_FM_alpha](https://github.com/DS3Lab/Decentralized_FM_alpha) | Github        |   2022 | [Pytorch](https://github.com/DS3Lab/Decentralized_FM_alpha) |        |         |</p>
</details>
<details><summary><b>ICCV workshop</b></summary> 
<p>

|    | meta                                 | title                                                                                                                                                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [OpenVINO](./meta/OpenVINO.prototxt) | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |        |        |         |</p>
</details>
<details><summary><b>ICLR</b></summary> 
<p>

|    | meta                                                | title                                                                                                                                                                             | publication   |   year | code                                                  | note   | cover   |
|---:|:----------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:-------|:--------|
|  0 | [Deep Compression](./meta/deepcompression.prototxt) | Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding                                                                          | ICLR          |   2016 |                                                       |        |         |
|  1 | [abbr](./meta/BU38BOQE.prototxt)                    | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |        |         |
|  2 | [abbr](./meta/SP5UN1RF.prototxt)                    | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |        |         |
|  3 | [abbr](./meta/Q3S45CWC.prototxt)                    | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |        |         |
|  4 | [abbr](./meta/JBRI286F.prototxt)                    | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |        |         |
|  5 | [abbr](./meta/22C0A4RH.prototxt)                    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  6 | [abbr](./meta/TVCZSVZY.prototxt)                    | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  7 | [abbr](./meta/ZHVKFNSL.prototxt)                    | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |        |         |
|  8 | [abbr](./meta/9O673CMS.prototxt)                    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |        |         |
|  9 | [abbr](./meta/Q0PKEEPI.prototxt)                    | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |        |         |
| 10 | [abbr](./meta/AZKA1WRH.prototxt)                    | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |        |         |
| 11 | [abbr](./meta/RR92I0FK.prototxt)                    | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |        |         |
| 12 | [abbr](./meta/CSUM4GXD.prototxt)                    | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |        |         |
| 13 | [MVUE](./meta/2U5DXO7C.prototxt)                    | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj)                                                                      | ICLR          |   2023 |                                                       |        |         |
| 14 | [NTK-SAP](./meta/HYTID4WD.prototxt)                 | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |        |         |
| 15 | [OTOv2](./meta/QBBMHBHQ.prototxt)                   | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |        |         |
| 16 | [abbr](./meta/1EZ5JYL3.prototxt)                    | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |        |         |
| 17 | [abbr](./meta/4IT9WPPA.prototxt)                    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |        |         |
| 18 | [abbr](./meta/GEZARAUL.prototxt)                    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |        |         |
| 19 | [m](./meta/0I1IQIH6.prototxt)                       | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |        |         |
| 20 | [abbr](./meta/DLHYYZU1.prototxt)                    | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |        |         |
| 21 | [SMC](./meta/EHWNTP1V.prototxt)                     | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp)                                                             | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench)  |        |         |
| 22 | [m](./meta/RRGOXITB.prototxt)                       | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |        |         |
| 23 | [abbr](./meta/MTKTZE3N.prototxt)                    | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |        |         |
| 24 | [m](./meta/R4X91L5N.prototxt)                       | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |        |         |</p>
</details>
<details><summary><b>arXiv</b></summary> 
<p>

|    | meta                                   | title                                                                                                            | publication   |   year | code                                               | note                                   | cover                                                            |
|---:|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:---------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [RPTQ](./meta/RPTQ.prototxt)           | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM)    |                                        |                                                                  |
|  1 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf) | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt) | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
</p>
</details>

<details><summary>

### instution
</summary> 
<p>

<details><summary><b>DS3Lab</b></summary> 
<p>

|    | meta                                         | title                                                                      | publication   |   year | code                                                        | note   | cover   |
|---:|:---------------------------------------------|:---------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------------|:-------|:--------|
|  0 | [Decentralized_FM](./meta/WD3EMM1O.prototxt) | [Decentralized_FM_alpha](https://github.com/DS3Lab/Decentralized_FM_alpha) | Github        |   2022 | [Pytorch](https://github.com/DS3Lab/Decentralized_FM_alpha) |        |         |</p>
</details>
<details><summary><b>Eindhoven University of Technology</b></summary> 
<p>

|    | meta                            | title                                                                                                                 | publication   |   year | code                                                 | note   | cover   |
|---:|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-----------------------------------------------------|:-------|:--------|
|  0 | [SMC](./meta/EHWNTP1V.prototxt) | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp) | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench) |        |         |</p>
</details>
<details><summary><b>Habana Labs</b></summary> 
<p>

|    | meta                             | title                                                                                                        | publication   |   year | code   | note   | cover   |
|---:|:---------------------------------|:-------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [MVUE](./meta/2U5DXO7C.prototxt) | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj) | ICLR          |   2023 |        |        |         |</p>
</details>
<details><summary><b>Houmo AI</b></summary> 
<p>

|    | meta                         | title                                                                                                            | publication   |   year | code                                            | note   | cover   |
|---:|:-----------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------|:-------|:--------|
|  0 | [RPTQ](./meta/RPTQ.prototxt) | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM) |        |         |</p>
</details>
<details><summary><b>IST Austria</b></summary> 
<p>

|    | meta                                   | title                                                                                                            | publication   |   year | code                                               | note                                   | cover                                                            |
|---:|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:---------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf) | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt) | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
<details><summary><b>Intel Corporation</b></summary> 
<p>

|    | meta                                 | title                                                                                                                                                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [OpenVINO](./meta/OpenVINO.prototxt) | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |        |        |         |</p>
</details>
<details><summary><b>Neural Magic</b></summary> 
<p>

|    | meta                                   | title                                                                                                            | publication   |   year | code                                               | note                                   | cover                                                            |
|---:|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:---------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf) | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt) | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
<details><summary><b>Stanford University</b></summary> 
<p>

|    | meta                                                | title                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:----------------------------------------------------|:---------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [Deep Compression](./meta/deepcompression.prototxt) | Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding | ICLR          |   2016 |        |        |         |</p>
</details>
<details><summary><b>Tencent AI Lab</b></summary> 
<p>

|    | meta                         | title                                                                                                            | publication   |   year | code                                            | note   | cover   |
|---:|:-----------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------|:-------|:--------|
|  0 | [RPTQ](./meta/RPTQ.prototxt) | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM) |        |         |</p>
</details>
<details><summary><b>University of Texas at Austin</b></summary> 
<p>

|    | meta                            | title                                                                                                                 | publication   |   year | code                                                 | note   | cover   |
|---:|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-----------------------------------------------------|:-------|:--------|
|  0 | [SMC](./meta/EHWNTP1V.prototxt) | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp) | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench) |        |         |</p>
</details>
<details><summary><b>inst1</b></summary> 
<p>

|    | meta                                | title                                                                                                                                                                             | publication   |   year | code                                                  | note   | cover   |
|---:|:------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:-------|:--------|
|  0 | [abbr](./meta/BU38BOQE.prototxt)    | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |        |         |
|  1 | [abbr](./meta/SP5UN1RF.prototxt)    | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |        |         |
|  2 | [abbr](./meta/Q3S45CWC.prototxt)    | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |        |         |
|  3 | [abbr](./meta/JBRI286F.prototxt)    | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |        |         |
|  4 | [abbr](./meta/22C0A4RH.prototxt)    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  5 | [abbr](./meta/TVCZSVZY.prototxt)    | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  6 | [abbr](./meta/ZHVKFNSL.prototxt)    | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |        |         |
|  7 | [abbr](./meta/9O673CMS.prototxt)    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |        |         |
|  8 | [abbr](./meta/Q0PKEEPI.prototxt)    | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |        |         |
|  9 | [abbr](./meta/AZKA1WRH.prototxt)    | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |        |         |
| 10 | [abbr](./meta/RR92I0FK.prototxt)    | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |        |         |
| 11 | [abbr](./meta/CSUM4GXD.prototxt)    | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |        |         |
| 12 | [NTK-SAP](./meta/HYTID4WD.prototxt) | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |        |         |
| 13 | [OTOv2](./meta/QBBMHBHQ.prototxt)   | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |        |         |
| 14 | [abbr](./meta/1EZ5JYL3.prototxt)    | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |        |         |
| 15 | [abbr](./meta/4IT9WPPA.prototxt)    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |        |         |
| 16 | [abbr](./meta/GEZARAUL.prototxt)    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |        |         |
| 17 | [m](./meta/0I1IQIH6.prototxt)       | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |        |         |
| 18 | [abbr](./meta/DLHYYZU1.prototxt)    | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |        |         |
| 19 | [m](./meta/RRGOXITB.prototxt)       | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |        |         |
| 20 | [abbr](./meta/MTKTZE3N.prototxt)    | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |        |         |
| 21 | [m](./meta/R4X91L5N.prototxt)       | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |        |         |</p>
</details>
<details><summary><b>inst2</b></summary> 
<p>

|    | meta                                | title                                                                                                                                                                             | publication   |   year | code                                                  | note   | cover   |
|---:|:------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:-------|:--------|
|  0 | [abbr](./meta/BU38BOQE.prototxt)    | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |        |         |
|  1 | [abbr](./meta/SP5UN1RF.prototxt)    | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |        |         |
|  2 | [abbr](./meta/Q3S45CWC.prototxt)    | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |        |         |
|  3 | [abbr](./meta/JBRI286F.prototxt)    | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |        |         |
|  4 | [abbr](./meta/22C0A4RH.prototxt)    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  5 | [abbr](./meta/TVCZSVZY.prototxt)    | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  6 | [abbr](./meta/ZHVKFNSL.prototxt)    | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |        |         |
|  7 | [abbr](./meta/9O673CMS.prototxt)    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |        |         |
|  8 | [abbr](./meta/Q0PKEEPI.prototxt)    | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |        |         |
|  9 | [abbr](./meta/AZKA1WRH.prototxt)    | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |        |         |
| 10 | [abbr](./meta/RR92I0FK.prototxt)    | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |        |         |
| 11 | [abbr](./meta/CSUM4GXD.prototxt)    | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |        |         |
| 12 | [NTK-SAP](./meta/HYTID4WD.prototxt) | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |        |         |
| 13 | [OTOv2](./meta/QBBMHBHQ.prototxt)   | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |        |         |
| 14 | [abbr](./meta/1EZ5JYL3.prototxt)    | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |        |         |
| 15 | [abbr](./meta/4IT9WPPA.prototxt)    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |        |         |
| 16 | [abbr](./meta/GEZARAUL.prototxt)    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |        |         |
| 17 | [m](./meta/0I1IQIH6.prototxt)       | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |        |         |
| 18 | [abbr](./meta/DLHYYZU1.prototxt)    | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |        |         |
| 19 | [m](./meta/RRGOXITB.prototxt)       | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |        |         |
| 20 | [abbr](./meta/MTKTZE3N.prototxt)    | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |        |         |
| 21 | [m](./meta/R4X91L5N.prototxt)       | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |        |         |</p>
</details>
</p>
</details>

<details><summary>

### author
</summary> 
<p>

<details><summary><b>Bingzhe Wu</b></summary> 
<p>

|    | meta                         | title                                                                                                            | publication   |   year | code                                            | note   | cover   |
|---:|:-----------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------|:-------|:--------|
|  0 | [RPTQ](./meta/RPTQ.prototxt) | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM) |        |         |</p>
</details>
<details><summary><b>Brian Chmiel</b></summary> 
<p>

|    | meta                             | title                                                                                                        | publication   |   year | code   | note   | cover   |
|---:|:---------------------------------|:-------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [MVUE](./meta/2U5DXO7C.prototxt) | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj) | ICLR          |   2023 |        |        |         |</p>
</details>
<details><summary><b>Dan Alistarh</b></summary> 
<p>

|    | meta                                   | title                                                                                                            | publication   |   year | code                                               | note                                   | cover                                                            |
|---:|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:---------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf) | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt) | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
<details><summary><b>Daniel Soudry</b></summary> 
<p>

|    | meta                             | title                                                                                                        | publication   |   year | code   | note   | cover   |
|---:|:---------------------------------|:-------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [MVUE](./meta/2U5DXO7C.prototxt) | [Minimum Variance Unbiased N:M Sparsity for the Neural Gradients](https://openreview.net/pdf?id=vuD2xEtxZcj) | ICLR          |   2023 |        |        |         |</p>
</details>
<details><summary><b>Elias Frantar</b></summary> 
<p>

|    | meta                                   | title                                                                                                            | publication   |   year | code                                               | note                                   | cover                                                            |
|---:|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:---------------------------------------------------|:---------------------------------------|:-----------------------------------------------------------------|
|  0 | [SparseGPT](./meta/sparsegpt.prototxt) | [SparseGPT: Massive Language Models Can be Accurately Pruned in one-shot.](https://arxiv.org/pdf/2301.00774.pdf) | arXiv         |   2023 | [Pytorch](https://github.com/IST-DASLab/sparsegpt) | [note](./notes/sparsegpt/SparseGPT.md) | <img width='1000' alt='image' src='./notes/sparsegpt/cover.jpg'> |</p>
</details>
<details><summary><b>Ivan Lazarevich</b></summary> 
<p>

|    | meta                                 | title                                                                                                                                                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [OpenVINO](./meta/OpenVINO.prototxt) | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |        |        |         |</p>
</details>
<details><summary><b>Jue Wang</b></summary> 
<p>

|    | meta                                         | title                                                                      | publication   |   year | code                                                        | note   | cover   |
|---:|:---------------------------------------------|:---------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------------|:-------|:--------|
|  0 | [Decentralized_FM](./meta/WD3EMM1O.prototxt) | [Decentralized_FM_alpha](https://github.com/DS3Lab/Decentralized_FM_alpha) | Github        |   2022 | [Pytorch](https://github.com/DS3Lab/Decentralized_FM_alpha) |        |         |</p>
</details>
<details><summary><b>Name1</b></summary> 
<p>

|    | meta                                | title                                                                                                                                                                             | publication   |   year | code                                                  | note   | cover   |
|---:|:------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:-------|:--------|
|  0 | [abbr](./meta/BU38BOQE.prototxt)    | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |        |         |
|  1 | [abbr](./meta/SP5UN1RF.prototxt)    | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |        |         |
|  2 | [abbr](./meta/Q3S45CWC.prototxt)    | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |        |         |
|  3 | [abbr](./meta/JBRI286F.prototxt)    | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |        |         |
|  4 | [abbr](./meta/22C0A4RH.prototxt)    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  5 | [abbr](./meta/TVCZSVZY.prototxt)    | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  6 | [abbr](./meta/ZHVKFNSL.prototxt)    | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |        |         |
|  7 | [abbr](./meta/9O673CMS.prototxt)    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |        |         |
|  8 | [abbr](./meta/Q0PKEEPI.prototxt)    | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |        |         |
|  9 | [abbr](./meta/AZKA1WRH.prototxt)    | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |        |         |
| 10 | [abbr](./meta/RR92I0FK.prototxt)    | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |        |         |
| 11 | [abbr](./meta/CSUM4GXD.prototxt)    | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |        |         |
| 12 | [NTK-SAP](./meta/HYTID4WD.prototxt) | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |        |         |
| 13 | [OTOv2](./meta/QBBMHBHQ.prototxt)   | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |        |         |
| 14 | [abbr](./meta/1EZ5JYL3.prototxt)    | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |        |         |
| 15 | [abbr](./meta/4IT9WPPA.prototxt)    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |        |         |
| 16 | [abbr](./meta/GEZARAUL.prototxt)    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |        |         |
| 17 | [m](./meta/0I1IQIH6.prototxt)       | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |        |         |
| 18 | [abbr](./meta/DLHYYZU1.prototxt)    | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |        |         |
| 19 | [m](./meta/RRGOXITB.prototxt)       | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |        |         |
| 20 | [abbr](./meta/MTKTZE3N.prototxt)    | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |        |         |
| 21 | [m](./meta/R4X91L5N.prototxt)       | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |        |         |</p>
</details>
<details><summary><b>Name2</b></summary> 
<p>

|    | meta                                | title                                                                                                                                                                             | publication   |   year | code                                                  | note   | cover   |
|---:|:------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------------|:-------|:--------|
|  0 | [abbr](./meta/BU38BOQE.prototxt)    | [A General Framework For Proving The Equivariant Strong Lottery Ticket Hypothesis](https://openreview.net/forum?id=vVJZtlZB9D)                                                    | ICLR          |   2023 |                                                       |        |         |
|  1 | [abbr](./meta/SP5UN1RF.prototxt)    | [A Unified Framework for Soft Threshold Pruning](https://openreview.net/forum?id=cCFqcrq0d8)                                                                                      | ICLR          |   2023 |                                                       |        |         |
|  2 | [abbr](./meta/Q3S45CWC.prototxt)    | [Bit-Pruning: A Sparse Multiplication-Less Dot-Product](https://openreview.net/forum?id=YUDiZcZTI8)                                                                               | ICLR          |   2023 |                                                       |        |         |
|  3 | [abbr](./meta/JBRI286F.prototxt)    | [CrAM: A Compression-Aware Minimizer](https://openreview.net/forum?id=_eTZBs-yedr)                                                                                                | ICLR          |   2023 |                                                       |        |         |
|  4 | [abbr](./meta/22C0A4RH.prototxt)    | [DFPC: Data flow driven pruning of coupled channels without data](https://openreview.net/forum?id=mhnHqRqcjYU)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  5 | [abbr](./meta/TVCZSVZY.prototxt)    | [DepthFL: Depthwise Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=pf8RIZTMU58)                                                                    | ICLR          |   2023 |                                                       |        |         |
|  6 | [abbr](./meta/ZHVKFNSL.prototxt)    | [Diffusion Models for Causal Discovery via Topological Ordering](https://openreview.net/forum?id=Idusfje4-Wq)                                                                     | ICLR          |   2023 |                                                       |        |         |
|  7 | [abbr](./meta/9O673CMS.prototxt)    | [Holistic Adversarially Robust Pruning](https://openreview.net/forum?id=sAJDi9lD06L)                                                                                              | ICLR          |   2023 |                                                       |        |         |
|  8 | [abbr](./meta/Q0PKEEPI.prototxt)    | [HomoDistil: Homotopic Task-Agnostic Distillation of Pre-trained Transformers](https://openreview.net/forum?id=D7srTrGhAs)                                                        | ICLR          |   2023 |                                                       |        |         |
|  9 | [abbr](./meta/AZKA1WRH.prototxt)    | [How I Learned to Stop Worrying and Love Retraining](https://openreview.net/forum?id=_nF5imFKQI)                                                                                  | ICLR          |   2023 |                                                       |        |         |
| 10 | [abbr](./meta/RR92I0FK.prototxt)    | [Joint Edge-Model Sparse Learning is Provably Efficient for Graph Neural Networks](https://openreview.net/forum?id=4UldFtZ_CVF)                                                   | ICLR          |   2023 |                                                       |        |         |
| 11 | [abbr](./meta/CSUM4GXD.prototxt)    | [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh)                                                                        | ICLR          |   2023 |                                                       |        |         |
| 12 | [NTK-SAP](./meta/HYTID4WD.prototxt) | [NTK-SAP: Improving neural network pruning by aligning training dynamics](https://openreview.net/forum?id=-5EWhW_4qWP)                                                            | ICLR          |   2023 |                                                       |        |         |
| 13 | [OTOv2](./meta/QBBMHBHQ.prototxt)   | [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/forum?id=7ynoX1ojPMt)                                                                                           | ICLR          |   2023 | [Pytorch](https://github.com/tianyic/only_train_once) |        |         |
| 14 | [abbr](./meta/1EZ5JYL3.prototxt)    | [Over-parameterized Model Optimization with Polyak-Lojasiewicz Condition](https://openreview.net/forum?id=aBIpZvMdS56)                                                            | ICLR          |   2023 |                                                       |        |         |
| 15 | [abbr](./meta/4IT9WPPA.prototxt)    | [Pruning Deep Neural Networks from a Sparsity Perspective](https://openreview.net/forum?id=i-DleYh34BM)                                                                           | ICLR          |   2023 |                                                       |        |         |
| 16 | [abbr](./meta/GEZARAUL.prototxt)    | [Rethinking Graph Lottery Tickets: Graph Sparsity Matters](https://openreview.net/forum?id=fjh7UGQgOB)                                                                            | ICLR          |   2023 |                                                       |        |         |
| 17 | [m](./meta/0I1IQIH6.prototxt)       | [Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph](https://openreview.net/forum?id=uVcDssQff)                                                             | ICLR          |   2023 |                                                       |        |         |
| 18 | [abbr](./meta/DLHYYZU1.prototxt)    | [Searching Lottery Tickets in Graph Neural Networks: A Dual Perspective](https://openreview.net/forum?id=Dvs-a3aymPe)                                                             | ICLR          |   2023 |                                                       |        |         |
| 19 | [m](./meta/RRGOXITB.prototxt)       | [Symmetric Pruning in Quantum Neural Networks](https://openreview.net/forum?id=K96AogLDT2K)                                                                                       | ICLR          |   2023 |                                                       |        |         |
| 20 | [abbr](./meta/MTKTZE3N.prototxt)    | [TVSPrune - Pruning Non-discriminative filters via Total Variation separability of intermediate representations without fine tuning](https://openreview.net/forum?id=sZI1Oj9KBKy) | ICLR          |   2023 |                                                       |        |         |
| 21 | [m](./meta/R4X91L5N.prototxt)       | [Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask?](https://openreview.net/forum?id=xSsW2Am-ukZ)                                                | ICLR          |   2023 |                                                       |        |         |</p>
</details>
<details><summary><b>Nikita Malinin</b></summary> 
<p>

|    | meta                                 | title                                                                                                                                                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [OpenVINO](./meta/OpenVINO.prototxt) | [Post-training deep neural network pruning via layer-wise calibration](https://openaccess.thecvf.com/content/ICCV2021W/LPCV/papers/Lazarevich_Post-Training_Deep_Neural_Network_Pruning_via_Layer-Wise_Calibration_ICCVW_2021_paper.pdf) | ICCV workshop |   2021 |        |        |         |</p>
</details>
<details><summary><b>Shiwei Liu</b></summary> 
<p>

|    | meta                            | title                                                                                                                 | publication   |   year | code                                                 | note   | cover   |
|---:|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-----------------------------------------------------|:-------|:--------|
|  0 | [SMC](./meta/EHWNTP1V.prototxt) | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp) | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench) |        |         |</p>
</details>
<details><summary><b>Song Han</b></summary> 
<p>

|    | meta                                                | title                                                                                                    | publication   |   year | code   | note   | cover   |
|---:|:----------------------------------------------------|:---------------------------------------------------------------------------------------------------------|:--------------|-------:|:-------|:-------|:--------|
|  0 | [Deep Compression](./meta/deepcompression.prototxt) | Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding | ICLR          |   2016 |        |        |         |</p>
</details>
<details><summary><b>Zhangyang Wang</b></summary> 
<p>

|    | meta                            | title                                                                                                                 | publication   |   year | code                                                 | note   | cover   |
|---:|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------|:--------------|-------:|:-----------------------------------------------------|:-------|:--------|
|  0 | [SMC](./meta/EHWNTP1V.prototxt) | [Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!](https://openreview.net/pdf?id=J6F3lLg4Kdp) | ICLR          |   2023 | [SMC-Bench](https://github.com/VITA-Group/SMC-Bench) |        |         |</p>
</details>
<details><summary><b>Zhihang Yuan</b></summary> 
<p>

|    | meta                         | title                                                                                                            | publication   |   year | code                                            | note   | cover   |
|---:|:-----------------------------|:-----------------------------------------------------------------------------------------------------------------|:--------------|-------:|:------------------------------------------------|:-------|:--------|
|  0 | [RPTQ](./meta/RPTQ.prototxt) | [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/pdf/2304.01089.pdf) | arXiv         |   2023 | [PyTorch](https://github.com/hahnyuan/RPTQ4LLM) |        |         |</p>
</details>
</p>
</details>


## References

1. https://github.com/he-y/Awesome-Pruning
2. https://github.com/htqin/awesome-model-quantization
3. https://github.com/csyhhu/Awesome-Deep-Neural-Network-Compression/tree/master
4. https://github.com/AojunZhou/Efficient-Deep-Learning
5. https://github.com/chester256/Model-Compression-Papers
