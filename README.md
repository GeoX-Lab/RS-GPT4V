# RS-GPT4V: A Unified Multimodal Instruction-Following Dataset for Remote Sensing Image Understanding


Linrui Xu, Ling Zhao, Wang Guo, Qiujun Li, Kewang Long, Kaiqi Zou, Yuhan Wang, [Haifeng Li☨](https://scholar.google.com/citations?user=51p_SJAAAAAJ)



## News
We will be releasing the complete dataset, scripts, and model weights soon!


+ **\[2024/06/18\]:** Our paper now is available at [arxiv](https://arxiv.org/abs/2406.12479).

We will be releasing the complete dataset, scripts, and model weights soon!
  
---
<p align="center">
  <a href="#Abstract">Abstract</a> •
  <a href="#Experiments">Experiments</a> •
  <a href="#Installa">Installation</a> •  
  <a href="#Usages">Usages</a> •
  <a href="#Result">Result</a> •
  <a href="#Citation">Citation</a>
</p>

<div align="center">
<img src="./fig/geox.png" width="200px">
</div>

---

This is the official repository for the paper:
> **[RS-GPT4V: A Unified Multimodal Instruction-Following Dataset for Remote Sensing Image Understanding]( )**<br>


> **Abstract:** The remote sensing image (RSI) intelligence understanding model is undergoing a new profound paradigm shift which has been promoted by multi-modal large language model (MLLM), i.e. from the paradigm learning a domain model (LaDM) shifts to paradigm learning a pre-trained general foundation model followed by an adaptive domain model (LaGD). Under the new LaGD paradigm, the old datasets, such as RSI-CD, DOTA, which have led to advances in RSI intelligence understanding in the last decade, are no longer suitable for fire-new tasks. We argued that a new dataset must be carefully designed to lighten tasks in the new paradigm with the following features: (1) Generalization: training model to learn shared knowledge among tasks and to adapt to different tasks; (2) Understanding complex scenes: training model to understand the fine-grained attribute of the objects of interest, and to be able to describe the scene with natural language with detailed; (3) Reasoning: training model to be able to realize high-level visual reasoning. In this paper, we designed a high-quality, diversified, and unified multimodal instruction-following dataset for RSI understanding produced by GPT-4V and existing datasets, which we called RS-GPT4V. To achieve generalization, RS-GPT4V used a (Question, Answer) which was deduced from GPT-4V via instruction-following to unify the tasks such as captioning, and localization; To achieve an understanding of a complex scene, RS-GPT4V proposed a hierarchical instruction description with local strategy in which the fine-grained attributes of the objects and their spatial relationships are described and global strategy in which all the local information are integrated to yield detailed instruction descript; To achieve reasoning, RS-GPT4V designed multiple-turn (Question, Answer) pair to provide the reasoning ability for a model. The empirical results show that the fine-tuned MLLMs by RS-GPT4V can describe fine-grained information, and implicit knowledge in multiple complex remote sensing scenarios, and reason better than existing datasets. 
<br>
<p align="center" float="center">
    <img src="https://github.com/GeoX-Lab/RS-GPT4V/assets/36953734/815838bf-622d-4fe0-bc17-708d57b4edc4" width="99%">
    <em>Principles-Driven Pipeline for RS-GPT4V Dataset Construction.</em>
</p>

 
## Experiments



## Install


## Usages




## Result





##  Relate Works


## Experimental Details and Supplement Materials 
More details and supplement experimental results are coming. 

## Citation
If you find RS-GPT4V useful for your research and applications, please cite using this BibTeX:

```
@ARTICLE{10197260,
  author={Xu, Linrui and Guo, Wang and Li, Qiujun and Long, Kewang and Zou, Kaiqi and Wang, Yuhan and Li, Haifeng},
  title={RS-GPT4V: A Unified Multimodal Instruction-Following Dataset for Remote Sensing Image Understanding}, 
  year={2024},
  volume={},
  number={},
  pages={1-14},
  journal={arXiv}, 
  doi={https://arxiv.org/abs/2406.12479}
}
```
