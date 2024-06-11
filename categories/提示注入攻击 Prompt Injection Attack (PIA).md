### 提示注入攻击 Prompt Injection Attack (PIA)

[TOC]

---

#### 防御

##### 列表

[2024/05] Preemptive Answer "Attacks" on Chain-of-Thought Reasoning

[2024/03] **[Defending Against Indirect Prompt Injection Attacks With Spotlighting](https://arxiv.org/abs/2403.14720)** 

---

##### 1、Preemptive Answer "Attacks" on Chain-of-Thought Reasoning

Tsinghua University

当与思维链（CoT）提示相结合时，大型语言模型（LLMs）展示了令人印象深刻的推理能力。然而，这种方法的稳健性值得进一步研究。在本文中，我们引入了一种新的场景，称为先发制人的答案，其中LLM在进行推理之前得到一个答案。这种情况可能是无意中引起的，也可能是由恶意用户通过即时注入攻击引起的。实验表明，先发制人的答案显著削弱了模型在各种CoT方法和广泛的数据集上的推理能力。为了支持推理的稳健性，我们提出了两种措施，旨在在一定程度上减轻这一问题。

---

##### 2、Defending Against Indirect Prompt Injection Attacks With Spotlighting

大型语言模型 (LLM) 虽然功能强大，但其构建和训练都是为了处理单个文本输入。在常见应用中，可以通过将多个输入连接在一起形成单个文本流来处理它们。但是，LLM 无法区分提示的哪些部分属于各种输入源。间接提示注入攻击利用此漏洞，将对抗性指令嵌入到与用户命令一起处理的不受信任的数据中。通常，LLM 会将对抗性指令误认为要遵循的用户命令，从而在更大的系统中造成安全漏洞。我们引入了spolight，这是一类提示工程技术，可用于提高 LLM 区分多个输入源的能力。关键见解是利用输入的转换来提供可靠且连续的来源信号。我们评估了聚光灯作为针对间接提示注入攻击的防御措施，并发现它是一种强大的防御措施，对底层 NLP 任务的不利影响最小。使用 GPT 系列模型，我们发现在实验中聚光灯将攻击成功率从超过 {50}% 降低到 {2}% 以下，对任务效率的影响极小。

关键词：提示注入，防御

---

#### 攻击

##### 列表

[2024/04]  **[Goal-guided Generative Prompt Injection Attack on Large Language Models](https://arxiv.org/abs/2404.07234)** 

[2024/03] **[Optimization-based Prompt Injection Attack to LLM-as-a-Judge](https://arxiv.org/abs/2403.17710)** 

[2024/03] **[Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks](https://arxiv.org/abs/2403.03792)**

[2024/03] **[Automatic and Universal Prompt Injection Attacks against Large Language Models](https://arxiv.org/abs/2403.04957)** ](https://arxiv.org/abs/2403.04957) 

[2023/11] **[Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition](https://arxiv.org/abs/2311.16119)** 

[2023/02] **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173v2)**（全面）

---

##### 3、Goal-guided Generative Prompt Injection Attack on Large Language Models

当前的大型语言模型（LLM）为大规模面向用户的自然语言任务提供了坚实的基础。大量用户可以通过用户界面轻易地注入对抗性文本或指令，从而对LLM模型的安全造成挑战。虽然目前有大量关于即时注入攻击的研究，但这些黑盒攻击大多采用启发式策略，尚不清楚这些启发式策略如何与攻击的成功率相关，从而有效提高模型鲁棒性。为了解决这个问题，我们重新定义了攻击的目标：最大化干净文本和对抗文本的条件概率之间的KL散度。进一步，我们证明当条件概率为高斯分布并给出关于x和x'的定量关系时，最大化KL散度等价于最大化干净文本和对抗文本的嵌入表示x和x'之间的马哈拉诺比斯距离。然后我们设计了一种简单有效的目标引导生成提示注入策略（G2PIA），以找到满足特定约束的注入文本以近似地达到最佳攻击效果。特别值得注意的是，我们的攻击方法是一种无查询的黑盒攻击方法，计算成本低。在七个LLM模型和四个数据集上的实验结果证明了我们的攻击方法的有效性。

关键词：对抗性攻击、即时提示注入、黑盒攻击

---

##### 4、Optimization-based Prompt Injection Attack to LLM-as-a-Judge

LLM-as-a-Judge 是一种新颖的解决方案，可以使用大型语言模型 (LLM) 评估文本信息。根据现有研究，LLM 在提供传统人工评估的有力替代方案方面表现出色。然而，这些系统对即时注入攻击的鲁棒性仍是一个悬而未决的问题。在这项工作中，我们引入了 JudgeDeceiver，这是一种针对 LLM-as-a-Judge 量身定制的新型基于优化的即时注入攻击。我们的方法制定了攻击 LLM-as-a-Judge 决策过程的精确优化目标，并利用优化算法有效地自动生成对抗序列，实现对模型评估的有针对性和有效的操纵。与手工即时注入攻击相比，我们的方法表现出卓越的有效性，对基于 LLM 的判断系统的当前安全范式构成了重大挑战。通过大量实验，我们展示了 JudgeDeceiver 在各种情况下改变决策结果的能力，突出了 LLM-as-a-Judge 系统对基于优化的即时注入攻击的脆弱性。

关键词：即时提示注入

---

##### 5、Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks

我们引入了一个名为 Neural Exec 的新型即时注入攻击。与依赖手工编写字符串的已知攻击（例如“忽略先前的指令并...”）不同，我们表明可以将执行触发器的创建概念化为可微分搜索问题，并使用基于学习的方法来自动生成它们。
我们的结果表明，有动机的对手可以伪造触发器，这些触发器不仅比当前手工编写的触发器有效得多，而且在形状、属性和功能方面也具有固有的灵活性。在这个方向上，我们表明攻击者可以设计和生成能够在多阶段预处理管道中持续存在的 Neural Exec，例如在基于检索增强生成 (RAG) 的应用程序的情况下。更重要的是，我们的研究结果表明，攻击者可以生成在形式和形状上与任何已知攻击有明显偏差的触发器，从而避开现有的基于黑名单的检测和清理方法。

关键词：提示注入、RAG

---

##### 6、Automatic and Universal Prompt Injection Attacks against Large Language Models

大型语言模型 (LLM) 擅长处理和生成人类语言，这得益于它们能够解释和遵循指令。然而，它们的能力可以通过即时注入攻击来利用。这些攻击操纵 LLM 集成应用程序，使其产生与攻击者注入的内容一致的响应，偏离用户的实际请求。这些攻击带来的巨大风险凸显了彻底了解威胁的必要性。然而，由于此类攻击缺乏统一的目标，并且依赖于手工制作的提示，因此该领域的研究面临挑战，使对即时注入稳健性的全面评估变得复杂。我们引入了一个统一的框架来理解即时注入攻击的目标，并提出了一种基于梯度的自动方法，用于生成高效且通用的即时注入数据，即使在防御措施面前也是如此。仅使用五个训练样本（相对于测试数据的 0.3%），我们的攻击就可以实现与基线相比更出色的性能。我们的研究结果强调了基于梯度的测试的重要性，它可以避免对稳健性的高估，尤其是对于防御机制而言。

关键词：提示注入攻击、基于梯度

---

##### 7、Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition

大型语言模型 (LLM) 部署在具有直接用户参与的交互式环境中，例如聊天机器人和写作助手。这些部署容易受到提示注入和越狱（统称为提示黑客攻击）的攻击，在这种情况下，模型会被操纵以忽略其原始指令并遵循潜在的恶意指令。尽管被广泛认为是一种重大安全威胁，但关于提示黑客攻击的大规模资源和定量研究却很少。为了弥补这一缺陷，我们发起了一场全球提示黑客攻击竞赛，允许自由形式的人工输入攻击。我们针对三个最先进的 LLM 引发了 600K+ 对抗性提示。我们描述了数据集，该数据集通过经验验证了当前的 LLM 确实可以通过提示黑客攻击进行操纵。我们还提出了对抗性提示类型的全面分类本体。

---

##### 8、Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection

大型语言模型 (LLM) 越来越多地被集成到各种应用程序中。最近的 LLM 的功能可以通过自然语言提示灵活地进行调整。这使得它们容易受到有针对性的对抗性提示的影响，例如，提示注入 (PI) 攻击使攻击者能够覆盖原始指令和使用的控件。到目前为止，假设用户直接提示 LLM。但是，如果不是用户提示呢？我们认为 LLM 集成应用程序模糊了数据和指令之间的界限。我们使用间接提示注入揭示了新的攻击媒介，使对手能够远程（无需直接接口）利用 LLM 集成应用程序，方法是将提示策略性地注入可能被检索的数据中。我们从计算机安全的角度得出了一个全面的分类法，以系统地调查影响和漏洞，包括数据盗窃、蠕虫、信息生态系统污染和其他新的安全风险。我们展示了我们的攻击对现实世界系统（例如 Bing 的 GPT-4 驱动的聊天和代码完成引擎）以及基于 GPT-4 构建的合成应用程序的实际可行性。我们展示了处理检索到的提示如何充当任意代码执行、操纵应用程序的功能以及控制如何调用其他 API 以及是否调用其他 API。尽管对 LLM 的集成和依赖日益增加，但目前仍缺乏对这些新兴威胁的有效缓解措施。通过提高对这些漏洞的认识并提供有关其影响的关键见解，我们旨在促进这些强大模型的安全和负责任的部署，以及开发强大的防御措施以保护用户和系统免受潜在攻击。

关键词：间接提示注入

---

##### 9、Prompt Injection attack against LLM-integrated Applications

大型语言模型 (LLM) 以其在语言理解和生成方面的卓越能力而闻名，它们刺激了周围充满活力的应用程序生态系统。然而，它们广泛融入各种服务带来了重大的安全风险。本研究解构了对实际 LLM 集成应用程序的提示注入攻击的复杂性和影响。首先，我们对十个商业应用程序进行了探索性分析，强调了当前攻击策略在实践中的限制。在这些限制的推动下，我们随后制定了一种新颖的黑盒提示注入攻击技术 HouYi，它从传统的 Web 注入攻击中汲取灵感。HouYi 分为三个关键元素：无缝集成的预构造提示、诱导上下文分区的注入提示和旨在实现攻击目标的恶意负载。利用 HouYi，我们发现了以前未知的严重攻击结果，例如不受限制的任意 LLM 使用和简单的应用程序提示盗窃。我们在 36 个实际的 LLM 集成应用程序上部署了 HouYi，并辨别出 31 个易受提示注入影响的应用程序。 10 家供应商已验证了我们的发现，其中包括可能影响数百万用户的 Notion。我们的调查阐明了即时注入攻击的潜在风险以及可能的缓解策略。

关键词：黑盒提示注入攻击

---

#### 评估和数据集

##### 列表

[2024/03] **[Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks](https://arxiv.org/abs/2403.09832)**

 [2024/03]**[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/abs/2403.02691)**](https://arxiv.org/abs/2403.02691)

[2023/10] **[Prompt Injection Attacks and Defenses in LLM-Integrated Applications](https://arxiv.org/abs/2310.12815)**]

[2023/09] **[Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game](https://openreview.net/forum?id=fsW7wJGLBd)**

---

##### 10、Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks

大型语言模型 (LLM) 正日益成为许多自然语言处理任务（例如机器翻译）的首选基础平台，因为它们的质量通常与特定于任务的模型相当或更好，并且可以通过自然语言指令或上下文示例轻松指定任务。然而，它们的通用性使它们容易受到最终用户的破坏，最终用户可能会将指令嵌入到他们的请求中，导致模型以未经授权且可能不安全的方式运行。在这项工作中，我们研究了机器翻译任务中多个 LLM 系列的这些提示注入攻击 (PIA)，重点关注模型大小对攻击成功率的影响。我们引入了一个新的基准数据集，我们发现在用英语编写的多个语言对和注入提示中，某些条件下较大的模型可能更容易受到成功攻击，这是逆缩放现象 (McKenzie et al., 2023) 的一个实例。据我们所知，这是第一项研究多语言环境中非平凡 LLM 缩放行为的工作。

关键词：提示注入攻击，攻击成功率

---

##### 11、InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents

最近的研究将 LLM 实现为Agent，允许它们访问工具、执行操作并与外部内容（例如电子邮件或网站）交互。但是，外部内容引入了间接提示注入 (IPI) 攻击的风险，其中恶意指令嵌入在 LLM 处理的内容中，旨在操纵这些代理对用户执行有害操作。鉴于此类攻击可能造成的严重后果，建立基准来评估和减轻这些风险势在必行。
在这项工作中，我们引入了 InjecAgent，这是一个旨在评估工具集成的 LLM 代理对 IPI 攻击的脆弱性的基准。InjecAgent 包含 1,054 个测试用例，涵盖 17 种不同的用户工具和 62 种攻击者工具。我们将攻击意图分为两种主要类型：直接伤害用户和泄露私人数据。我们评估了 30 种不同的 LLM 代理，并表明代理容易受到 IPI 攻击，其中 ReAct 提示的 GPT-4 有 24% 的时间容易受到攻击。进一步研究增强设置（攻击者指令通过黑客提示得到强化），发现成功率进一步提高，几乎使 ReAct 提示的 GPT-4 攻击成功率翻了一番。我们的发现对 LLM Agent 的广泛部署提出了质疑。我们的基准测试可在此https://github.com/uiuc-kang-lab/InjecAgent上找到。

关键词：间接提示注入IPI、Agent评估、

---

##### 12、Formalizing and Benchmarking Prompt Injection Attacks and Defenses

即时注入攻击旨在将恶意指令/数据注入 LLM 集成应用程序的输入，使其产生攻击者想要的结果。现有研究仅限于案例研究。因此，文献缺乏对即时注入攻击及其防御的系统理解。我们旨在通过这项工作弥补这一空白。特别是，我们提出了一个框架来形式化即时注入攻击。现有攻击是我们框架中的特殊情况。此外，基于我们的框架，我们通过结合现有攻击设计了一种新攻击。使用我们的框架，我们对 5 种即时注入攻击和 10 种防御进行了系统评估，其中包括 10 个 LLM 和 7 个任务。我们的工作为定量评估未来的即时注入攻击和防御提供了一个通用基准。为了促进对该主题的研究，我们在 https://github.com/liu00222/Open-Prompt-Injection 上公开了我们的平台。

关键词：即时注入攻击框架

---

##### 13、Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game

虽然大型语言模型 (LLM) 在实际应用中的使用越来越多，但它们仍然容易受到提示注入攻击：恶意的第三方提示会破坏系统设计者的意图。为了帮助研究人员研究这个问题，我们提供了一个包含超过 126,000 个提示注入攻击和 46,000 个基于提示的“防御”提示注入的数据集，所有这些都是由名为 Tensor Trust 的在线游戏的玩家创建的。据我们所知，这是目前最大的人工生成的指令跟踪 LLM 对抗性示例数据集。我们数据集中的攻击具有许多易于解释的结构，并揭示了 LLM 的弱点。我们还使用该数据集创建了抵抗两种提示注入的基准，我们将其称为提示提取和提示劫持。我们的基准测试结果表明，许多模型都容易受到 Tensor Trust 数据集中的攻击策略的攻击。此外，我们表明，数据集中的一些攻击策略可以推广到已部署的基于 LLM 的应用程序，即使它们与游戏的约束条件非常不同。我们在https://tensortrust.ai/paper/发布所有数据和源代码

关键词：指令对抗数据集



