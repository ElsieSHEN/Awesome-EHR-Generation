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
      - [Rule-based Methods](#rule-based-methods)
      - [Others](#others)
    - [Text EHR Generation](#text-ehr-generation)
  - [Utility Evaluation Benchmarks](#utility-evaluation-benchmarks)
  - [Tutorials](#tutorials)
## Papers
### Surveys for EHR
| Survey     | Authors        | Year |
|------------|----------------|------|
|[Mining Electronic Health Records (EHRs): A Survey](https://dl.acm.org/doi/pdf/10.1145/3127881)|Pranjul Yadav, Michael Steinbach, Vipin Kumar, Gyorgy Simon|2018|
|[Deep EHR: A Survey of Recent Advances in Deep Learning Techniques for Electronic Health Record (EHR) Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8086133)|Benjamin Shickel, Patrick James Tighe, Azra Bihorac, Parisa Rashidi|2017

### EHR Representation
| Method      | Veneue  | Reference           | Authors | Code  |
|-------------|---------|---------------------|---------|-------|
|Med-BERT     |NPJ-2021 |[Med-BERT: pretrained contextualized embeddings on largescale structured electronic health records for disease prediction](https://www.nature.com/articles/s41746-021-00455-y.pdf)|Laila Rasmy, Yang Xiang, Ziqian Xie, Cui Tao, Degui Zhi|[GitHub](https://github.com/ZhiGroup/Med-BERT)|
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
| Method      | Veneue   | Reference           | Authors | Note  |
|-------------|----------|---------------------|---------|-------|
|Survey       |DS-2021   |[GANs for Tabular Healthcare Data Generation: A Review on Utility and Privacy](https://link.springer.com/chapter/10.1007/978-3-030-88942-5_22)| João Coutinho-Almeida, Pedro Pereira Rodrigues, Ricardo João Cruz-Correia |2021|
|HALO         |arXiv-2023|[Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model](https://arxiv.org/pdf/2304.02169.pdf)|Brandon Theodorou, Cao Xiao, Jimeng Sun|[GitHub](https://github.com/btheodorou99/HALO_Inpatient/tree/main)|
|EVA          |MLHC-2021|[EVA: Generating Longitudinal Electronic Health Records Using Conditional Variational Autoencoders](https://arxiv.org/pdf/2012.10020.pdf)| Siddharth Biswal, Soumya Ghosh, Jon Duke, Bradley Malin, Walter Stewart, Cao Xiao, Jimeng Sun |
|DAAE         |AMIA-2020|[Generating sequential electronic health records using dual adversarial autoencoder](http://di.postech.ac.kr/donalee/daae/jamia_daae.pdf)|Dongha Lee, Hwanjo Yu, Xiaoqian Jiang, Deevakar Rogith, Meghana Gudala, Mubeen Tejani, Qiuchen Zhang, Li Xiong |
|MedWGAN      |AIMA-2019|[Synthesizing electronic health records using improved generative adversarial networks](https://watermark.silverchair.com/ocy142.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAsEwggK9BgkqhkiG9w0BBwagggKuMIICqgIBADCCAqMGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQM6VnmyP2kAAbdeoDwAgEQgIICdAUYcIiL0vL7HsnfNtK6-5wCCWDX5pAN035hSM9D9XqBbBPRBXSOmIA8myjhAD_viekzl-XcTN05TVmpegznrcGNXsqYhxB2P-vZsE28M5HjUzdQhTf9CKMLGCCAjYSLyfDANlhIzF0KVsDtTNsjNRgweBaX4jUQFY7g8Y-O6nU8ibzWJ0KkyeBUVM1tLNGnnvfKe6MK9M8UwpvX3ZnvkAcbuhtyp-fafH7KM_Krx827IIWbPdos45j9RJtPJyHXs2Rdb4PivX3ZbpO0cBrVYQWmTf36HtKXpPFKupj6K1zlYAxNaUKkmqs_oXDA_ZX6daO-pT2Qjx9GDLL4dMnYEcGpiGb4J-VN4SLkZrWHSx8OvknaUm0n4_JTdTXrTKVeVV2ob2rPU0rYSAcFJfAZAjO9JP0krOIx7rYVCxIUeIoQPF1Ww7-Dgdb6Li5CrcuTq14NcJVXUQBnnG9zIeyBG-lz-SZQGCcmwKh3HpdQfQppWXr1ZSG955RNyrPFDhJXvsSg7bgZLC5DSFWUi90DDHTbJgfW7HpUK6rONvWcVRCM7ADd-en_pxbjoVWZHgy_i__M2lX2hvvKkPX4Gmg2IrzUnH7t4u-C3A2BmNKr3i8c5FEmNqLHDu-HR1rqaZms31bU4ru9bapJIwaw-_JbL7cHRK1KaX0vU1J_RqIsYDoWkOwreNV0OypEOhBgUVY4eOPzoASeHJ-DlUnJerTavi3EGwkzKOskjd3R-8KIaYQn8q4tdtm9S6I4mWKFcGGRjgKf5Ka6j-Efxx4YaciRzxtulLOtyOPDwG9CWZMOItxPIpKl7FrQPF_P45w8jKvx8JgY_eU)|Mrinal Kanti Baowaly, Chia-Ching Lin, Chao-Lin Liu, Kuan-Ta Chen|[GitHub](https://github.com/baowaly/SynthEHR)|
|mtGAN        |BIBM-2018 |[Generation of Synthetic Electronic Medical Record Text](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8621223&casa_token=__-_XDklt7AAAAAA:7UL6CAfIcDC9ov9oA8oV8RdVM6NBYe7TI9MoWBw3uT1zMqYZeQN6xSNYzQwlXlgnTxbP9Xr0fRbL)|Jiaqi Guan, Runzhe Li, Sheng Yu, Xuegong Zhang|
|RGAN & RCGAN |arXiv-2017|[Real-valued (Medical) Time Series Generation with Recurrent Conditional GANs](https://arxiv.org/pdf/1706.02633.pdf)|Stephanie L. Hyland, Cristóbal Esteban, Gunnar Rätsch|
|medGAN       |MLHC-2017 |[Generating Multi-label Discrete Patient Records using Generative Adversarial Networks](http://proceedings.mlr.press/v68/choi17a/choi17a.pdf)|Edward Choi, Siddharth Biswal, Bradley Malin, Jon Duke, Walter F.Stewart, Jimeng Sun|[GitHub](https://github.com/mp2893/medgan)|

#### Rule-based Methods
| Method      | Veneue    | Reference           | Authors | Code  |
|-------------|-----------|---------------------|---------|-------|
|CoMSER       |ICHI-2016  |[Using the CareMap with Health Incidents Statistics for Generating the Realistic Synthetic Electronic Healthcare Record](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7776401&casa_token=S325KIaNQeIAAAAA:SFdeOJaK0mQ17RxeQMlSzfDDpYqo_sY7IAVszHCVM3qMwTVt7TAagiGrPMHQna_xpVS3nAPw9LFS&tag=1)| Scott McLachlan, Kudakwashe Dube, Thomas Gallagher|
|             |BMC-2010   |[Data-driven approach for creating synthetic electronic medical records](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-10-59?report=reader)|Anna L Buczak, Steben Babin, Linda Moniz|
|EMERGE       |JHUAPL-2008|[A Method for Generation and Distribution of Synthetic Medical Record Data for Evaluation of Disease-Monitoring Systems](https://secwww.jhuapl.edu/techdigest/Content/techdigest/pdf/V27-N04/27-04-LombardoMethod.pdf)|Joseph S. Lombardo, Linda J. Moniz||

#### Others
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
||IEEE BD-2021|[A practical and universal framework for generating publicly available medical notes of authentic quality via the power of crowds](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9671418)| Rina Kagawa, Yukino Baba, Hideo Tsurushima|
|Contenxutal Autocomplete|MLHC-2020|[Fast, Structured Clinical Documentation via Contextual Autocomplete](http://proceedings.mlr.press/v126/gopinath20a/gopinath20a.pdf)|Divya Gopinath, Monica Agrawal, Luke Murray, Steven Horng, David Karger, David Sontag|[GitHub](https://github.com/clinicalml/ContextualAutocomplete_MLHC2020)|

### Text EHR Generation
| Method      | Veneue   | Reference           | Authors | Code  |
|-------------|----------|---------------------|---------|-------|
|MedText      |NAACL-2019|[Towards Automatic Generation of Shareable Synthetic Clinical Notes Using Neural Language Models](https://arxiv.org/pdf/1905.07002.pdf)|Oren Melamud, Chaitanya Shivade|[GitHub](https://github.com/orenmel/synth-clinical-notes)
||arXiv-2018|[Learning to Write Notes in Electronic Health Records](https://arxiv.org/pdf/1808.02622.pdf)|Peter J. Liu

## Utility Evaluation Benchmarks
| Benchmark   |  Reference           | Note  |
|-------------|----------------------|-------|
|MedNLI       |[Lessons from Natural Language Inference in the Clinical Domain](https://arxiv.org/pdf/1808.06752.pdf)|[GitHub](https://github.com/jgc128/mednli)

## Tutorials
- [Predictive Modeling on Electronic Health Records(EHR) using Pytorch](https://github.com/ZhiGroup/pytorch_ehr#predictive-modeling-on-electronic-health-recordsehr-using-pytorch)