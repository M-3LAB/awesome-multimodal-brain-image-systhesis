# Awesome Multi-Modal Brain Image Systhesis

We provide a list of awesome papers in medical multimodel brain image systhesis.

If you have questions, contact me! [linkingring@163.com](https://scholar.google.com/citations?hl=en&user=qI80ipUAAAAJ&view_op=list_works&alert_preview_top_rm=2&gmla=AJsN-F6lNbeBtlxu4BVhiy0be17RJo_nkYXuWkZulyQsJmF2cEWVpaFGX6MGh8F_Q5sxtYMeoCdtkGlDHwzhQ62A8AnXiPpy9zGj16BTDIoTm0Vunuz4PKw 'jinbao-wang')

# Overview

+ [Review](#review)
+ [MRI ->  MRI](#mri-mri)
+ [MRI -> CT](#mri-ct)
+ [MRI -> PET](#mri-pet)
+ [CT -> PET](#ct-pet)
+ [US -> MRI](#us-mri)
+ [PET -> PET](#pet-pet)
+ [Supplementary work](#supplementary-work)

# <span id='review'> Review </span>

+ Deep learning of brain magnetic resonance images: A brief review [[Methods, 2021]](https://www.sciencedirect.com/science/article/pii/S1046202320302024)
+ Generative adversarial network in medical imaging: A review [[MedIA, 2019]](https://www.sciencedirect.com/science/article/pii/S1361841518308430)


# <span id='mri-mri'> MRI -> MRI </span>
> Supervised

[comment]: <> (Chen2021ABCnetAB)
+ ABCnet: Adversarial bias correction network for infant brain MR images[[MedIA, 2021]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8316417/) 

[comment]: <> (Bne2021ContrastEnhancedBM)
+ Contrast-Enhanced Brain MRI Synthesis With Deep Learning: Key Input Modalities and Asymptotic Performance[[ISBI, 2021]](https://hal.archives-ouvertes.fr/hal-03128023/file/ISBI_2021__VCE.pdf)

[comment]: <> (Zhou2020HiNetHN)
+ Hi-Net: Hybrid-Fusion Network for Multi-Modal MR Image Synthesis[[TMI, 2020]](http://arxiv.org/pdf/2002.05000)

[comment]: <> (Liu2021AUC)
+ A Unified Conditional Disentanglement Framework For Multimodal Brain Mr Image Translation[[ISBI, 2021]](https://europepmc.org/articles/pmc8460116?pdf=render)

[comment]: <> (Yurt2021mustGANMG)
+ mustGAN: Multi-Stream Generative Adversarial Networks for MR Image Synthesis[[MedIA, 2021]](http://repository.bilkent.edu.tr/bitstream/11693/77499/1/mustGAN_multi-stream_Generative_Adversarial_Networks_for_MR_Image_Synthesis.pdf)

[comment]: <> (Zuo2021DMCFusionDM)
+ DMC-Fusion: Deep Multi-Cascade Fusion With Classifier-Based Feature Synthesis for Medical Multi-Modal Images[[JBHI,2021]](https://ieeexplore.ieee.org/document/9442289)

[comment]: <> (Huang2020MCMTGANMC)
+ MCMT-GAN: Multi-Task Coherent Modality Transferable GAN for 3D Brain Image Synthesis[[TIP, 2020]](https://ieeexplore.ieee.org/document/9152126)

[comment]: <> (Sharma2020MissingMP)
+ Missing MRI Pulse Sequence Synthesis Using Multi-Modal Generative Adversarial Network[[TMI, 2020]](http://arxiv.org/pdf/1904.12200)

[comment]: <> (Xin2020MultiModalityGA)
+ Multi-Modality Generative Adversarial Networks with Tumor Consistency Loss for Brain MR Image Synthesis[[ISBI, 2020]](http://arxiv.org/pdf/2005.00925)

[comment]: <> (Yu2020SampleAdaptiveGL)
+ Sample-Adaptive GANs: Linking Global and Local Mappings for Cross-Modality MR Image Synthesis[[TMI, 2020]](https://ieeexplore.ieee.org/document/8970559)

[comment]: <> (uang2019CoCaGANCC)
+ CoCa-GAN: Common-Feature-Learning-Based Context-Aware Generative Adversarial Network for Glioma Grading[[MICCAI, 2019]](https://link.springer.com/chapter/10.1007/978-3-030-32248-9_18)

[comment]: <> (Dar2019ImageSI)
+ Image Synthesis in Multi-Contrast MRI With Conditional Generative Adversarial Networks[[TMI, 2019]](http://repository.bilkent.edu.tr/bitstream/11693/53059/1/Image_Synthesis_in_Multi-Contrast_MRI_with_Conditional_Generative_Adversarial_Networks.pdf)

[comment]: <> (Kwon2019GenerationO3)
+ Generation of 3D Brain MRI Using Auto-Encoding Generative Adversarial Networks[[MICCAI, 2019]](https://arxiv.org/pdf/1908.02498.pdf)

[comment]: <> (Lee2019CollaGANCG)
+ CollaGAN: Collaborative GAN for Missing Image Data Imputation[[CVPR, 2019]](http://arxiv.org/pdf/1901.09764)

[comment]: <> (Li2019DiamondGANUM)
+ DiamondGAN: Unified Multi-Modal Generative Adversarial Networks for MRI Sequences Synthesis[[MICCAI, 2019]](https://arxiv.org/pdf/1904.12894.pdf)

[comment]: <> (Chartsias2018MultimodalMS)
+ Multimodal MR Synthesis via Modality-Invariant Latent Representation[[TMI, 2018]](https://europepmc.org/articles/pmc5904017?pdf=render)

[comment]: <> (Yu20183DCB)
+ 3D cGAN based cross-modality MR image synthesis for brain tumor segmentation[[ISBI, 2018]](https://ieeexplore.ieee.org/document/8363653)

[comment]: <> (Huang2017DOTEDC) 
+ DOTE: Dual cOnvolutional filTer lEarning for Super-Resolution and Cross-Modality Synthesis in MRI  [[MICCAI,2017]](https://arxiv.org/pdf/1706.04954.pdf)

[comment]: <> (Jog2017RandomFR)
+ Random forest regression for magnetic resonance image synthesis[[[MedIA, 2017]](http://manuscript.elsevier.com/S1361841516301578/pdf/S1361841516301578.pdf)

[comment]: <> (Joyce2017RobustMM)
+ Robust Multi-modal MR Image Synthesis[[MICCAI, 2017]](https://www.pure.ed.ac.uk/ws/files/44085420/MICCAI_2017_final.pdf)


> Weakly-supervised

[comment]: <> (Shen2021MultiDomainIC)
+ Multi-Domain Image Completion for Random Missing Input Data[[TMI, 2021]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8136445)

[comment]: <> (Huang2019SimultaneousSA) 
+ Simultaneous Super-Resolution and Cross-Modality Synthesis in Magnetic Resonance Imaging[[ACVPR, 2019]](https://link.springer.com/chapter/10.1007/978-3-030-13969-8_21)

[comment]: <> (Huang2018CrossModalityIS)
+ Cross-Modality Image Synthesis via Weakly Coupled and Geometry Co-Regularized Joint Dictionary Learning[[TMI, 2018]](http://eprints.whiterose.ac.uk/128920/1/WAG-Huang-final.pdf)

> Unsupervised

[comment]: <> (He2021AutoencoderBS) 
+ Autoencoder based self-supervised test-time adaptation for medical image analysis[[MedIA, 2021]](https://www.sciencedirect.com/science/article/am/pii/S1361841521001821)

[comment]: <> (Yang2021AUH)
+ A Unified Hyper-GAN Model for Unpaired Multi-contrast MR Image Translation[[MICCAI, 2021]](https://arxiv.org/pdf/2107.11945.pdf)

[comment]: <> (Guo2021AnatomicAM)
+ Anatomic and Molecular MR Image Synthesis Using Confidence Guided CNNs[[TMI, 2021]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8543492)

[comment]: <> (Tomar2021SelfAttentiveSA)
+ Self-Attentive Spatial Adaptive Normalization for Cross-Modality Domain Adaptation[[TMI, 2021]](http://arxiv.org/pdf/2103.03781f)

[comment]: <> (yang2020mri)
+ MRI cross-modality image-to-image translation[[Nature, Scientific Reports, 2021]](https://www.nature.com/articles/s41598-020-60520-6.pdf)

[comment]: <> (Huang2020SuperResolutionAI) 
+ Super-Resolution and Inpainting with Degraded and Upgraded Generative Adversarial Networks[[IJCAI, 2020]](https://www.ijcai.org/proceedings/2020/0090.pdf)

[comment]: <> (Sun2020AnAL)
+ An Adversarial Learning Approach to Medical Image Synthesis for Lesion Detection[[JBHI, 2020]](http://arxiv.org/pdf/1810.10850)

[comment]: <> (qu2020multimodal)
+ Multimodal brain MRI translation focused on lesions[[ICMLC, 2020]](https://dl.acm.org/doi/10.1145/3383972.3384024)

[comment]: <> (yang2018mri)
+ Mri image-to-image translation for cross-modality image registration and segmentation[[arXiv, 2018]](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/2018MRI-Image-to-Image-Translation-for-Cross-Modality-Image-Registration-and-Segmentation.pdf)

[comment]: <> (bian2022dda)
+ DDA-Net: Unsupervised cross-modality medical image segmentation via dual domain adaptation[[CMPB, 2013]](https://www.sciencedirect.com/science/article/pii/S0169260721006052)

# 2. MRI - CT
# <span id='mri-ct'> MRI -> CT </span>

> Supervised

[comment]: <> (Zuo2021DMCFusionDM)
+ DMC-Fusion: Deep Multi-Cascade Fusion With Classifier-Based Feature Synthesis for Medical Multi-Modal Images[[JBHI, 2021]](https://ieeexplore.ieee.org/document/9442289)

[comment]: <> (huynh2015estimating)
+ Estimating CT image from MRI data using structured random forest and auto-context model[[TMI, 2015]](https://europepmc.org/articles/pmc4703527?pdf=render)

> Weakly-supervised

[comment]: <> (Hemsley2020DeepGM)
+ Deep Generative Model for Synthetic-CT Generation with Uncertainty Predictions[[MICCAI, 2020]](https://link.springer.com/chapter/10.1007/978-3-030-59710-8_81)

> Unsupervised

[comment]: <> (Klser2021ImitationLF)
+ Imitation learning for improved 3D PET/MR attenuation correction[[MedIA, 2022]](https://doi.org/10.1016/j.media.2021.102079)

[comment]: <> (Yang2020UnsupervisedMS)
+ Unsupervised MR-to-CT Synthesis Using Structure-Constrained CycleGAN[[TMI, 2020]](http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=1401787&name=DLFE-134301.pdf)

[comment]: <> (Huo2019SynSegNetSS)
+ SynSeg-Net: Synthetic Segmentation Without Target Modality Ground Truth[[TMI, 2019]](https://doi.org/10.1109/tmi.2018.2876633)

[comment]: <> (Zeng2019HybridGA)
+ Hybrid Generative Adversarial Networks for Deep MR to CT Synthesis Using Unpaired Data[[MICCAI, 2019]](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_83)

[comment]: <> (Nie2017MedicalIS)
+ Medical Image Synthesis with Context-Aware Generative Adversarial Networks[[MICCAI, 2017]](https://europepmc.org/articles/pmc6044459?pdf=render)


# <span id='mri-pet'> MRI -> PET </span>
> Supervised

[comment]: <> (Hu2022BidirectionalMG)
+ Bidirectional Mapping Generative Adversarial Networks for Brain MR to PET Synthesis[[TMI, 2022]](http://arxiv.org/pdf/2008.03483)

[comment]: <> (Liu2022AssessingCP)
+ Assessing clinical progression from subjective cognitive decline to mild cognitive impairment with incomplete multi-modal neuroimages[[MedIA, 2022]](https://mingxia.web.unc.edu/wp-content/uploads/sites/12411/2021/10/SCD_MIA2021.pdf)

[comment]: <> (zhang2022bpgan)
+ BPGAN: Brain PET synthesis from MRI using generative adversarial network for multi-modal Alzheimer’s disease diagnosis[[CMPB, 2022]](https://www.sciencedirect.com/science/article/pii/S016926072200061X)

[comment]: <> (pan2021disease)
+ Disease-image-specific Learning for Diagnosis-oriented Neuroimage Synthesis with Incomplete Multi-Modality Data.[[TPAMI, 2021]](https://mingxia.web.unc.edu/wp-content/uploads/sites/12411/2021/07/FGAN_TPAMI2021.pdf)

[comment]: <> (Zuo2021DMCFusionDM)
+ DMC-Fusion: Deep Multi-Cascade Fusion With Classifier-Based Feature Synthesis for Medical Multi-Modal Images[[JBHI, 2021]](https://ieeexplore.ieee.org/document/9442289)

[comment]: <> (Hu2020BrainMT)
+ Brain MR to PET Synthesis via Bidirectional Generative Adversarial Network[[MICCAI, 2020 ]](https://link.springer.com/chapter/10.1007/978-3-030-59713-9_67)

[comment]: <> (Shin2020GANDALFGA)
+ GANDALF: Generative Adversarial Networks with Discriminator-Adaptive Loss Fine-tuning for Alzheimer's Disease Diagnosis from MRI[[MICCAI, 2020]](https://arxiv.org/pdf/2008.04396.pdf)

[comment]: <> (Pan2019DiseaseImageSG)
+ Disease-Image Specific Generative Adversarial Network for Brain Disease Diagnosis with Incomplete Multi-modal Neuroimages[[MICCAI, 2019]](http://mingxia.web.unc.edu/files/2019/10/Pan2019_Chapter_Disease-ImageSpecificGenerativ.pdf)

[comment]: <> (Wang2018LocalityAM)
+ Locality Adaptive Multi-modality GANs for High-Quality PET Image Synthesis[[MICCAI, 2018]](https://europepmc.org/articles/pmc6494468?pdf=render)

[comment]: <> (Pan2018SynthesizingMP)
+ Synthesizing Missing PET from MRI with Cycle-consistent Generative Adversarial Networks for Alzheimer's Disease Diagnosis[[MICCAI, 2018]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8336606)

[comment]: <> (Wei2018LearningMC)
+ Learning Myelin Content in Multiple Sclerosis from Multimodal MRI through Adversarial Training[[MICCAI, 2018]](https://arxiv.org/pdf/1804.08039.pdf)

> Unsupervised

[comment]: <> (kao2021demystifying)
+ Demystifying T1-MRI to FDG$^{18}$ -PET Image Translation via Representational Similarity[[MICCAI, 2021]](https://people.cs.nctu.edu.tw/~walon/publications/kao2021miccai.pdf)



# <span id='ct-pet'> CT -> PET </span>
>  Supervised

[comment]: <> (Klser2021ImitationLF)
+ Imitation learning for improved 3D PET/MR attenuation correction[[MedIA, 2021]](https://doi.org/10.1016/j.media.2021.102079)


# <span id='us-mri'> US -> MRI </span>
>  Unsupervised

[comment]: <> (Jiao2020SelfSupervisedUT)
+ Self-Supervised Ultrasound to MRI Fetal Brain Image Synthesis[[TMI, 2020]](https://ora.ox.ac.uk/objects/uuid:8ce5a71a-4246-4d4f-a635-e2b70552c015/download_file?safe_filename=Jiao_et_al_2020_self_supervised_ultrasound.pdf&file_format=pdf&type_of_work=Journal+article)


# <span id='pet-pet'> PET -> PET </span>
>  Supervised

[comment]: <> (Zhou2021SynthesizingMP)
+ Synthesizing Multi-Tracer PET Images for Alzheimer's Disease Patients using a 3D Unified Anatomy-aware Cyclic Adversarial Network[[MICCAI, 2021]](https://arxiv.org/pdf/2107.05491.pdf)

[comment]: <> (Wang20193DAL)
+ 3D Auto-Context-Based Locality Adaptive Multi-Modality GANs for PET Synthesis[[TMI, 2019]](https://europepmc.org/articles/pmc6541547?pdf=render)


# <span id='supplementary-work'> Supplementary work </span>

+ Deep Generative Models in the Real-World: An Open Challenge from Medical Imaging [[arXiv, 2018]](https://arxiv.org/abs/1806.05452)

+ Learning to synthesise the ageing brain without longitudinal data [[MedIA, 2021]](https://www.pure.ed.ac.uk/ws/files/219334907/Tian_MeDIA_Brain_Ageing_2021_accepted.pdf)

+ SA-GAN: Structure-Aware GAN for Organ-Preserving Synthetic CT Generation [[MICCAI, 2021]](https://arxiv.org/pdf/2105.07044.pdf)

+ TarGAN: Target-Aware Generative Adversarial Networks for Multi-modality Medical Image Translation [[MICCAI, 2021]](https://arxiv.org/pdf/2105.08993.pdf)

+ Spatial-Intensity Transform GANs for High Fidelity Medical Image-to-Image Translation [[MICCAI, 2020]](https://europepmc.org/articles/pmc7888153?pdf=render)

+ Degenerative Adversarial NeuroImage Nets: Generating Images that Mimic Disease Progression [[MICCAI, 2019]](https://arxiv.org/pdf/1907.02787.pdf)

+ Generative Adversarial Network for Segmentation of Motion Affected Neonatal Brain MRI [[MICCAI, 2019]](https://arxiv.org/pdf/1906.04704.pdf)


+ Anatomy-Constrained Contrastive Learning for Synthetic Segmentation without Ground-truth [[MICCAI, 2021]](https://arxiv.org/pdf/2107.05482.pdf)

