# Awesome-EHR-Generation[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>
A curated list of awesome papers for electronic health record (EHR) generation. :-)

<!-- ## Contributing
Please feel free to send me [pull requests](https://github.com/zhjohnchan/awesome-pretraining-in-nlp/pulls) or email (chihung.chan@outlook.com) to add links. -->

## Contents
- [Awesome-EHR-Generation](#awesome-ehr-generation)
  - [Contents](#contents)
  - [Papers](#papers)
    - [Surveys for EHR](#surveys-for-ehr)
    - [EHR Representation](#ehr-representation)
    - [Hybrid-type EHR Generation](#hybrid-type-ehr-generation)
    - [Tabular EHR Synthesis](#tabular-ehr-synthesis)
      - [Difussion Models](#difussion-models)
      - [GAN \& VAE Style](#gan--vae-style)
      - [Others](#others)
    - [Text EHR Generation](#text-ehr-generation)
  - [Utility Evaluation Benchmarks](#utility-evaluation-benchmarks)
## Papers
### Surveys for EHR
| Survey     | Authors        | Year |
|------------|----------------|------|
|[Mining Electronic Health Records (EHRs): A Survey](https://dl.acm.org/doi/pdf/10.1145/3127881)|Pranjul Yadav, Michael Steinbach, Vipin Kumar, Gyorgy Simon|2018|
|[Deep EHR: A Survey of Recent Advances in Deep Learning Techniques for Electronic Health Record (EHR) Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8086133)|Benjamin Shickel, Patrick James Tighe, Azra Bihorac, Parisa Rashidi|2017

### EHR Representation
| Method      | Veneue  | Reference           | Authors | Code  |
|-------------|---------|---------------------|---------|-------|
|EVA          |MLHC-2021|[EVA: Generating Longitudinal Electronic Health Records Using Conditional Variational Autoencoders](https://arxiv.org/pdf/2012.10020.pdf)| Siddharth Biswal, Soumya Ghosh, Jon Duke, Bradley Malin, Walter Stewart, Cao Xiao, Jimeng Sun |
|Clinial XLNet|CNLP-2020|[Clinical XLNet: Modeling Sequential Clinical Notes and Predicting Prolonged Mechanical Ventilation](https://arxiv.org/pdf/1912.11975.pdf)|Kexin Huang, Abhishek Singh, Sitong Chen, Edward T. Moseley, Chih-Ying Deng, Naomi George, Charlotta Lindvall|[GitHub](https://github.com/lindvalllab/clinicalXLNet)|
|ClinicalBERT |CHIL-2020|[ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission](https://arxiv.org/pdf/1904.05342.pdf)|Kexin Huang, Jaan Altosaar, Rajesh Ranganath|[GitHub](https://github.com/kexinhuang12345/clinicalBERT)
|BioBERT      |NAACL-2019|[Publicly Available Clinical BERT Embeddings](https://arxiv.org/pdf/1904.03323.pdf)|Emily Alsentzer, John R. Murphy, Willie Boag, We-Hung Weng, Di Jin, Tristan Naumann, Matthew B.A. McDermott|[GitHub](https://github.com/EmilyAlsentzer/clinicalBERT), [Hugging Face](https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT)|

### Hybrid-type EHR Generation
| Method     | Veneue   | Reference           | Authors | Code  |
|------------|----------|---------------------|---------|-------|
|PromptEHR   |EMNLP-2022|[PromptEHR: Conditional Electronic Healthcare Records Generation with Prompt Learning](https://arxiv.org/pdf/2211.01761.pdf)| Zifeng Wang, Jimeng Sun| [GitHub](https://github.com/RyanWangZf/PromptEHR)
### Tabular EHR Synthesis
#### Difussion Models
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
|EHRDiff      |arXiv-2023|[EHRDIFF : Exploring Realistic EHR Synthesis with Diffusion Models](https://arxiv.org/pdf/2303.05656.pdf)|Hongyi Yuan, Songchi Zhou, Sheng Yu|[Github](https://github.com/sczzz3/ehrdiff)|
|MedDiff      |arXiv-2023|[MedDiff: Generating Electronic Health Records using Accelerated Denoising Diffusion Model](https://arxiv.org/pdf/2302.04355.pdf)|Huan He, Shifan Zhao, Yuanzhe Xi, Joyce Ho|

#### GAN & VAE Style
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
|HALO         |arXiv-2023|[Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model](https://arxiv.org/pdf/2304.02169.pdf)|Brandon Theodorou, Cao Xiao, Jimeng Sun|[GitHub](https://github.com/btheodorou99/HALO_Inpatient/tree/main)|
|DAAE         |AMIA-2020|[Generating sequential electronic health records using dual adversarial autoencoder](http://di.postech.ac.kr/donalee/daae/jamia_daae.pdf)|Dongha Lee, Hwanjo Yu, Xiaoqian Jiang, Deevakar Rogith, Meghana Gudala, Mubeen Tejani, Qiuchen Zhang, Li Xiong |
|MedGAN       |MLHC-2017 |[Generating Multi-label Discrete Patient Records using Generative Adversarial Networks](http://proceedings.mlr.press/v68/choi17a/choi17a.pdf)|Edward Choi, Siddharth Biswal, Bradley Malin, Jon Duke, Walter F.Stewart, Jimeng Sun|[GitHub](https://github.com/mp2893/medgan)|

#### Others
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
|Contenxutal Autocomplete|MLHC-2020|[Fast, Structured Clinical Documentation via Contextual Autocomplete](http://proceedings.mlr.press/v126/gopinath20a/gopinath20a.pdf)|Divya Gopinath, Monica Agrawal, Luke Murray, Steven Horng, David Karger, David Sontag|[GitHub](https://github.com/clinicalml/ContextualAutocomplete_MLHC2020)|

### Text EHR Generation
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
|MedText      |NAACL-2019|[Towards Automatic Generation of Shareable Synthetic Clinical Notes Using Neural Language Models](https://arxiv.org/pdf/1905.07002.pdf)|Oren Melamud, Chaitanya Shivade|[GitHub](https://github.com/orenmel/synth-clinical-notes)

## Utility Evaluation Benchmarks
| Benchmark   |  Reference           | Note  |
|-------------|----------------------|-------|
|MedNLI       |[Lessons from Natural Language Inference in the Clinical Domain](https://arxiv.org/pdf/1808.06752.pdf)|[GitHub](https://github.com/jgc128/mednli)