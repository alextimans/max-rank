## Overview

This is the public code repository for our work
[Max-Rank: Efficient Multiple Testing for Conformal Prediction](https://arxiv.org/abs/2311.10900) presented at AISTATS 2025.


#### Abstract :memo:
---

Multiple hypothesis testing (MHT) commonly arises in various scientific fields, from genomics to psychology, where testing many hypotheses simultaneously increases the risk of Type-I errors. These errors can mislead scientific inquiry, rendering MHT corrections essential. In this paper, we address MHT within the context of conformal prediction, a flexible method for predictive uncertainty quantification. Some conformal prediction settings can require simultaneous testing, and positive dependencies among tests typically exist. We propose a novel correction named 𝚖𝚊𝚡-𝚛𝚊𝚗𝚔 that leverages these dependencies, whilst ensuring that the joint Type-I error rate is efficiently controlled. Inspired by permutation-based corrections from Westfall & Young (1993), 𝚖𝚊𝚡-𝚛𝚊𝚗𝚔 exploits rank order information to improve performance, and readily integrates with any conformal procedure. We demonstrate both its theoretical and empirical advantages over the common Bonferroni correction and its compatibility with conformal prediction, highlighting the potential to enhance predictive uncertainty quantification.

---

#### Citation
If you find this repository useful, please consider citing our work:

```
@inproceedings{timans2025maxrank,
    title = {Max-Rank: Efficient Multiple Testing for Conformal Prediction}, 
    author = {Alexander Timans and Christoph-Nikolas Straehle and Kaspar Sakmann and Christian Naesseth and Eric Nalisnick},
    booktitle = {Proceedings of the 28th International Conference on Artificial Intelligence and Statistics},
    year = {2025}
}
```

#### Acknowledgements
The [Robert Bosch GmbH](https://www.bosch.com) is acknowledged for financial support.

## Repo structure
The code with details for reproducibility and runnables will be shared shortly, please wait a little longer.

#### Still open questions?

If there are any problems you encounter which have not been addressed, please feel free to create an issue or reach out! 
