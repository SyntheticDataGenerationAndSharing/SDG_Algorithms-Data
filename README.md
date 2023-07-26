# Synthetic Data Generation Algorithms and Data Sharing
This repository belongs to IEEE PES Task Force on Power System Synthetic Data Generation and Sharing. https://cmte.ieee.org/pes-pssdgs/

We encourage researchers to contribute to the community by open-sourcing their algorithms on the topic of Synthetic Data Generation.

## Organizers
Yi Hu (North Carolina State University)

Ning Lu (North Carolina State University)

## Contact
Please send your questions and comments to: hugh19flyer@gmail.com

## Citation
If you are using the shared dataset, please cite:

## Open-source Algorithms
### 1. MultiLoad-GAN
figures

Generate a group of load profiles considering spatial-temporal correlations. https://github.com/hughwln/MultiLoad-GAN_public

_Yi Hu,  Yiyan Li, Lidong Song, Han Pyo Lee, PJ Rehm, Matthew Makdad, Edmond Miller, and Ning Lu, "MultiLoad-GAN: A GAN-Based Synthetic Load Group Generation Method Considering Spatial-Temporal Correlations," submitted to IEEE Transactions on Smart Grid (2022). Available online at: https://arxiv.org/abs/2210.01167._

**Abstract**: This paper presents a deep-learning framework, Multi-load Generative Adversarial Network (MultiLoad-GAN), for generating a group of synthetic load profiles (SLPs) simultaneously. The main contribution of MultiLoad-GAN is the capture of spatial-temporal correlations among a group of loads that are served by the same distribution transformer. This enables the generation of a large amount of correlated SLPs required for microgrid and distribution system studies. The novelty and uniqueness of the MultiLoad-GAN framework are three-fold. First, to the best of our knowledge, this is the first method for generating a group of load profiles bearing realistic spatial-temporal correlations simultaneously. Second, two complementary realisticness metrics for evaluating generated load profiles are developed: computing statistics based on domain knowledge and comparing high-level features via a deep-learning classifier. Third, to tackle data scarcity, a novel iterative data augmentation mechanism is developed to generate training samples for enhancing the training of both the classifier and the MultiLoad-GAN model. Simulation results show that MultiLoad-GAN can generate more realistic load profiles than existing approaches, especially in group level characteristics.  With little finetuning, MultiLoad-GAN can be readily extended to generate a group of load or PV profiles for a feeder or a service area.

### 2. profile_infilling
GAN-based method to restore missing data and estimate baseline of CVR events. https://github.com/EricLDS/profile_infilling

_Li, Yiyan, Lidong Song, Yi Hu, Hanpyo Lee, Di Wu, P. J. Rehm, and Ning Lu. "Load Profile Inpainting for Missing Load Data Restoration and Baseline Estimation." arXiv preprint arXiv:2211.16332 (2022)._

**Abstract**: This paper introduces a Generative Adversarial Nets (GAN) based, Load Profile Inpainting Network (Load-PIN) for restoring missing load data segments and estimating the baseline for a demand response event. The inputs are time series load databefore and after the inpainting period together with explanatory variables (e.g., weather data). We propose a Generator structure consisting of a coarse network and a fine-tuning network. The coarse network provides an initial estimation of the data segment in the inpainting period. The fine-tuning network consists of selfattention blocks and gated convolution layers for adjusting the initial estimations. Loss functions are specially designed for the fine-tuning and the discriminator networks to enhance both the point-to-point accuracy and realisticness of the results. We test the Load-PIN on three real-world data sets for two applications: patching missing data and deriving baselines of conservation voltage reduction (CVR) events. We benchmark the performance of Load-PIN with five existing deep-learning methods. Our simulation results show that, compared with the state-of-the-art methods, Load-PIN can handle varying-length missing data events and achieve 15-30% accuracy improvement.

## Shared dataset


## FAQ
