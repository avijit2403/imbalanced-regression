# Delving into Deep Imbalanced Regression

This repository contains the implementation code for paper: <br>
__Delving into Deep Imbalanced Regression__ <br>
_arXiv preprint arXiv:xxx_ <br>
[[arXiv](https://arxiv.org/abs/xxx)] [[Paper](https://arxiv.org/pdf/xxx.pdf)]

<p align="center">
    <img src="dir.png" width="450"> <br>
<b>Deep Imbalanced Regression (DIR)</b> aims to learn from imbalanced data with continuous targets, <br> tackle potential missing data for certain regions, and generalize to the entire target range.
</p>


## Beyond Imbalanced Classification: Brief Introduction for DIR
Existing techniques for learning from imbalanced data focus on targets with __categorical__ indices, i.e., the targets are different classes. However, many real-world tasks involve __continuous__ and even infinite target values. We systematically investigate _Deep Imbalanced Regression (DIR)_, which aims to learn continuous targets from natural imbalanced data, deal with potential missing data for certain target values, and generalize to the entire target range.

We curate and benchmark large-scale DIR datasets for common real-world tasks in _computer vision_, _natural language processing_, and _healthcare_ domains, ranging from single-value prediction such as age or health condition score, to dense-value prediction such as depth.


## Updates
- __[02/18/2021]__ [ArXiv version](https://arxiv.org/abs/xxx) posted. The code is currently under cleaning. Please stay tuned for updates.


## Citation
```bib
@article{yang2021delving,
  title={Delving into Deep Imbalanced Regression},
  author={Yang, Yuzhe and Zha, Kaiwen and Chen, Ying-Cong and Wang, Hao and Katabi, Dina},
  journal={arXiv preprint arXiv:xxx},
  year={2021}
}
```
