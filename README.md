# FEEINnet

This repository contains the tensorflow implementation of our research paper:

**FEEINnet: Feature-Enhanced Edge-INverse attention network for skin lesion segmentation**

## 📄 Paper Abstract
In skin cancer, particularly melanoma, is one of the most aggressive and deadly forms of cancer with
its incidence rising globally. Early detection is crucial for improving survival rates, but the 
traditional dermatoscopy method is a highly time-consuming and subjective process. To resolve this 
issue, we propose a novel Feature-Enhanced Edge-INverse attention network (FEEINnet) model that helps 
to segment the skin lesion region more accurately. FEEINnet consists of three sub-networks: Feature
Enhanced Mechanism (FEM) learns and extracts the fine-grained enhanced features from informative
channels, the Edge Attention Mechanism (EAM) helps to precisely identify the edges of the lesion
region and the INverse Attention Mechanism (INAM) generates inverse attention maps which emphasize
the less confident or ambiguous regions thereby increasing the segmentation accuracy iteratively.
These three sub-networks collectively helps to improve feature extraction, enhance boundary detection,
and refine segmentation maps, even in challenging scenarios with varying lesion size, shape
and pigment. FEEINnet consistently outperforms existing models, achieving an F1-score of 95.55%,
95.53%, and 94.52%; Intersection over Union (IoU) of 92.76%, 92.43%, and 91.34%; and Structural
Similarity Index Measure (SSIM) of 94.63%, 93.51%, and 91.85% on the HAM10000, PH2, and
ISIC2018 datasets, respectively. The obtained results demonstrate that the proposed model has a
higher ability to segment complex skin lesions more accurately.

## 📦 Datasets
The following link contains the files for all the 3 datasets used in the paper: Ham10000, ISIC2018 and PH2.
abc.123

