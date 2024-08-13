# Role-Play-LLMs
[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/ModelEditingPapers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/Starrylay/Role-Play-LLMs?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)


This repository is dedicated to summarizing papers related to large language models 





[21] Boosting legal case retrieval by query content selection with large language models [paper](https://arxiv.org/pdf/2312.03494v1.pdf)

[22] LLMediator: GPT-4 Assisted Online Dispute Resolution [paper](https://arxiv.org/pdf/2307.16732v1.pdf)

[23] Employing Label Models on ChatGPT Answers Improves Legal Text Entailment Performance [paper](https://arxiv.org/pdf/2401.17897v1.pdf)

[24] LLaMandement: Large Language Models for Summarization of French Legislative Proposals [paper](https://arxiv.org/pdf/2401.16182v1.pdf)




## Benchmark:
[1] RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models.

Zekun Moore Wang, Zhongyuan Peng, Haoran Que, Jiaheng Liu, Wangchunshu Zhou, Yuhan Wu, Hongcheng Guo, Ruitong Gan, Zehao Ni, Man Zhang, Zhaoxiang Zhang, Wanli Ouyang, Ke Xu, Wenhu Chen, Jie Fu, Junran Peng. ACL 2024, [paper](https://arxiv.org/pdf/2310.00746), RoleBench [code](https://github.com/InteractiveNLP-Team/RoleLLM-public/tree/main?tab=readme-ov-file)


## Dataset:

| Model           |  Resource | Character | Samples | Language | Source | Method |
|-----------------|-----------|-----------|--------|-----------|---------|-------------|
| PDP             |[[paper](https://arxiv.org/pdf/2308.09597)], [[data](https://github.com/LC1332/Chat-Haruhi-Suzumiya)]         | 327       | 1,042,647 | EN, ZH  | TV shows | Experience Extraction, Dialogue Synthesis |
| Character-LLM   | 9         | 1,900,800 | EN      | Encyclopedia | Experience Extraction, Dialogue Synthesis |
| ChatHaruhi      | 32        | 54,726  | EN, ZH   | Books, Games, Movies | Experience Extraction, Dialogue Synthesis |
| RoleLLM         | 100       | 140,726 | EN, ZH   | Scripts | Experience Extraction, Dialogue Synthesis |
| HPD             | -         | 1,191*  | EN, ZH   | Books   | Dialogue Synthesis, Human Annotation |
| CharacterGLM    | 250       | 1034*   | ZH       | Books, Scripts | Experience Extraction, Dialogue Synthesis, Human Annotation |
| PIPPA           | 1,254     | 25,940* | EN       | Character.ai-Users | Dialogue Synthesis |
| RoleEval        | 300       | 6,000   | EN, ZH   | Encyclopedia | Dialogue Synthesis |
| CharacterEval   | 77        | 11,376  | ZH       | Books, Scripts | Experience Extraction, Human Annotation |
| ...             | ...       | ...     | ...      | ...     | ... |


## Evaluation:
[1] Rouge-L Evaluation.[paper](https://aclanthology.org/W04-1013.pdf) [applied](https://arxiv.org/pdf/2310.00746)
(1) Raw groundtruths of general instructions without role-playing (RAW); (2) Customized general instruction responses with role-playing from RoleBench-general (CUS); (3) Role-specific instruction responses from RoleBench-specific (SPE). 



# Acknowledgement
Please cite the following papers as the references if you use our codes or the processed datasets.

```bib
@article{xxxxx,
  title={xxxxxx},
  author={xxx},
  journal={arXiv preprint arXiv:xxx},
  year={2024}
}
```

