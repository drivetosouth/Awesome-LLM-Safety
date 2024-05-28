A collection of awesome public projects about LLM Safety.

## Table of Contents
  - [Awesome-LLM-Safety](#awesome-llm-safety)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Survey](#survey)

## Overview

to do...

## Survey

some papers and blogs

- [On Protecting the Data Privacy of Large Language Models (LLMs): A Survey](https://arxiv.org/pdf/2403.05156)
  - Biwei Yan, Kun Li, Minghui Xu, Yueyan Dong, Yue Zhang, Zhaochun Ren, Xiuzhen Cheng
  - 这篇论文聚焦于与LLM相关的**数据隐私**问题。文章首先介绍了LLM的隐私威胁，包括数据隐私泄露和数据隐私攻击，然后介绍了隐私保护的方法，根据保护的位置分为了预训练、微调和推理三个阶段。
 
- [Attacks, Defenses and Evaluations for LLM Conversation Safety: A Survey](http://arxiv.org/abs/2402.09283)
  - Zhichen Dong, Zhanhui Zhou, Chao Yang, Jing Shao, Yu Qiao
  - NAACL 2024
  - 这篇论文对LLM**对话安全**领域的近期研究做了全面概述。从攻击、防御和评估三个方面进行介绍。

- [From ChatGPT to ThreatGPT: Impact of Generative AI in Cybersecurity and Privacy](http://arxiv.org/abs/2307.00691)
  - Maanak Gupta, CharanKumar Akiri, Kshitiz Aryal, Eli Parker, Lopamudra Praharaj
  - 这篇论文对**GenAI在网络安全和隐私领域**的问题做了系统性概述。论文讨论了ChatGPT本身的漏洞，应用ChatGPT开发网络攻击工具，利用ChatGPT改进防御措施，ChatGPT的社会、法律和道德影响四个方面，并对ChatGPT和Bard做了安全性对比。
 
- [Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities](http://arxiv.org/abs/2308.12833)
  - Maximilian Mozes, Xuanli He, Bennett Kleinberg, Lewis D. Griffin
  - 这篇论文回顾了LLM**安全技术**工作的现状，将现有方法分为威胁、预防措施和漏洞三个方面进行阐述。威胁指通过LLM生成有害信息的方法，预防措施指试图减少LLM产生威胁的方法，漏洞指能够使得通过不完美的预防措施对齐后的LLM重新产生威胁的方法。
 
- [A Survey on Large Language Model (LLM) Security and Privacy: The Good, the Bad, and the Ugly](https://arxiv.org/abs/2312.02003)
  - Yifan Yao, Jinhao Duan, Kaidi Xu, Yuanfang Cai, Zhibo Sun, Yue Zhang
  - 这篇论文调研了LLM在**安全和隐私领域**的积极和消极影响。并将其分为三个方面进行阐述：The Good（LLM对安全界的积极影响），The Bad（利用LLM对安全和隐私进行攻击），The Ugly（LLM本身的漏洞，并探讨了防御措施）。

- [Aligning Large Language Models with Human: A Survey](http://arxiv.org/abs/2307.12966)
  - Yufei Wang, Wanjun Zhong, Liangyou Li, Fei Mi, Xingshan Zeng, Wenyong Huang, Lifeng Shang, Xin Jiang, Qun Liu
  - 这篇论文聚焦于**LLM对齐**的相关技术。包括数据收集、训练方法、模型评估三个方面。

- [Breaking Down the Defenses: A Comparative Survey of Attacks on Large Language Models](http://arxiv.org/abs/2403.04786)
  - Arijit Ghosh Chowdhury, Md Mofijul Islam, Vaibhav Kumar, Faysal Hossain Shezan, Vaibhav Kumar, Vinija Jain, Aman Chadha
  - 这篇论文对针对LLM的**不同形式的攻击**做了系统性调研，将攻击方式分为越狱、提示注入、数据投毒三种方式，并介绍了外部防御（输入/输出审查）、内部防御（训练/微调时防御）两种防御措施。

- [Security and Privacy Challenges of Large Language Models: A Survey](http://arxiv.org/abs/2402.00888)
  - Badhan Chandra Das, M. Hadi Amini, Yanzhao Wu
  - 这篇论文全面调研了LLM**安全和隐私**面临的威胁和防御措施。论文阐述了LLM的漏洞、针对LLM的安全和隐私攻击、针对不同类型攻击的防御技术和对于特定的LLM应用程序的风险。

## 潜在安全威胁和漏洞

some papers and blogs

### 训练阶段安全性问题

+ `数据投毒`
  
Data Poisoning is an adversarial attack that tries to manipulate the training dataset in order to control the prediction behavior of a trained model such that the model will label malicious examples into a desired classes (e.g., labeling spam e-mails as safe).

  - [Forcing Generative Models to Degenerate Ones: The Power of Data Poisoning Attacks](https://arxiv.org/abs/2312.04748)
    - Shuli Jiang, Swanand Ravindra Kadhe, Yi Zhou, Ling Cai, Nathalie Baracaldo

  - [On the exploitability of instruction tuning](https://arxiv.org/abs/2306.17194)
    - Manli Shu, Jiongxiao Wang, Chen Zhu, Jonas Geiping, Chaowei Xiao, Tom Goldstein
   
  - [Learning to Poison Large Language Models During Instruction Tuning](https://arxiv.org/abs/2402.13459v1)
    - Yao Qiang, Xiangyu Zhou, Saleh Zare Zade, Mohammad Amin Roshani, Douglas Zytko, Dongxiao Zhu
   
  - [Poisoning Language Models During Instruction Tuning](https://proceedings.mlr.press/v202/wan23b.html)
    - Alexander Wan, Eric Wallace, Sheng Shen, Dan Klein
    - PLMR 2023

  - [Data Poisoning for In-context Learning](https://arxiv.org/abs/2402.02160)
    - Pengfei He, Han Xu, Yue Xing, Hui Liu, Makoto Yamada, Jiliang Tang
   
  - 
+ `后门攻击`

Backdoor attacks inject maliciously constructed data into a training set so that, at test time, the trained model misclassifies inputs patched with a backdoor trigger as an adversarially-desired target class.
  
  - [BITE: Textual Backdoor Attacks with Iterative Trigger Injection](https://arxiv.org/abs/2205.12700)
    - Jun Yan, Vansh Gupta, Xiang Ren
    - ACL 2023
 
  - [Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models](https://arxiv.org/abs/2305.01219)
    - Shuai Zhao, Jinming Wen, Luu Anh Tuan, Junbo Zhao, Jie Fu
    - EMNLP 2023
 
  - [Backdooring Instruction-Tuned Large Language Models with Virtual Prompt Injection](https://arxiv.org/abs/2307.16888)
    - Jun Yan, Vikas Yadav, Shiyang Li, Lichang Chen, Zheng Tang, Hai Wang, Vijay Srinivasan, Xiang Ren, Hongxia Jin
    - NAACL 2024
 
  - [Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)
    - Jiashu Xu, Mingyu Derek Ma, Fei Wang, Chaowei Xiao, Muhao Chen
    - NAACL 2024
   
  - [Talk Too Much: Poisoning Large Language Models under Token Limit](https://arxiv.org/abs/2404.14795)
    - Jiaming He, Wenbo Jiang, Guanyu Hou, Wenshu Fan, Rui Zhang, Hongwei Li

  - [Training-free Lexical Backdoor Attacks on Language Models](https://arxiv.org/abs/2302.04116v1)
    - Yujin Huang, Terry Yue Zhuo, Qiongkai Xu, Han Hu, Xingliang Yuan, Chunyang Chen
    - WWW 2023
   
  - [Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment](https://arxiv.org/abs/2311.09433)
    - Haoran Wang, Kai Shu
      
  - [Universal Jailbreak Backdoors from Poisoned Human Feedback](https://arxiv.org/abs/2311.14455)
    - Javier Rando, Florian Tramèr
    - ICLR 2024
   
  - [Stealthy and Persistent Unalignment on Large Language Models via Backdoor Injections](https://arxiv.org/abs/2312.00027)
    - Yuanpu Cao, Bochuan Cao, Jinghui Chen

### 推理阶段安全性问题

+ `提示注入`

Prompt injections involve bypassing filters or manipulating the LLM using carefully crafted prompts that make the model ignore previous instructions or perform unintended actions. These vulnerabilities can lead to unintended consequences, including data leakage, unauthorized access, or other security breaches.

  - [Ignore Previous Prompt: Attack Techniques For Language Models](https://arxiv.org/abs/2211.09527)
    - Fábio Perez, Ian Ribeiro
    - NeurIPS 2022

  - ["Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models](https://arxiv.org/abs/2308.03825)
    - Xinyue Shen, Zeyuan Chen, Michael Backes, Yun Shen, Yang Zhang

  - [Prompt Injection attack against LLM-integrated Applications](https://arxiv.org/abs/2306.05499)
    - Yi Liu, Gelei Deng, Yuekang Li, Kailong Wang, Zihao Wang, Xiaofeng Wang, Tianwei Zhang, Yepang Liu, Haoyu Wang, Yan Zheng, Yang Liu

  - [Jailbroken: How Does LLM Safety Training Fail?](https://proceedings.neurips.cc/paper_files/paper/2023/hash/fd6613131889a4b656206c50a8bd7790-Abstract-Conference.html)
    - Alexander Wei, Nika Haghtalab, Jacob Steinhardt
    - NeurIPS 2023
   
  - [More than you’ve asked for: A comprehensive analysis of novel prompt injection threats to application-integrated large language models](https://ui.adsabs.harvard.edu/abs/2023arXiv230212173G/abstract)
    - Greshake, Kai ; Abdelnabi, Sahar ; Mishra, Shailesh ; Endres, Christoph ; Holz, Thorsten ; Fritz, Mario

  - [Safeguarding Crowdsourcing Surveys from ChatGPT with Prompt Injection](https://arxiv.org/abs/2306.08833)
    - Chaofan Wang, Samuel Kernan Freire, Mo Zhang, Jing Wei, Jorge Goncalves, Vassilis Kostakos, Zhanna Sarsenbayeva, Christina Schneegass, Alessandro Bozzon, Evangelos Niforatos
   
  - [Effective Prompt Extraction from Language Models](https://arxiv.org/abs/2307.06865)
    - Yiming Zhang, Nicholas Carlini, Daphne Ippolito
   

+ `幻觉和错误信息`

### 部署阶段安全性问题

+ `模型窃取`

Model theft attacks occur when an attacker gains access to the model’s parameters.

 - [Stealing Part of a Production Language Model](https://arxiv.org/abs/2403.06634)
   - Nicholas Carlini, Daniel Paleka, Krishnamurthy Dj Dvijotham, Thomas Steinke, Jonathan Hayase, A. Feder Cooper, Katherine Lee, Matthew Jagielski, Milad Nasr, Arthur Conmy, Eric Wallace, David Rolnick, Florian Tramèr

  - [A Fast, Performant, Secure Distributed Training Framework For LLM](https://ieeexplore.ieee.org/abstract/document/10446717)
    - Wei Huang; Yinggui Wang; Anda Cheng; Aihui Zhou; Chaofan Yu; Lei Wang
    - IEEE 2024
   
  - [Matching Pairs: Attributing Fine-Tuned Models to their Pre-Trained Large Language Models](https://arxiv.org/abs/2306.09308)
    - Myles Foley, Ambrish Rawat, Taesung Lee, Yufang Hou, Gabriele Picco, Giulio Zizzo

  - [Secure Your Model: An Effective Key Prompt Protection Mechanism for Large Language Models](https://www.researchgate.net/profile/Ruixiang-Tang/publication/374555007_Secure_Your_Model_An_Effective_Key_Prompt_Protection_Mechanism_for_Large_Language_Models/links/65f8a03b286738732d5ce0d3/Secure-Your-Model-An-Effective-Key-Prompt-Protection-Mechanism-for-Large-Language-Models.pdf)
    - Tang, Ruixiang and Chuang, Yu-Neng and Cai, Xuanting and Platforms, Meta and Du, Mengnan and Hu, Xia

+ `数据泄露`

Data leakage occurs when an LLM accidentally reveals sensitive information, proprietary algorithms, or other confidential details through its responses. This can result in unauthorized access to sensitive data or intellectual property, privacy violations, and other security breaches.

  -[Teach LLMs to Phish: Stealing Private Information from Language Models](https://arxiv.org/abs/2403.00871)
    - Ashwinee Panda, Christopher A. Choquette-Choo, Zhengming Zhang, Yaoqing Yang, Prateek Mittal
    - ICLR 2024

  - [The janus interface: How finetuning in large language models amplifies the privacy risks](https://arxiv.org/abs/2310.15469)
    - Xiaoyi Chen, Siyuan Tang, Rui Zhu, Shijun Yan, Lei Jin, Zihao Wang, Liya Su, Zhikun Zhang, XiaoFeng Wang, Haixu Tang

  - [Analyzing leakage of personally identifiable information in language models](https://ieeexplore.ieee.org/abstract/document/10179300)
    - Nils Lukas; Ahmed Salem; Robert Sim; Shruti Tople; Lukas Wutschitz; Santiago Zanella-Béguelin
    - IEEE 2023
   
  - [Beyond Memorization: Violating Privacy Via Inference with Large Language Models](https://arxiv.org/abs/2310.07298)
    - Robin Staab, Mark Vero, Mislav Balunović, Martin Vechev
   
  - [Cybercrime and privacy threats of large language models](https://ieeexplore.ieee.org/abstract/document/10174273)
    - Nir Kshetri

  - [Information leakage in embedding models](https://arxiv.org/abs/2004.00053)
    - Congzheng Song, Ananth Raghunathan
   
  - [Extracting training data from large language models](https://arxiv.org/abs/2012.07805)
    - Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, Katherine Lee, Adam Roberts, Tom Brown, Dawn Song, Ulfar Erlingsson, Alina Oprea, Colin Raffel

  - [Text revealer: Private text reconstruction via model inversion attacks against transformers](https://arxiv.org/abs/2209.10505)
    - Ruisi Zhang, Seira Hidano, Farinaz Koushanfar

## 安全性防御措施和技术

### 数据安全

+ `数据预处理`

+ `数据检查`
  
### 模型安全

+ `模型对齐`

+ `对抗性训练`

### 部署安全

### 推理安全

## 安全评估方法

### 评估标准

### 评估方法

+ `评估平台`

+ `数据集`
