# CodeM: Less Data Yields More Versatility via Ability Matrix

[paper](https://openreview.net/pdf?id=FhpWlIs7V3)

## Abstract
In the era of code large language models (code LLMs), data engineering plays a pivotal role during the instruction fine-tuning phase. To train a versatile model, previous efforts devote tremendous efforts into crafting instruction data covering all the downstream scenarios. Nonetheless, this will incur significant expenses in constructing data and training model. Therefore, this paper introduces CodeM, a novel data construction strategy, which can efficiently train a versatile model using less data via our newly proposed ability matrix. CodeM uses ability matrix to decouple code LLMs' abilities into two dimensions, constructing a lightweight training corpus that only covers a subset of target scenarios. Extensive experiments on HumanEvalPack and MultiPL-E imply that code LLMs can combine the single-dimensional abilities to master composed abilities, validating the effectiveness of CodeM.

## Data
[download multi-langs&tasks code data](https://github.com/NL2Code/CodeM/releases/tag/CodeM-data)

## Citation
```
@inproceedings{
zan2024codem,
title={CodeM: Less Data Yields More Versatility via Ability Matrix},
author={Daoguang Zan, Ailun Yu, Wei Liu, Bo Shen, Shaoxin Lin, Yongshun Gong, Yafen Yao, Yan Liu, Bei Guan, Weihua Luo, Yongji Wang, Qianxiang Wang, Lizhen Cui},
booktitle={The 62nd Annual Meeting of the Association for Computational Linguistics},
year={2024},
url={https://openreview.net/forum?id=FhpWlIs7V3}
}
```
