A collection of awesome public projects about LLM Safety.

## Table of Contents
  - [Awesome-LLM-Safety](#awesome-llm-safety)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Survey](#survey)
  - [LLM Safety Subtopic List](#llm-safety-subtopic-list)
  - [Dataset](#dataset)

## Overview

to do...

## Survey

some papers and blogs



## LLM Safety Subtopic List

some papers and blogs

### 毒性（Toxicity）

模型在生成文本时可能会产生的有害内容。

- [A New Generation of Perspective API: Efficient Multilingual Character-level Transformers](https://arxiv.org/abs/2202.11176)
  - arXiv  

### 越狱 & 攻击（jailbreak & attack）

一系列尝试绕过或破坏模型内置的安全限制，以迫使模型执行它通常被设计为拒绝的任务或生成有害内容的行为

- [A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily](https://arxiv.org/pdf/2311.08268)
  - NAACL 2024

### 幻觉（Hallucination）

模型可能生成虚假或不准确的信息，这些信息在现实世界中并不存在。

- [A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions](https://arxiv.org/abs/2311.05232)
  - arXiv

### 隐私和数据安全（Privacy and Data Security）

保护用户的个人数据不被泄露，包括在模型训练和使用过程中。确保模型训练和使用的数据安全，防止未授权访问和数据泄露。

- [DEPN: Detecting and Editing Privacy Neurons in Pretrained Language Models](https://arxiv.org/abs/2310.20138)
  - EMNLP2023

### 偏见和歧视（Bias & discrimination）

模型可能会复制或放大训练数据中的偏见，导致不公平或歧视性的结果。

- [Bias and Fairness in Large Language Models: A Survey](https://arxiv.org/abs/2309.00770)
  - arXiv

### 滥用（abuse）

模型可能被用于不当目的，如制造假新闻、网络钓鱼、欺诈等。（如何对抗/审查？）

- [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698)
  - NeurIPS 2023

### 社会影响（social influence）

LLM安全性对社会的潜在影响，如监管、治理等。

### 安全代码大模型（Safe Code LLM）

#### 代码大模型

- [Code Llama: Open Foundation Models for Code](https://arxiv.org/abs/2308.12950)
  - arXiv

#### 评估框架
- [HumanEval](https://github.com/openai/human-eval)
  - 测试模型根据文档字符串完成代码的能力。
 
- [MBPP](https://github.com/google-research/google-research/tree/master/mbpp)
  - 测试模型根据描述编写代码的能力。
 
- [MultiPL-E](https://github.com/nuprl/MultiPL-E)
  - 测试模型多语言编程能力。

#### 相关博客

- [Large Language Models for Code Generation](https://blog.fabrichq.ai/large-language-models-for-code-generation-f95f93fe7de4)

- [The Top LLMs For Code Generation: 2024 Edition](https://www.scribbledata.io/blog/the-top-llms-for-code-generation-2024-edition/)

- [代码大模型论文汇总](https://blog.csdn.net/wtyuong/article/details/134650727)

## Dataset

