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


## Resource:

| Model           |  Resource          | Character | Samples | Language | Source | Method |
|-----------------|--------------------|-----------|--------|-----------|---------|-------------|
| PDP             |[[paper](https://arxiv.org/pdf/2308.09597)], [[data](https://github.com/LC1332/Chat-Haruhi-Suzumiya)]         | 327       | 1,042,647 | EN, ZH  | TV shows | Experience Extraction, Dialogue Synthesis |
| Character-LLM   |[[paper](https://arxiv.org/pdf/2310.10158)], [[data](https://github.com/choosewhatulike/trainable-agents)] | 9         | 1,900,800 | EN      | Encyclopedia | Experience Extraction, Dialogue Synthesis |
| ChatHaruhi      |[[paper](https://arxiv.org/pdf/2308.09597)], [[data](https://github.com/LC1332/Chat-Haruhi-Suzumiya)]   | 32        | 54,726  | EN, ZH   | Books, Games, Movies | Experience Extraction, Dialogue Synthesis |
| RoleLLM         |[[paper](https://arxiv.org/pdf/2310.00746)], [[data](https://github.com/InteractiveNLP-Team/RoleLLM-public)]            | 100       | 140,726 | EN, ZH   | Scripts | Experience Extraction, Dialogue Synthesis |
| HPD             |[[paper](https://aclanthology.org/2023.findings-emnlp.570.pdf)], [[data](https://nuochenpku.github.io/HPD.github.io/)] | -         | 1,191*  | EN, ZH   | Books   | Dialogue Synthesis, Human Annotation |
| CharacterGLM    |[[paper](https://arxiv.org/pdf/2311.16832)], [[data](https://github.com/thu-coai/CharacterGLM-6B)] | 250       | 1034*   | ZH       | Books, Scripts | Experience Extraction, Dialogue Synthesis, Human Annotation |
| PIPPA           |[[[paper](https://arxiv.org/pdf/2308.05884)],[[data](https://huggingface.co/datasets/PygmalionAI/PIPPA)]| 1,254     | 25,940* | EN       | Character.ai-Users | Dialogue Synthesis |
| RoleEval        |[[paper](https://arxiv.org/pdf/2312.16132)], [[data](https://github.com/Magnetic2014/RoleEval/tree/main)]| 300       | 6,000   | EN, ZH   | Encyclopedia | Dialogue Synthesis |
| CharacterEval   |[[paper](https://arxiv.org/pdf/2401.01275)], [[data](https://github.com/morecry/CharacterEval)]| 77        | 11,376  | ZH       | Books, Scripts | Experience Extraction, Human Annotation |
| CroSS-MR        |[[paper](https://arxiv.org/pdf/2404.12726)], [[data](https://github.com/Joanna0123/character_profiling/tree/main)] | 126   | 445      | EN | Literature-Analysis       | Experience Extraction      |
| DITTO        |[[paper](https://arxiv.org/pdf/2401.12474)], [[data](https://github.com/OFA-Sys/Ditto)]| 4,002      | 36,662  | EN, ZH | Encyclopedia              | Experience Extraction, Dialogue Synthesis |
| RoleInteract |[[paper](https://arxiv.org/pdf/2403.13679v3)], [[data](https://github.com/X-PLUG/SocialBench)]| 500 | 30,800 | EN, ZH | Books, Movies              | Experience Extraction, Dialogue Synthesis |
| LifeChoice   |[[paper](https://arxiv.org/pdf/2404.12138)], [[data](xxxx)] | 1,401 | 1,401    | EN | Literature-Analysis       | Experience Extraction      |
| InCharacter  |[paper](https://arxiv.org/pdf/2310.17976)], [[data](https://github.com/Neph0s/InCharacter)] | 32  | 18,304  | EN, ZH | Personality-Tests         | Dialogue Synthesis         |

## Evaluation:

[1] INCHARACTER: Evaluating Personality Fidelity in Role-Playing Agents through Psychological Interviews  [[paper](https://arxiv.org/pdf/2310.17976)], [[code](https://github.com/Neph0s/InCharacter)]

[2] Rouge-L Evaluation.[paper](https://aclanthology.org/W04-1013.pdf) [applied](https://arxiv.org/pdf/2310.00746)
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

