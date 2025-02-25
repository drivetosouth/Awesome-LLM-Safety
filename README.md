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

    *Li, X. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2311.03191)] [[Source](https://github.com/tmlr-group/DeepInception)]

7. **"Autodan: Automatic and interpretable adversarial attacks on large language models"**  

    *Zhu, S. et al.* COLM 2024. [[Paper](https://arxiv.org/abs/2310.15140)]

8. **"Universal and transferable adversarial attacks on aligned language models"**  

    *Zou, A. et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2307.15043)]

### Defenses

#### Data Security

##### Data Preprocessing

1. **"Deduplicating training data makes language models better"**
   
    *Lee, Katherine, et al.* ACL 2022. [[Paper](https://aclanthology.org/2022.acl-long.577/)] [[Source](https://github.com/google-research/deduplicate-text-datasets)]

2. **"Deduplicating training data mitigates privacy risks in language models"**  

   *Kandpal, Nikhil, Eric Wallace, and Colin Raffel.* ICML 2022. [[Paper](https://arxiv.org/abs/2202.06539)]

3. **"The refinedweb dataset for falcon llm: outperforming curated corpora with web data, and web data only"**  

   *Penedo, Guilherme, et al.* NeurIPS 2023. [[Paper](https://arxiv.org/abs/2305.18674)]

4. **"Privacy- and Utility-Preserving NLP with Anonymized data: A case study of Pseudonymization"**  

   *Yermilov, Oleksandr, Vipul Raheja, and Artem Chernodub.* NeurIPS 2023. [[Paper](https://aclanthology.org/2023.trustnlp-1.20/)] [[Source](https://github.com/olexandryermilov/privacy-preserving-nlp)]

5. **"Large language models are advanced anonymizers"**
   *Staab, Robin, et al.* ICLR 2025. [[Paper](https://arxiv.org/abs/2402.13846)] [Source](https://github.com/robin-staab/anonymizer)

6. **"Beyond memorization: Violating privacy via inference with large language models"**
   
   *Staab, Robin, et al.* ICLR 2024. [[Paper]((https://arxiv.org/abs/2310.07298))] [Source]([XX](https://github.com/eth-sri/llmprivacy))

##### Differential Privacy

1. **"Calibrating noise to sensitivity in private data analysis"**
   
   *Dwork, Cynthia, et al.* TCC 2006. [[Paper]((https://link.springer.com/chapter/10.1007/11681878_14))]

2. **"Deep learning with differential privacy"**
   
   *Abadi, Martin, et al.* CCS 2016. [[Paper](https://dl.acm.org/doi/proceedings/10.1145/2976749)]

3. **"Dp-fp: Differentially private forward propagation for large models"**
   
   *Jian Du, Haitao Mi* arXiv 2021. [[Paper](https://arxiv.org/abs/2112.14430)]

4. **"Submix: Practical private prediction for large-scale language models"**
   
   *Ginart, Antonio, et al.* arXiv 2022. [[Paper](https://arxiv.org/abs/2201.00971)]

5.  **"Just fine-tune twice: Selective differential privacy for large language models"**
   
   *Shi, Weiyan, et al.* EMNLP 2022. [[Paper](https://aclanthology.org/2022.emnlp-main.425/)]

6.  **"Ew-tune: A framework for privately fine-tuning large language models with differential privacy"**
   
   *Behnia, Rouzbeh, et al.* IEEE ICDMW 2022. [[Paper](https://arxiv.org/abs/2210.15042)]

7.  **"Privacy-preserving in-context learning for large language models."**
   
   *Wu, Tong, et al.* ICLR 2024. [[Paper](https://arxiv.org/abs/2305.01639)]

8.  **"Dpzero: dimension-independent and differentially private zeroth-order optimization"**
   
   *Zhang, Liang, et al.* NeurIPS. [[Paper](https://arxiv.org/abs/2310.09639)]

9.  **"De-amplifying bias from differential privacy in language model fine-tuning"**
   
   *Srivastava, Sanjari, et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2402.04489)]

##### Federated Learning

1. **"Integration of Large Language Models and Federated Learning"**
   
   *Chen, Chaochao, et al.* Patterns 2024. [[Paper](https://arxiv.org/abs/2307.08925)]

2. **"The future of large language model pre-training is federated"**
   
   *Sani, Lorenzo, et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2405.10853)]

3. **"Openfedllm: Training large language models on decentralized private data via federated learning"**
   
   *Ye, Rui, et al.* KDD 2024. [[Paper](https://dl.acm.org/doi/10.1145/3637528.3671582)] [[Source](https://github.com/rui-ye/OpenFedLLM)]

4.  **"Shieldgemma: Generative ai content moderation based on gemma"**
   
   *Zeng, Wenjun, et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2407.21772)]

5.  **"Differentially private low-rank adaptation of large language model using federated learning"**
   
   *Liu, Xiao-Yang, et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2312.17493)]

##### Unlearning

1.  **"Large language model unlearning"**
   
   *Yao, Yuanshun, Xiaojun Xu, and Yang Liu.* NeurIPS 2024. [[Paper](https://openreview.net/forum?id=8Dy42ThoNe)] [Source](https://github.com/kevinyaobytedance/llm_unlearn)


2.  **"Who’s harry potter? approximate unlearning in llms"**
   
   *Eldan, Ronen, and Mark Russinovich.* arXiv 2023. [[Paper](https://arxiv.org/abs/2310.02238)]

3.  **"Unlearn what you want to forget: Efficient unlearning for llms"**
   
   *Chen, Jiaao, and Diyi Yang.* EMNLP 2023. [[Paper](https://aclanthology.org/2023.emnlp-main.738/)] [Source](https://github.com/SALT-NLP/Efficient_Unlearning)

4.  **"Every language counts: Learn and unlearn in multilingual llms"**
   
   *Lu, Taiming, and Philipp Koehn.* arXiv 2024. [[Paper](https://arxiv.org/abs/2406.13748)] [Source](https://github.com/TaiMingLu/learn-unlearn)

5.  **"Ununlearning: Unlearning is not sufficient for content regulation in advanced generative ai"**
   
   *Shumailov, Ilia, et al.* arXiv 2024. [[Paper](https://arxiv.org/abs/2407.00106)]

#### Model Security

##### Red-Teaming

1.  **"Realtoxicityprompts: Evaluating neural toxic degeneration in language models"**
   
   *Gehman, Samuel, et al.* EMNLP 2020. [[Paper](https://aclanthology.org/2020.findings-emnlp.301/)]

2.  **"Bot-adversarial dialogue for safe conversational agents"**
   
   *Xu, Jing, et al.* NAACL 2021. [[Paper](https://aclanthology.org/2021.naacl-main.235/)]

3.  **"Red teaming language models to reduce harms: Methods, scaling behaviors, and lessons learned"**
   
   *Ganguli, Deep, et al.* arXiv 2022. [[Paper](https://arxiv.org/abs/2209.07858)] [Source](https://github.com/anthropics/hh-rlhf)

4.  **"Red teaming language models with language models"**
   
   *Perez, Ethan, et al.* EMNLP 2022. [[Paper](https://aclanthology.org/2022.emnlp-main.225/)]

5.  **"Gptfuzzer: Red teaming large language models with auto-generated jailbreak prompts"**
   
   *Yu, Jiahao, et al.* arXiv 2023. [[Paper](https://arxiv.org/abs/2309.10253)] [Source](https://github.com/sherdencooper/GPTFuzz)

6.  **"Persistent anti-muslim bias in large language models"**
   
   *Abid, Abubakar, Maheen Farooqi, and James Zou.* AAAI 2021. [[Paper](https://arxiv.org/abs/2101.05783)]

7.  **"Bias and fairness in large language models: A survey"**
   
   *Gallegos, Isabel O., et al.* CL 2024. [[Paper](https://aclanthology.org/2024.cl-3.8/)]

8.  **"Attack prompt generation for red teaming and defending large language models"**
   
   *Deng, Boyi, et al.* EMNLP 2023. [[Paper]([XX](https://aclanthology.org/2023.findings-emnlp.143/))]

9.  **"MART: Improving LLM safety with multi-round automatic red-teaming"**
   
   *Ge, Suyu, et al.* NAACL 2024. [[Paper](https://aclanthology.org/2024.naacl-long.107/)]

10. **"Automated progressive red teaming"**
   
   *Jiang, Bojian, et al.* COLING 2025. [[Paper](https://aclanthology.org/2025.coling-main.260/)]

11. **"Unveiling safety vulnerabilities of large language models"**
   
   *Kour, George, et al.* GEM 2023. [[Paper]((https://aclanthology.org/2023.gem-1.10/))]

12. **"Socialstigmaqa: A benchmark to uncover stigma amplification in generative language models"**
   
   *Nagireddy, Manish, et al.* AAAI 2024. [[Paper](https://arxiv.org/abs/2312.07492)]

13. **"Truthfulqa: Measuring how models mimic human falsehoods"**
   
   *Lin, Stephanie, Jacob Hilton, and Owain Evans.* ACL 2022. [[Paper](https://aclanthology.org/2022.acl-long.229/)] [Source](https://github.com/sylinrl/TruthfulQA)

14. **"Curiosity-driven red-teaming for large language models"**
   
   *Hong, Zhang-Wei, et al.* ICLR 2024. [[Paper](https://arxiv.org/abs/2402.19464)] [Source](https://github.com/Improbable-AI/curiosity_redteam)

##### Alignment

###### SFT

1. **"Self-instruct: Aligning language models with self-generated instructions"**
   
   *Wang, Yizhong, et al.* ACL 2023. [[Paper](https://aclanthology.org/2023.acl-long.754/)] [Source](https://github.com/yizhongw/self-instruct)

2.  **"Enhancing chat language models by scaling high-quality instructional conversations"**
   
   *Ding, Ning, et al.* EMNLP 2023. [[Paper](https://aclanthology.org/2023.emnlp-main.183/)]

3.  **"Baize: An open-source chat model with parameter-efficient tuning on selfchat data"**
   
   *Xu, Canwen, et al.* EMNLP 2023. [[Paper](https://aclanthology.org/2023.emnlp-main.385/)] [Source](https://github.com/project-baize/baize-chatbot)

4.  **"Magpie: Alignment data synthesis from scratch by prompting aligned llms with nothing"**
   
   *Xu, Zhangchen, et al.* ICLR 2025. [[Paper](https://arxiv.org/abs/2406.08464)] [Source](https://github.com/magpie-align/magpie)

5.  **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

6.  **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

7.  **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

8.  **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

9.  **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

10. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

11. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

12. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

13. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

14. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

15. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

16. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

17. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

18. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

19. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

20. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

21. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)

22. **"XX"**
   
   *XX* XX. [[Paper](XX)] [Source](XX)
