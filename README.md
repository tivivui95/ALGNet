# Official implementation of ALGNet: Attention Light Graph Memory Network for Medical Recommendation System

This is the implementation for paper ALGNet: Attention Light Graph Memory Network for Medical Recommendation System, SOICT 2023.

<b>Author:</b> Minh-Van Nguyen, Duy-Thinh Nguyen, Quoc-Huy Trinh, Bac Le

## Installation

To install all necessary packages, install via ```requirements.txt``` file with this command:

```
pip install -r requirements.txt
```

After running this script, all packages will be installed.

## Training

For training, you have to change dir to ```./src/```. Then you can run file ```ALGNet.py``` for the training via this command:

```
python ALGNet.py
```

## Acknowledgement
Thanks [GAMENET](https://github.com/sjy1203/GAMENet) for the initial pipeline.

## Citation 
```
@inproceedings{10.1145/3628797.3628983,
author = {Nguyen, Minh-Van and Nguyen, Duy-Thinh and Trinh, Quoc-Huy and Le, Bac},
title = {ALGNet: Attention Light Graph Memory Network for Medical Recommendation System},
year = {2023},
isbn = {9798400708916},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3628797.3628983},
doi = {10.1145/3628797.3628983},
abstract = {Medication recommendation is a vital task for improving patient care and reducing adverse events. However, existing methods often fail to capture the complex and dynamic relationships among patient medical records, drug efficacy and safety, and drug-drug interactions (DDI). In this paper, we propose ALGNet, a novel model that leverages light graph convolutional networks (LGCN) and augmentation memory networks (AMN) to enhance medication recommendation. LGCN can efficiently encode the patient records and the DDI graph into low-dimensional embeddings, while AMN can augment the patient representation with external knowledge from a memory module. We evaluate our model on the MIMIC-III dataset and show that it outperforms several baselines in terms of recommendation accuracy and DDI avoidance. We also conduct an ablation study to analyze the effects of different components of our model. Our results demonstrate that ALGNet can achieve superior performance with less computation and more interpretability.},
booktitle = {Proceedings of the 12th International Symposium on Information and Communication Technology},
pages = {570–577},
numpages = {8},
keywords = {Electronic health record system, Memory Network., Light Graph Convolutional Network, Medical Recommendation},
location = {<conf-loc>, <city>Ho Chi Minh</city>, <country>Vietnam</country>, </conf-loc>},
series = {SOICT '23}
}
```
