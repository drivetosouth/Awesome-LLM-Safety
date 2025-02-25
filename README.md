# Awesome LLM Safety Papers :
case:
1. **"Racial Disparity in Natural Language Processing: A Case Study of Social Media African-American English"**.

	*Su Lin Blodgett et al*. arxiv 2017. [[Paper](http://arxiv.org/abs/1707.00061)]

2. **"Predicting the Type and Target of Offensive Posts in Social Media"**.

	*Marcos Zampieri et al*. HLT-NAACL 2019. [[Paper](https://arxiv.org/abs/1902.09666)] [[Source](http://scholar.harvard.edu/malmasi/olid)]

## Table of Contents

## Papers

### Attacks

#### Training Phase

##### Data poisoning

1. **"Poisoning Web-Scale Training Datasets is Practical"**.

   *Carlini, N et al.* IEEE Symposium on Security and Privacy(SP) 2024 . [[Paper](https://arxiv.org/abs/2302.10149)]

2. "**Data Poisoning for In-context Learning"**

   *He, P et al*. arxiv 2024. [[Paper](https://arxiv.org/abs/2402.02160)]

3. **"Learning to poison large language models during instruction tuning"**

   *Qiang, Y et al*. arxiv 2024. [[Paper](https://arxiv.org/abs/2402.13459)]

4. **“Forcing generative models to degenerate ones: The power of data poisoning attacks”**

   *Jiang, S. et al.* NeurIPS 2023 Workshop on Backdoors in Deep Learning. [[Paper](https://arxiv.org/abs/2312.04748)]

5. **"Fine-tuning aligned language models compromises safety, even when users do not intend to!"**

   *Qi, X. et al.* ICLR 2024. [[Paper](https://arxiv.org/abs/2310.03693)]

6. **"Poisoning language models during instruction tuning"**

   *Wan, A. et al.* ICML 2023. PMLR. [[Paper](https://arxiv.org/abs/2305.00944)]

7. **"On the Exploitability of Instruction Tuning"**

    *Shu, M et al.* NeurIPS 2023 . [[Paper](https://arxiv.org/abs/2306.17194)]

8. **"RLHFPoison: Reward poisoning attack for reinforcement learning with human feedback in large language models"**

   *Wang, J et al.* ACL 2024. [[Paper](https://aclanthology.org/2024.acl-long.140.pdf)]

9. **"Is poisoning a real threat to LLM alignment? Maybe more so than you think"**

*Pathmanathan, P et al.* ICML 2024 Workshop on Models of Human Feedback for AI Alignment . [[Paper](https://openreview.net/pdf?id=QTviVh3VQU)]

##### Backdoor Attacks

1. **“Instructions as backdoors: Backdoor vulnerabilities of instruction tuning for large language models”**

   *Xu, J. et al.* NAACL 2024. [[Paper](https://arxiv.org/abs/2305.14710)]

 2. **“Universal jailbreak backdoors from poisoned human feedback”**

    *Rando, J. et al.* ICLR 2024. [[Paper](https://arxiv.org/abs/2311.14455)]

3. **“Badrag: Identifying vulnerabilities in retrieval augmented generation of large language models”**

   *Xue, J. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2406.00083)]

4. **“Weight poisoning attacks on pretrained models”**

   *Kurita, K. et al.* ACL 2020. [[Paper](http://aclanthology.org/2020.acl-main.249.pdf)]

5. **“Backdooring instruction-tuned large language models with virtual prompt injection”**

   *Yan, J. et al.* NAACL 2024. [[Paper](https://aclanthology.org/2024.naacl-long.337.pdf)]

6. **“A backdoor attack against LSTM-based text classification systems”**

​	*Dai, J. et al.* IEEE Access 2019. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8836465)]

7. **“Hidden killer: Invisible textual backdoor attacks with syntactic trigger”**

   *Qi, F. et al.* ACL 2021. [[Paper](https://aclanthology.org/2021.acl-long.37.pdf)]

8. **“Prompt as triggers for backdoor attack: Examining the vulnerability in language models”**

​	*Zhao, S. et al.* EMNLP 2023. [[Paper](https://aclanthology.org/2023.emnlp-main.757.pdf)]

9. **“BITE: Textual backdoor attacks with iterative trigger injection”**

​	*Yan, J. et al.* ACL 2023. [[Paper](https://aclanthology.org/2023.acl-long.725.pdf)]

10. **“Talk too much: Poisoning large language models under token limit”**

​	*He, J. et al.* arXiv 2024. [[Paper](https://arxiv.org/html/2404.14795v3)]

11. **“Training-free lexical backdoor attacks on language models”**

​	*Huang, Y. et al.* ACM Web Conference 2023. [[Paper](https://arxiv.org/abs/2302.04116)]

12. **“Badchain: Backdoor chain-of-thought prompting for large language models”**

​	*Xiang, Z. et al.* NeurIPS 2023 Workshop. [[Paper](https://openreview.net/pdf?id=S4cYxINzjp)]

13. **“Defending against weight-poisoning backdoor attacks for parameter-efficient fine-tuning”**

​	*Zhao, S. et al.* NAACL 2024. [[Paper](https://aclanthology.org/2024.findings-naacl.217.pdf)]

14. **“Measuring impacts of poisoning on model parameters and embeddings for large language models of code”**

​	*Hussain, A. et al.* AIware 2024. [[Paper](https://dl.acm.org/doi/10.1145/3664646.3664764)]

15. **“Chain-of-scrutiny: Detecting backdoor attacks for large language models”**

​	*Li, X. et al.* arXiv 2024. [[Paper](https://arxiv.org/html/2406.05948v1)]

#### Training Phase

##### Model Stealing

1. **"Practical black-box attacks against machine learning"**  

    *Papernot, N. et al.* ACM Asia CCS 2017. [[Paper](https://arxiv.org/abs/1602.02697)]

2. **"Stealing part of a production language model"**  

    *Carlini, N. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2403.06634)]

3. **"Can’t hide behind the API: Stealing black-box commercial embedding models"**  

    *Tamber, M.S. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2406.09355)]

4. **"Mondrian: Prompt abstraction attack against large language models for cheaper API pricing"** 

    *Si, W.M. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2308.03558)]

5. **"Pleak: Prompt leaking attacks against large language model applications"**  

    *Hui, B. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2405.06823)]

6. **"Prompt stealing attacks against large language models"**  

    *Sha, Z. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2402.12959)]

7. **"Are you copying my model? Protecting the copyright of large language models for EaaS via backdoor watermark"**  

    *Peng, W. et al.* ACL 2023. [[Paper](https://aclanthology.org/2023.acl-long.423.pdf)]

8. **"Adaptive and robust watermark against model extraction attack"**  

    *Pang, K. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2405.02365)]

##### Privacy Leaking

1. **"Large language model watermark stealing with mixed integer programming"**  

    *Zhang, Z. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2405.19677)]

2. **"Are large pre-trained language models leaking your personal information?"**  

    *Huang, J. et al.* EMNLP 2022. [[Paper](https://doi.org/10.18653/v1/2022.findings-emnlp.148)]

3. **"Quantifying association capabilities of large language models and its implications on privacy leakage"**  

    *Shao, H. et al.* EACL 2024. [[Paper](https://aclanthology.org/2024.findings-eacl.54.pdf)]

4. **"Beyond memorization: Violating privacy via inference with large language models"**  

    *Staab, R. et al.* ICLR 2024. [[Paper](https://arxiv.org/abs/2310.07298)] [[Source](https://github.com/eth-sri/llmprivacy)]

5. **"Do membership inference attacks work on large language models?"**  

    *Duan, M. et al.* Language Modeling Conference 2024. [[Paper](https://aclanthology.org/2023.findings-acl.719.pdf)]

#### Operation Phase

##### Prompt Injection

1. **"Membership inference attack susceptibility of clinical language models"**  

    *Jagannatha, A. et al.* arXiv 2021. [[Paper](https://arxiv.org/abs/2104.08305)]

2. **"Scalable extraction of training data from (production) language models"**  

    *Nasr, M. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2311.17035)]

3. **"Exploiting programmatic behavior of LLMs: Dual-use through standard security attacks"**  

    *Kang, D. et al.* IEEE SPW 2024. [[Paper](https://arxiv.org/abs/2302.05733)]

4. **"Ignore previous prompt: Attack techniques for language models"**  

    *Perez, F. et al.* NeurIPS ML Safety Workshop 2022. [[Paper](https://openreview.net/pdf?id=qiaRo_7Zmug)]

5. **"Jailbreaking ChatGPT via prompt engineering: An empirical study"**  

    *Liu, Y. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2305.13860)]

6. **"Ignore this title and hackaprompt: Exposing systemic vulnerabilities of LLMs through a global prompt hacking competition"**  

    *Schulhoff, S. et al.* EMNLP 2023. [[Paper](https://aclanthology.org/2023.emnlp-main.302.pdf)]

7. **"Promptbench: Towards evaluating the robustness of large language models on adversarial prompts"**  

    *Zhu, K. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2306.04528)]

8. **"Tensor trust: Interpretable prompt injection attacks from an online game"**  

    *Toyer, S. et al.* ICLR 2024. [[Paper](https://openreview.net/pdf?id=fsW7wJGLBd)]

9. **"Benchmarking and defending against indirect prompt injection attacks on large language models"**  

    *Yi, J. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2312.14197)]

##### Jailbreak

1. **"InjecAgent: Benchmarking indirect prompt injections in tool-integrated large language model agents"**  

    *Zhan, Q. et al.* ACL 2024. [[Paper](https://aclanthology.org/2024.findings-acl.624.pdf)]

2. **"Not what you’ve signed up for: Compromising real-world LLM-integrated applications with indirect prompt injection"**  

    *Greshake, K. et al.* ACM AI and Security 2023. [[Paper](https://arxiv.org/abs/2302.12173)]

3. **"Tapi: Towards target-specific and adversarial prompt injection against code LLMs"**  

    *Yang, Y. et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2407.09164)]

4. **"Jailbroken: How does LLM safety training fail?"**  

    *Wei, A. et al.* NeurIPS 2023. [[Paper](https://openreview.net/forum?id=jA235JGM09)]

5. **"ArtPrompt: ASCII art-based jailbreak attacks against aligned LLMs"**  

    *Jiang, F. et al.* ACL 2024. [[Paper](https://aclanthology.org/2024.acl-long.809.pdf)]

6. **"Deepinception: Hypnotize large language model to be jailbreaker"**  

    *Li, X. et al.* arXiv 2023. [[Paper](https://example.com)] [[Source](https://github.com/tmlr-group/DeepInception)]

7. **"Autodan: Automatic and interpretable adversarial attacks on large language models"**  

    *Zhu, S. et al.* COLM 2024. [[Paper](https://arxiv.org/abs/2310.15140)]

8. **"Universal and transferable adversarial attacks on aligned language models"**  

    *Zou, A. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2307.15043)]

### Defenses