# 探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。

发布时间：2024年04月01日

`LLM应用` `软件工程` `代码生成`

> Exploring and Evaluating Hallucinations in LLM-Powered Code Generation

# 摘要

> 随着大型语言模型（LLMs）的崛起，软件工程领域的诸多应用，尤其是代码生成，得到了显著的提升。然而，尽管 LLMs 展现出了潜力，它们却容易引发幻觉现象，即生成与用户意图不符、内部逻辑混乱或与现实知识脱节的输出，这使得 LLMs 在广泛应用中的部署变得潜在风险。目前的研究主要关注自然语言生成中的幻觉问题，而在代码生成背景下对幻觉的认识尚存在不足。为了填补这一研究空白，我们对 LLM 生成的代码进行了深入的主题分析，总结出代码中的幻觉类型，并进行了分类。我们的研究建立了一个全面的幻觉分类体系，根据代码生成中观察到的目标冲突和偏差程度，划分了五种主要的幻觉类型。我们还系统地分析了幻觉的分布情况，探讨了不同 LLMs 之间的差异及其与代码准确性的相关性。基于这些发现，我们提出了 HalluCode 基准，用于评估代码 LLMs 在识别幻觉方面的性能。通过 HalluCode 和 HumanEval 进行的实验表明，现有的 LLMs 在识别和缓解幻觉方面面临着巨大的挑战，尤其是在辨别幻觉类型方面。我们相信，这些研究成果将为未来关于幻觉评估、检测和缓解的研究提供宝贵的启示，为构建更加有效和可靠的代码生成 LLMs 奠定基础。

> The rise of Large Language Models (LLMs) has significantly advanced many applications on software engineering tasks, particularly in code generation. Despite the promising performance, LLMs are prone to generate hallucinations, which means LLMs might produce outputs that deviate from users' intent, exhibit internal inconsistencies, or misalign with the factual knowledge, making the deployment of LLMs potentially risky in a wide range of applications. Existing work mainly focuses on investing the hallucination in the domain of natural language generation (NLG), leaving a gap in understanding the types and extent of hallucinations in the context of code generation. To bridge the gap, we conducted a thematic analysis of the LLM-generated code to summarize and categorize the hallucinations present in it. Our study established a comprehensive taxonomy of hallucinations in LLM-generated code, encompassing 5 primary categories of hallucinations depending on the conflicting objectives and varying degrees of deviation observed in code generation. Furthermore, we systematically analyzed the distribution of hallucinations, exploring variations among different LLMs and their correlation with code correctness. Based on the results, we proposed HalluCode, a benchmark for evaluating the performance of code LLMs in recognizing hallucinations. Hallucination recognition and mitigation experiments with HalluCode and HumanEval show existing LLMs face great challenges in recognizing hallucinations, particularly in identifying their types, and are hardly able to mitigate hallucinations. We believe our findings will shed light on future research about hallucination evaluation, detection, and mitigation, ultimately paving the way for building more effective and reliable code LLMs in the future.

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x1.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x2.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x3.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x4.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x5.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x6.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x7.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x8.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x9.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x10.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x11.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x12.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x13.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x14.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x15.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x16.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x17.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x18.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x19.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x20.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x21.png)

![探究与评价由大型语言模型（LLM）驱动的代码生成过程中的虚构现象。](../../../paper_images/2404.00971/x22.png)

[Arxiv](https://arxiv.org/abs/2404.00971)