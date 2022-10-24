# Awesome Proteomics on AWS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for protein analysis on AWS.

## Contents

- [1. Overview](#1-overview)
- [2. Resources by Workflow Type](#2-resources-by-workflow-type)
- [2.1. Resources for Sequence Homology Search](#21-resources-for-sequence-homology-search)
- [2.2. Resources for Sequence Property Prediction](#22-resources-for-sequence-property-prediction)
- [2.3. Resources for MSA-based Structure Prediction](#23-resources-for-msa-based-structure-prediction)
- [2.4. Resources for LLM-based Structure Prediction](#24-resources-for-llm-based-structure-prediction)
- [2.5. Resources for Experimental Analysis](#25-resources-for-experimental-analysis)
- [2.6. Resources for Molecular Dynamics Simulations](#26-resources-for-molecular-dynamics-simulations)
- [2.7. Resources for Protein Design](#27-resources-for-protein-design)
- [2.8. Other Resources](#28-other-resources)
- [3. Content Creators](#3-content-creators)
- [4. Contribute](#4-contribute)

## 1. Overview

Knowing the physical structure of proteins is an important part of both small molecule and biologics drug R&D. Machine learning algorithms like DeepMind’s AlphaFold can significantly reduce the cost and time required to generate usable protein structures. These high-profile projects have inspired increased development of AI-driven workflows for protein structure prediction, de novo protein design, and protein-ligand interaction analysis. AWS pharmaceutical and life science customers believe that these in silico tools can help reduce the cost and time required to bring new therapeutics to market.

AWS technical teams have developed solutions to common proteomics problems. These use a variety of services to best fit the needs of our customers.

---

## 2. Resources by Workflow Type

:newspaper: Blog Post  
:hammer: Architecture  
:books: Customer Story  

### 2.1. Resources for Sequence Homology Search

- 2022 :hammer: [AWS Batch Architecture for JackHMMER/HHBlits](https://github.com/aws-samples/aws-batch-arch-for-protein-folding)

---

### 2.2. Resources for Sequence Property Prediction

- 2021-06-10 :newspaper: [Exploring the UniProt protein knowledgebase with AWS Open Data and Amazon Neptune](https://aws.amazon.com/blogs/industries/exploring-the-uniprot-protein-knowledgebase-with-aws-open-data-and-amazon-neptune/)
- 2021-05-27 :newspaper: [Fine-tune and deploy the ProtBERT model for protein classification using Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/fine-tune-and-deploy-the-protbert-model-for-protein-classification-using-amazon-sagemaker/)

---

### 2.3. Resources for MSA-Based Structure Prediction

- 2022-10-04 :newspaper: [Optimize Protein Folding Costs with OpenFold on AWS Batch](https://aws.amazon.com/blogs/hpc/optimize-protein-folding-costs-with-openfold-on-aws-batch/)
- 2022-04-18 :newspaper: [Predicting protein structures at scale using AWS Batch](https://aws.amazon.com/blogs/industries/predicting-protein-structures-at-scale-using-aws-batch/)
- 2022 :hammer: [AWS Batch Architecture for AlphaFold 2.0](https://github.com/aws-samples/aws-batch-arch-for-protein-folding)
- 2022 :hammer: [AWS Batch Architecture for AlphaFold-Multimer](https://github.com/aws-samples/aws-batch-arch-for-protein-folding)
- 2022 :hammer: [AWS Batch Architecture for OpenFold](https://github.com/aws-samples/aws-batch-arch-for-protein-folding)
- 2022 :hammer: [AWS EKS Architecture For OpenFold Inference](https://github.com/aws-samples/aws-do-openfold-inference)
- 2021-11-05 :newspaper: [Run AlphaFold v2.0 on Amazon EC2](https://aws.amazon.com/blogs/machine-learning/run-alphafold-v2-0-on-amazon-ec2/)
- 2021 :hammer: [AWS Batch Architecture for RoseTTAFold](https://github.com/aws-samples/aws-rosettafold)

---

### 2.4. Resources for LLM-Based Structure Prediction

- 2022 :hammer: [AWS Batch Architecture for OmegaFold](https://github.com/aws-samples/aws-batch-arch-for-protein-folding)

---

### 2.5. Resources for Experimental Analysis

- 2022-09-21 :newspaper: [Japan’s High Energy Accelerator Research Organization, KEK, accelerates search for new vaccines with AWS](https://aws.amazon.com/blogs/publicsector/japans-high-energy-accelerator-research-organization-kek-accelerates-search-new-vaccines-aws/)
- 2022-07-12 :newspaper: [How Thermo Fisher Scientific Accelerated Cryo-EM using AWS ParallelCluster](https://aws.amazon.com/blogs/hpc/how-thermo-fisher-scientific-accelerated-cryo-em-using-aws-parallelcluster/)
- 2022-01-17 :newspaper: [CelerisTx: Drug Discovery for Incurable Diseases with ML on AWS](https://aws.amazon.com/blogs/startups/celeristx-drug-discovery-for-incurable-diseases-with-ml-on-aws/)
- 2022 :books: [ENPICOM Supports Faster Insights for Therapeutic Antibody Discovery Using AWS](https://aws.amazon.com/solutions/case-studies/ENPICOM-case-study/?did=cr_card&trk=cr_card)
- 2021-08-17 :newspaper: [Stion – a Software as a Service for Cryo-EM data processing on AWS](https://aws.amazon.com/blogs/hpc/stion-a-saas-for-cryo-em-data-processing-on-aws/)
- 2019-10-30 :newspaper: [Structural biologists learning cryo-electron microscopy can access educational resources powered by AWS](https://aws.amazon.com/blogs/publicsector/structural-biologists-learning-cryo-electron-microscopy-have-new-educational-resources-powered-by-aws/)
- 2019-10-29 :newspaper: [Building a GPU-enabled CryoEM workflow on AWS](https://aws.amazon.com/blogs/industries/building-a-gpu-enabled-cryoem-workflow-on-aws/)

---

### 2.6. Resources for Molecular Dynamics Simulations

- 2022-06-09 :newspaper: [Running cost-effective GROMACS simulations using Amazon EC2 Spot Instances with AWS ParallelCluster](https://aws.amazon.com/blogs/hpc/running-gromacs-on-spot-with-checkpointing/)
- 2022-02-16 :newspaper: [GROMACS performance on Amazon EC2 with Intel Ice Lake processors](https://aws.amazon.com/blogs/hpc/gromacs-performance-on-amazon-ec2-with-intel-ice-lake-processors/)
- 2021-11-02 :newspaper: [Running 20k simulations in 3 days to accelerate early stage drug discovery with AWS Batch](https://aws.amazon.com/blogs/hpc/running-20k-simulations-in-3-days-with-aws-batch/)
- 2021-10-14 :newspaper: [Running GROMACS on GPU instances: multi-node price-performance](https://aws.amazon.com/blogs/hpc/running-gromacs-on-gpu-instances-multi-node-price-performance/)
- 2021-10-13 :newspaper: [Running GROMACS on GPU instances: single-node price-performance](https://aws.amazon.com/blogs/hpc/running-gromacs-on-gpu-instances-single-node-price-performance/)
- 2021-10-12 :newspaper: [Running GROMACS on GPU instances](https://aws.amazon.com/blogs/hpc/running-gromacs-on-gpu-instances/)
- 2021-03-31 :newspaper: [GROMACS price-performance optimizations on AWS](https://aws.amazon.com/blogs/hpc/gromacs-price-performance-optimizations-on-aws/)
- 2020-11-25 :newspaper: [A new key to unlocking drug discovery](https://aws.amazon.com/blogs/publicsector/new-key-unlocking-drug-discovery/)
- 2020-11-02 :newspaper: [Crowdsourcing a cure for COVID-19: How the cloud and Folding@home are accelerating research and drug discovery](https://aws.amazon.com/blogs/publicsector/crowdsourcing-cure-covid-19-cloud-accelerating-research-drug-discovery/)
- 2020-08-14 :newspaper: [Folding@home infectious disease research with Spot Instances](https://aws.amazon.com/blogs/compute/foldinghome-infectious-disease-research-with-spot-instances/)

---

### 2.7. Resources for Protein Design

- 2022 :hammer: [AWS Batch Architecture for RFDesign](https://github.com/aws-samples/aws-batch-architecture-for-rfdesign)

---

### 2.8. Other Resources

- 2021-08-16 :newspaper: [Menten AI Leverages AWS, AI, and Quantum Computing to Create New and Improved Drugs](https://aws.amazon.com/blogs/startups/menten-ai-leverages-aws-ai-quantum-computing-to-create-drugs/)
- 2021 :books: [Powering Moderna’s digital biotechnology platform to develop new vaccines](https://aws.amazon.com/solutions/case-studies/moderna-machine-learning/?did=cr_card&trk=cr_card)
- 2020 :books: [Relay Therapeutics Uses AWS to Accelerate Drug Discovery](https://aws.amazon.com/solutions/case-studies/relay-therapeutics/)

## 3. Content Creators

- [Ariyawansa, Shamika](https://github.com/shamika)
- Atnoor, Deven
- Bhatkar, Swapnil
- [Bollig, Evan](https://github.com/bollig)
- [Broyde, Joshua](https://github.com/JoshB29)
- Carter, Maggie
- Cherian, Austin
- Cianfrocco, Michael
- Deshpande, Aniket
- Eng, Edward
- Enigbokan, Olajide
- Greene, Eric
- Joshi, Vaijayanti
- Kadyan, Sachin
- [Khanuja, Mani](https://github.com/mani-aiml)
- Kitzmiller, Grace
- Kniep, Christian
- [Loyal, Brian](https://github.com/brianloyal)
- Malhotra, Sudhanshu
- Pamulapati, Santhan
- Peven, Ben
- Rapp, Micah
- [Schreckengaust, Scott](https://github.com/scottschreckengaust)
- Shi, Yuan
- [Skjerven, Brian](https://github.com/skjerven)
- [Smith, Sean](https://github.com/sean-smith)
- [Srivastava, Ankur](https://github.com/awsankur)
- Trummer Christopher
- Wang, Qi
- Weber, Noah
- [White, Natalie](https://github.com/natalie-white-aws)
- Wu, Angela
- [Xu, Rafa](https://github.com/aaaaatoz)

---

## 4. Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
