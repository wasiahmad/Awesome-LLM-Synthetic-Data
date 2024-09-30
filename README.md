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
* [2. Methods](#2-Methods)
  * [2.1 Techniques](#21-Techniques)
  * [2.2 Instruction Generation with High Quality/Complexity](#22-Instruction-Generation-with-High-QualityComplexity)
* [3. Application Areas](#3-Application-Areas)
  * [3.1 Mathematical Reasoning](#31-Mathematical-Reasoning)
  * [3.2 Code Generation](#32-Code-Generation)
  * [3.3 Text-to-SQL](#33-Text-to-SQL)
  * [3.4 Alignment](#34-Alignment)
  * [3.5 Reward Modeling](#35-Reward-Modeling)
  * [3.6 Long Context](#36-Long-Context)
  * [3.7 Weak to Strong](#37-Weak-to-Strong)
  * [3.8 Agent and Tool Use](#38-Agent-and-Tool-Use)
  * [3.9 Vision and Language](#39-Vision-and-Language)
  * [3.10 Factuality](#310-Factuality)
* [4. Datasets](#4-Datasets)
* [5. Tools](#5-Tools)
* [6. Blogs](#6-Blogs)

### 1. Surveys

- [**Best Practices and Lessons Learned on Synthetic Data for Language Models.**](https://arxiv.org/abs/2404.07503) *Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou, Andrew M. Dai.* Arxiv 2024.
- [**On LLMs-Driven Synthetic Data Generation, Curation, and Evaluation: A Survey.**](https://arxiv.org/abs/2406.15126) *Lin Long, Rui Wang, Ruixuan Xiao, Junbo Zhao, Xiao Ding, Gang Chen, Haobo Wang.* Arxiv 2024.
- [**Large Language Models for Data Annotation: A Survey**](https://arxiv.org/abs/2402.13446) *Zhen Tan, Dawei Li, Song Wang, Alimohammad Beigi, Bohan Jiang, Amrita Bhattacharjee, Mansooreh Karami, Jundong Li, Lu Cheng, Huan Liu.* Arxiv 2024.
- [**Generative AI for Synthetic Data Generation: Methods, Challenges and the Future.**](https://arxiv.org/abs/2403.04190) *Xu Guo, Yiqiang Chen.* Arxiv 2024.
- [**Comprehensive Exploration of Synthetic Data Generation: A Survey.**](https://arxiv.org/abs/2401.02524) *André Bauer, Simon Trapp, Michael Stenger, Robert Leppich, Samuel Kounev, Mark Leznik, Kyle Chard, Ian Foster.* Arxiv 2024.


## 2. Methods

### 2.1. Techniques

- [**STaR: Bootstrapping Reasoning With Reasoning**](https://arxiv.org/abs/2203.14465) *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman.* NeurIPS 2022.
- [**Symbolic Knowledge Distillation: from General Language Models to Commonsense Models**](https://arxiv.org/abs/2110.07178) *Peter West, Chandra Bhagavatula, Jack Hessel, Jena D. Hwang, Liwei Jiang, Ronan Le Bras, Ximing Lu, Sean Welleck, Yejin Choi.* NAACL 2022.
- [**Generating Training Data with Language Models: Towards Zero-Shot Language Understanding**](https://arxiv.org/abs/2202.04538) *Yu Meng, Jiaxin Huang, Yu Zhang, Jiawei Han.* NeurIPS 2022.
- [**ZeroGen: Efficient Zero-shot Learning via Dataset Generation**](https://arxiv.org/abs/2202.07922) *Jiacheng Ye, Jiahui Gao, Qintong Li, Hang Xu, Jiangtao Feng, Zhiyong Wu, Tao Yu, Lingpeng Kong.* EMNLP 2022.
- [**Large Language Models Can Self-Improve**](https://aclanthology.org/2023.emnlp-main.67/) *Jiaxin Huang, Shixiang Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han.* EMNLP 2023.
- [**Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models.**](https://arxiv.org/abs/2401.01335) *Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu.* ICML 2024.
- [**Self-Rewarding Language Models.**](https://arxiv.org/abs/2401.10020) *Weizhe Yuan, Richard Yuanzhe Pang, Kyunghyun Cho, Xian Li, Sainbayar Sukhbaatar, Jing Xu, Jason Weston.* Arxiv 2024.
- [**Synthetic Data (Almost) from Scratch: Generalized Instruction Tuning for Language Models.**](https://arxiv.org/abs/2402.13064) *Haoran Li, Qingxiu Dong, Zhengyang Tang, Chaojun Wang, Xingxing Zhang, Haoyang Huang, Shaohan Huang, Xiaolong Huang, Zeqiang Huang, Dongdong Zhang, Yuxian Gu, Xin Cheng, Xun Wang, Si-Qing Chen, Li Dong, Wei Lu, Zhifang Sui, Benyou Wang, Wai Lam, Furu Wei.* Arxiv 2024.
- [**Self-instruct: Aligning language models with self-generated instructions.**](https://arxiv.org/abs/2212.10560) *Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi, Hannaneh Hajishirzi.* ACL 2023.
- [**TarGEN: Targeted Data Generation with Large Language Models**](https://arxiv.org/abs/2310.17876) *Himanshu Gupta, Kevin Scaria, Ujjwala Anantheswaran, Shreyas Verma, Mihir Parmar, Saurabh Arjun Sawant, Chitta Baral, Swaroop Mishra.* COLM 2024.
- [**Automatic Instruction Evolving for Large Language Models.**](https://arxiv.org/abs/2406.00770) *Weihao Zeng, Can Xu, Yingxiu Zhao, Jian-Guang Lou, Weizhu Chen.* Arxiv 2024.
- [**Scaling Synthetic Data Creation with 1,000,000,000 Personas.**](https://arxiv.org/abs/2406.20094) *Xin Chan, Xiaoyang Wang, Dian Yu, Haitao Mi, Dong Yu.* Arxiv 2024.
- [**Self-playing Adversarial Language Game Enhances LLM Reasoning**](https://arxiv.org/abs/2404.10642) *Pengyu Cheng, Tianhao Hu, Han Xu, Zhisong Zhang, Yong Dai, Lei Han, Nan Du* Arxiv 2024.
- [**Source2Synth: Synthetic Data Generation and Curation Grounded in Real Data Sources**](https://arxiv.org/abs/2409.08239) *Alisia Lupidi, Carlos Gemmell, Nicola Cancedda, Jane Dwivedi-Yu, Jason Weston, Jakob Foerster, Roberta Raileanu, Maria Lomeli* Arxiv 2024.
- [**Learning to Generate Instruction Tuning Datasets for Zero-Shot Task Adaptation**](https://arxiv.org/abs/2402.18334) *Nihal V. Nayak, Yiyang Nan, Avi Trost, Stephen H. Bach* ACL Findings 2024.

### 2.2. Instruction Generation with High Quality/Complexity

- [**CodecLM: Aligning Language Models with Tailored Synthetic Data.**](https://arxiv.org/abs/2404.05875) *Zifeng Wang, Chun-Liang Li, Vincent Perot, Long T. Le, Jin Miao, Zizhao Zhang, Chen-Yu Lee, Tomas Pfister.* Findings of NAACL 2024.
- [**WizardLM: Empowering Large Language Models to Follow Complex Instructions.**](https://arxiv.org/abs/2304.12244) *Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jiang.* Arxiv 2023. 

## 3. Application Areas

### 3.1. Mathematical Reasoning
- [**MuggleMath: Assessing the Impact of Query and Response Augmentation on Math Reasoning.**](https://arxiv.org/abs/2310.05506v3) *Chengpeng Li, Zheng Yuan, Hongyi Yuan, Guanting Dong, Keming Lu, Jiancan Wu, Chuanqi Tan, Xiang Wang, Chang Zhou.* ACL 2024.
- [**MathGenie: Generating Synthetic Data with Question Back-translation for Enhancing Mathematical Reasoning of LLMs.**](https://arxiv.org/abs/2402.16352) *Zimu Lu, Aojun Zhou, Houxing Ren, Ke Wang, Weikang Shi, Junting Pan, Mingjie Zhan, Hongsheng Li.* ACL 2024.
- [**MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models.**](https://arxiv.org/abs/2309.12284) *Longhui Yu, Weisen Jiang, Han Shi, Jincheng Yu, Zhengying Liu, Yu Zhang, James T. Kwok, Zhenguo Li, Adrian Weller, Weiyang Liu.* ICLR 2024.
- [**Augmenting Math Word Problems via Iterative Question Composing.**](https://arxiv.org/abs/2401.09003) *Haoxiong Liu, Yifan Zhang, Yifan Luo, Andrew Chi-Chih Yao.* DPFM@ICLR 2024.

### 3.2. Code Generation
- [**Language Models Can Teach Themselves to Program Better**](https://arxiv.org/abs/2207.14502) *Patrick Haluptzok, Matthew Bowers, Adam Tauman Kalai.* ICLR 2023.
- [**Genetic Instruct: Scaling up Synthetic Generation of Coding Instructions for Large Language Models.**](https://arxiv.org/abs/2407.21077) *Somshubra Majumdar, Vahid Noroozi, Sean Narenthiran, Aleksander Ficek, Jagadeesh Balam, Boris Ginsburg.* Arxiv 2024.
- [**Learning Performance-Improving Code Edits**](https://arxiv.org/abs/2302.07867) *Alexander Shypula, Aman Madaan, Yimeng Zeng, Uri Alon, Jacob Gardner, Milad Hashemi, Graham Neubig, Parthasarathy Ranganathan, Osbert Bastani, Amir Yazdanbakhsh.* ICLR 2024.

### 3.3. Text-to-SQL
- [**Synthesizing Text-to-SQL Data from Weak and Strong LLMs.**](https://arxiv.org/abs/2408.03256) *Jiaxi Yang, Binyuan Hui, Min Yang, Jian Yang, Junyang Lin, Chang Zhou.* ACL 2024.

### 3.4. Alignment

- [**Constitutional AI: Harmlessness from AI Feedback.**](https://arxiv.org/abs/2212.08073) *Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen, Anna Goldie, Azalia Mirhoseini, Cameron McKinnon, Carol Chen, Catherine Olsson, Christopher Olah, Danny Hernandez, Dawn Drain, Deep Ganguli, Dustin Li, Eli Tran-Johnson, Ethan Perez, Jamie Kerr, Jared Mueller, Jeffrey Ladish, Joshua Landau, Kamal Ndousse, Kamile Lukosuite, Liane Lovitt, Michael Sellitto, Nelson Elhage, Nicholas Schiefer, Noemi Mercado, Nova DasSarma, Robert Lasenby, Robin Larson, Sam Ringer, Scott Johnston, Shauna Kravec, Sheer El Showk, Stanislav Fort, Tamera Lanham, Timothy Telleen-Lawton, Tom Conerly, Tom Henighan, Tristan Hume, Samuel R. Bowman, Zac Hatfield-Dodds, Ben Mann, Dario Amodei, Nicholas Joseph, Sam McCandlish, Tom Brown, Jared Kaplan.* Arxiv 2022.
- [**Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision**](https://arxiv.org/abs/2305.03047) *Zhiqing Sun, Yikang Shen, Qinhong Zhou, Hongxin Zhang, Zhenfang Chen, David Cox, Yiming Yang, Chuang Gan.* NeurIPS 2023.
- [**SALMON: Self-Alignment with Instructable Reward Models**](https://arxiv.org/abs/2310.05910) *Zhiqing Sun, Yikang Shen, Hongxin Zhang, Qinhong Zhou, Zhenfang Chen, David Cox, Yiming Yang, Chuang Gan.* ICLR 2024.
- [**Refined Direct Preference Optimization with Synthetic Data for Behavioral Alignment of LLMs.**](https://arxiv.org/abs/2402.08005) *V´ıctor Gallego.* Arxiv 2024.
- [**Self-play with Execution Feedback: Improving Instruction-following Capabilities of Large Language Models**](https://arxiv.org/abs/2406.13542) *Guanting Dong, Keming Lu, Chengpeng Li, Tingyu Xia, Bowen Yu, Chang Zhou, Jingren Zhou* Arxiv 2024.


### 3.5. Reward Modeling
- [**West-of-N: Synthetic Preference Generation for Improved Reward Modeling.**](https://arxiv.org/abs/2401.12086) *Alizée Pace, Jonathan Mallinson, Eric Malmi, Sebastian Krause, Aliaksei Severyn.* Arxiv 2024.

### 3.6. Long Context
- [**Make Your LLM Fully Utilize the Context.**](https://arxiv.org/abs/2404.16811) *Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou.* Arxiv 2024.

### 3.7. Weak-to-Strong

- [**Impossible Distillation for Paraphrasing and Summarization: How to Make High-quality Lemonade out of Small, Low-quality Models**](https://arxiv.org/abs/2305.16635) *Jaehun Jung, Peter West, Liwei Jiang, Faeze Brahman, Ximing Lu, Jillian Fisher, Taylor Sorensen, Yejin Choi.* NAACL 2024.

### 3.8. Agent and Tool Use

- [**Toolformer: Language Models Can Teach Themselves to Use Tools**](https://arxiv.org/abs/2302.04761) *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom.* NeurIPS 2023.
- [**GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**](https://arxiv.org/abs/2305.18752) *Rui Yang, Lin Song, Yanwei Li, Sijie Zhao, Yixiao Ge, Xiu Li, Ying Shan.* Arxiv 2024.
- [**Gorilla: Large Language Model Connected with Massive APIs**]() *Shishir G. Patil, Tianjun Zhang, Xin Wang, Joseph E. Gonzalez.* Arxiv 2023.
- [**ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases**](https://arxiv.org/abs/2306.05301) *Qiaoyu Tang, Ziliang Deng, Hongyu Lin, Xianpei Han, Qiao Liang, Boxi Cao, Le Sun.* Arxiv 2023.
- [**Voyager: An Open-Ended Embodied Agent with Large Language Models**](https://arxiv.org/abs/2305.16291) *Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar.* Arxiv 2023.

### 3.9. Vision and Language

- [**Visual Instruction Tuning**](https://arxiv.org/abs/2304.08485) *Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee.* NeurIPS 2023.
- [**MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models**](https://arxiv.org/abs/2304.10592) *Deyao Zhu, Jun Chen, Xiaoqian Shen, Xiang Li, Mohamed Elhoseiny.* ICLR 2024.
- [**Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond**](https://arxiv.org/abs/2308.12966) *Jinze Bai, Shuai Bai, Shusheng Yang, Shijie Wang, Sinan Tan, Peng Wang, Junyang Lin, Chang Zhou, Jingren Zhou.* Arxiv 2023.
- [**G-LLaVA: Solving Geometric Problem with Multi-Modal Large Language Model**](https://arxiv.org/abs/2312.11370) *Jiahui Gao, Renjie Pi, Jipeng Zhang, Jiacheng Ye, Wanjun Zhong, Yufei Wang, Lanqing Hong, Jianhua Han, Hang Xu, Zhenguo Li, Lingpeng Kong.* Arxiv 2023.
- [**Enhancing Large Vision Language Models with Self-Training on Image Comprehension**](https://arxiv.org/abs/2405.19716) *Yihe Deng, Pan Lu, Fan Yin, Ziniu Hu, Sheng Shen, James Zou, Kai-Wei Chang, Wei Wang.* Arxiv 2024.

### 3.10. Factuality

- [**Fine-tuning Language Models for Factuality**](https://arxiv.org/abs/2311.08401) *Katherine Tian, Eric Mitchell, Huaxiu Yao, Christopher D. Manning, Chelsea Finn.* Arxiv 2023.
- [**MiniCheck: Efficient Fact-Checking of LLMs on Grounding Documents**](https://arxiv.org/abs/2404.10774) *Liyan Tang, Philippe Laban, Greg Durrett.* Arxiv 2024.


## 4. Datasets

- [**Synthetic-Text-To-SQL: A synthetic dataset for training language models to generate SQL queries from natural language prompts.**](https://huggingface.co/datasets/gretelai/synthetic-text-to-sql) *Meyer, Yev and Emadi, Marjan and Nathawani, Dhruv and Ramaswamy, Lipika and Boyd, Kendrick and Van Segbroeck, Maarten and Grossman, Matthew and Mlocek, Piotr and Newberry, Drew.* Huggingface 2024.

## 5. Tools

- [**DataDreamer: A Tool for Synthetic Data Generation and Reproducible LLM Workflows.**](https://arxiv.org/abs/2402.10379) *Ajay Patel, Colin Raffel, Chris Callison-Burch.* ACL 2024.
- [**AgentInstruct: Toward Generative Teaching with Agentic Flows.**](https://arxiv.org/abs/2407.03502) *Arindam Mitra, Luciano Del Corro, Guoqing Zheng, Shweti Mahajan, Dany Rouhana, Andres Codas, Yadong Lu, Wei-ge Chen, Olga Vrousgos, Corby Rosset, Fillipe Silva, Hamed Khanpour, Yash Lara, Ahmed Awadallah.* Arxiv 2024.

## 6. Blogs

- [**Synthetic dataset generation techniques: Self-Instruct.**](https://huggingface.co/blog/davanstrien/self-instruct) *Daniel van Strien.* 2024
- [**LLM-Driven Synthetic Data Generation, Curation & Evaluation.**](https://cobusgreyling.medium.com/llm-driven-synthetic-data-generation-curation-evaluation-33731e33b525) *Cobus Greyling.* 2024
- [**The Rise of Agentic Data Generation.**](https://huggingface.co/blog/mlabonne/agentic-datagen) *Maxime Labonne.* 2024

  
