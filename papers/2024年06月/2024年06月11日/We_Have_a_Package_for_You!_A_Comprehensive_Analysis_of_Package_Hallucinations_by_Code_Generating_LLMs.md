# 您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。

发布时间：2024年06月11日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在代码生成过程中产生的“包幻觉”问题，这是一种新型的软件供应链威胁。论文通过实验评估了不同编程语言和设置下的包幻觉现象，并探讨了如何通过不同的模型配置和缓解策略来减少这一问题。虽然论文中提到了RAG（Retrieval-Augmented Generation）作为一种缓解策略，但整体研究重点在于LLMs的应用层面，特别是在软件开发和供应链安全方面的应用，因此归类为LLM应用。` `软件供应链` `网络安全`

> We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs

# 摘要

> Python和JavaScript等流行编程语言对集中包仓库和开源软件的依赖，加上代码生成大型语言模型（LLMs）的兴起，催生了一种新型软件供应链威胁：包幻觉。这种幻觉源自LLMs生成代码时的事实冲突错误，构成了一种新颖的包混淆攻击，严重威胁软件供应链的完整性。本文深入评估了不同编程语言、设置和参数下的包幻觉，探讨了LLMs配置如何影响错误包推荐生成，并揭示了其根本原因。通过分析16种模型在两种语言和两个数据集上生成的576,000个代码样本，我们发现19.7%的包存在幻觉，其中包括205,474个独特的幻觉包名，凸显了这一威胁的广泛性和严重性。我们还测试了基于RAG、自我检测反馈和监督微调的缓解策略，有效降低了幻觉率，但研究表明，包幻觉是一个持续且系统性的问题，对LLMs的代码生成能力构成了重大挑战。

> The reliance of popular programming languages such as Python and JavaScript on centralized package repositories and open-source software, combined with the emergence of code-generating Large Language Models (LLMs), has created a new type of threat to the software supply chain: package hallucinations. These hallucinations, which arise from fact-conflicting errors when generating code using LLMs, represent a novel form of package confusion attack that poses a critical threat to the integrity of the software supply chain. This paper conducts a rigorous and comprehensive evaluation of package hallucinations across different programming languages, settings, and parameters, exploring how different configurations of LLMs affect the likelihood of generating erroneous package recommendations and identifying the root causes of this phenomena. Using 16 different popular code generation models, across two programming languages and two unique prompt datasets, we collect 576,000 code samples which we analyze for package hallucinations. Our findings reveal that 19.7% of generated packages across all the tested LLMs are hallucinated, including a staggering 205,474 unique examples of hallucinated package names, further underscoring the severity and pervasiveness of this threat. We also implemented and evaluated mitigation strategies based on Retrieval Augmented Generation (RAG), self-detected feedback, and supervised fine-tuning. These techniques demonstrably reduced package hallucinations, with hallucination rates for one model dropping below 3%. While the mitigation efforts were effective in reducing hallucination rates, our study reveals that package hallucinations are a systemic and persistent phenomenon that pose a significant challenge for code generating LLMs.

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x1.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x2.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x3.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x4.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x5.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x6.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x7.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x8.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x9.png)

![您的专属“包裹”已送达！深入剖析大型语言模型在代码生成中产生的包幻觉现象。](../../../paper_images/2406.10279/x10.png)

[Arxiv](https://arxiv.org/abs/2406.10279)