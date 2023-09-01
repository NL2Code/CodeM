# CodeM: Can Programming Languages Boost Each Other via Instruction Tuning?

[paper](https://arxiv.org/pdf/2308.16824.pdf)

## Abstract
When human programmers have mastered a programming language, it would be easier when they learn a new programming language. In this report, we focus on exploring whether programming languages can boost each other during the instruction fine-tuning phase of code large language models. We conduct extensive experiments of 8 popular programming languages (Python, JavaScript, TypeScript, C, C++, Java, Go, HTML) on StarCoder. Results demonstrate that programming languages can significantly improve each other. For example, CodeM-Python 15B trained on Python is able to increase Java by an absolute 17.95% pass@1 on HumanEval-X. More surprisingly, we found that CodeM-HTML 7B trained on the HTML corpus can improve Java by an absolute 15.24% pass@1. Our training data is released at [this https URL](https://huggingface.co/datasets/Daoguang/CodeM-Multilinugal-Data) or [this folder](https://github.com/NL2Code/CodeM/tree/main/data).

## Reference

```
@misc{zan2023codem,
      title={Can Programming Languages Boost Each Other via Instruction Tuning?}, 
      author={Daoguang Zan and Ailun Yu and Bo Shen and Jiaxin Zhang and Taihong Chen and Bing Geng and Bei Chen and Jichuan Ji and Yafen Yao and Yongji Wang and Qianxiang Wang},
      year={2023},
      eprint={2308.16824},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
