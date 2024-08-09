# Synthetic Data of LLMs, by LLMs, for LLMs

<div align="center">

[![LICENSE](https://img.shields.io/github/license/wasiahmad/Awesome-LLM-Synthetic-Data-Generation)](https://github.com/wasiahmad/Awesome-LLM-Synthetic-Data-Generation/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/wasiahmad/Awesome-LLM-Synthetic-Data-Generation?color=blue)](https://github.com/wasiahmad/Awesome-LLM-Synthetic-Data-Generation/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/wasiahmad/Awesome-LLM-Synthetic-Data-Generation/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/wasiahmad/Awesome-LLM-Synthetic-Data-Generation)](https://github.com/wasiahmad/Awesome-LLM-Synthetic-Data-Generation)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

This repo includes papers, tools, and blogs about Synthetic Data of LLMs, by LLMs, for LLMs.

Thanks for all the great contributors on GitHub!🔥⚡🔥

## Contents

* [1. Surveys](#11-Surveys)
* [2. Techniques/Methods](#2-Techniques-Methods)
  * [2.1 Instruction Generation with High Quality/Complexity](#21-Instruction-Generation-with-High-Quality-Complexity)
* [3. Application Areas](#3-Application-Areas)
  * [3.1 Mathematical Reasoning](#31-Mathematical-Reasoning)
  * [3.2 Code Generation](#32-Code-Generation)
  * [3.3 Text-to-SQL](#33-Text-to-SQL)
  * [3.4 Preference Optimization](#34-Preference-Optimization)
  * [3.5 Reward Modeling](#35-Reward-Modeling)
* [4. Datasets](#4-Datasets)
* [5. Tools](#5-Tools)
* [6. Blogs](#6-Blogs)

### 1. Surveys

- [**Best Practices and Lessons Learned on Synthetic Data for Language Models.**](https://arxiv.org/abs/2404.07503) *Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou, Andrew M. Dai.* Arxiv 2024.
- [**On LLMs-Driven Synthetic Data Generation, Curation, and Evaluation: A Survey.**](https://arxiv.org/abs/2406.15126) *Lin Long, Rui Wang, Ruixuan Xiao, Junbo Zhao, Xiao Ding, Gang Chen, Haobo Wang.* Arxiv 2024.
- [**Generative AI for Synthetic Data Generation: Methods, Challenges and the Future.**](https://arxiv.org/abs/2403.04190) *Xu Guo, Yiqiang Chen.* Arxiv 2024.
- [**Comprehensive Exploration of Synthetic Data Generation: A Survey.**](https://arxiv.org/abs/2401.02524) *André Bauer, Simon Trapp, Michael Stenger, Robert Leppich, Samuel Kounev, Mark Leznik, Kyle Chard, Ian Foster.* Arxiv 2024.


## 2. Techniques/Methods

- [**Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models.**](https://arxiv.org/abs/2401.01335) *Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu.* ICML 2024.
- [**Synthetic Data (Almost) from Scratch: Generalized Instruction Tuning for Language Models.**](https://arxiv.org/abs/2402.13064) *Haoran Li, Qingxiu Dong, Zhengyang Tang, Chaojun Wang, Xingxing Zhang, Haoyang Huang, Shaohan Huang, Xiaolong Huang, Zeqiang Huang, Dongdong Zhang, Yuxian Gu, Xin Cheng, Xun Wang, Si-Qing Chen, Li Dong, Wei Lu, Zhifang Sui, Benyou Wang, Wai Lam, Furu Wei.* Arxiv 2024.
- [**Self-instruct: Aligning language models with self-generated instructions.**](https://arxiv.org/abs/2212.10560) *Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi, Hannaneh Hajishirzi.* ACL 2023.
- [**Automatic Instruction Evolving for Large Language Models.**](https://arxiv.org/abs/2406.00770) *Weihao Zeng, Can Xu, Yingxiu Zhao, Jian-Guang Lou, Weizhu Chen.* Arxiv 2024.

### 2.1. Instruction Generation with High Quality/Complexity

- [**CodecLM: Aligning Language Models with Tailored Synthetic Data.**](https://arxiv.org/abs/2404.05875) *Zifeng Wang, Chun-Liang Li, Vincent Perot, Long T. Le, Jin Miao, Zizhao Zhang, Chen-Yu Lee, Tomas Pfister.* Findings of NAACL 2024.
- [**WizardLM: Empowering Large Language Models to Follow Complex Instructions.**](https://arxiv.org/abs/2304.12244) *Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jiang.* Arxiv 2023. 

## 3. Application Areas

### 3.1. Mathematical Reasoning
- [**MuggleMath: Assessing the Impact of Query and Response Augmentation on Math Reasoning.**](https://arxiv.org/abs/2310.05506v3) *Chengpeng Li, Zheng Yuan, Hongyi Yuan, Guanting Dong, Keming Lu, Jiancan Wu, Chuanqi Tan, Xiang Wang, Chang Zhou.* ACL 2024.
- [**MathGenie: Generating Synthetic Data with Question Back-translation for Enhancing Mathematical Reasoning of LLMs.**](https://arxiv.org/abs/2402.16352) *Zimu Lu, Aojun Zhou, Houxing Ren, Ke Wang, Weikang Shi, Junting Pan, Mingjie Zhan, Hongsheng Li.* ACL 2024.
- [**MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models.**](https://arxiv.org/abs/2309.12284) *Longhui Yu, Weisen Jiang, Han Shi, Jincheng Yu, Zhengying Liu, Yu Zhang, James T. Kwok, Zhenguo Li, Adrian Weller, Weiyang Liu.* ICLR 2024.
- [**Augmenting Math Word Problems via Iterative Question Composing.**](https://arxiv.org/abs/2401.09003) *Haoxiong Liu, Yifan Zhang, Yifan Luo, Andrew Chi-Chih Yao.* DPFM@ICLR 2024.

### 3.2. Code Generation
- [**Genetic Instruct: Scaling up Synthetic Generation of Coding Instructions for Large Language Models.**](https://arxiv.org/abs/2407.21077) *Somshubra Majumdar, Vahid Noroozi, Sean Narenthiran, Aleksander Ficek, Jagadeesh Balam, Boris Ginsburg.* Arxiv 2024.

### 3.3. Text-to-SQL
- [**Synthesizing Text-to-SQL Data from Weak and Strong LLMs.**](https://arxiv.org/abs/2408.03256) *Jiaxi Yang, Binyuan Hui, Min Yang, Jian Yang, Junyang Lin, Chang Zhou.* ACL 2024.
- 
### 3.4. Preference Optimization
- [**Refined Direct Preference Optimization with Synthetic Data for Behavioral Alignment of LLMs.**](https://arxiv.org/abs/2402.08005) *V´ıctor Gallego.* Arxiv 2024.

### 3.5. Reward Modeling
- [**West-of-N: Synthetic Preference Generation for Improved Reward Modeling.**](https://arxiv.org/abs/2401.12086) *Alizée Pace, Jonathan Mallinson, Eric Malmi, Sebastian Krause, Aliaksei Severyn.* Arxiv 2024.


## 4. Datasets

- [**Synthetic-Text-To-SQL: A synthetic dataset for training language models to generate SQL queries from natural language prompts.**](https://huggingface.co/datasets/gretelai/synthetic-text-to-sql) *Meyer, Yev and Emadi, Marjan and Nathawani, Dhruv and Ramaswamy, Lipika and Boyd, Kendrick and Van Segbroeck, Maarten and Grossman, Matthew and Mlocek, Piotr and Newberry, Drew.* Huggingface 2024.

## 5. Tools

- [**DataDreamer: A Tool for Synthetic Data Generation and Reproducible LLM Workflows.**](https://arxiv.org/abs/2402.10379) *Ajay Patel, Colin Raffel, Chris Callison-Burch.* ACL 2024.
- [**AgentInstruct: Toward Generative Teaching with Agentic Flows.**](https://arxiv.org/abs/2407.03502) *Arindam Mitra, Luciano Del Corro, Guoqing Zheng, Shweti Mahajan, Dany Rouhana, Andres Codas, Yadong Lu, Wei-ge Chen, Olga Vrousgos, Corby Rosset, Fillipe Silva, Hamed Khanpour, Yash Lara, Ahmed Awadallah.* Arxiv 2024.

## 6. Blogs

- [**Synthetic dataset generation techniques: Self-Instruct.**](https://huggingface.co/blog/davanstrien/self-instruct) *Daniel van Strien.* 2024
- [**LLM-Driven Synthetic Data Generation, Curation & Evaluation.**](https://cobusgreyling.medium.com/llm-driven-synthetic-data-generation-curation-evaluation-33731e33b525) *Cobus Greyling.* 2024
- [**The Rise of Agentic Data Generation.**](https://huggingface.co/blog/mlabonne/agentic-datagen) *Maxime Labonne.* 2024

  
