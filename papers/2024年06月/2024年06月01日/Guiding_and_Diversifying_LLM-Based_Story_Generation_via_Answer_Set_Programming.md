# 利用答案集编程，引导并丰富大型语言模型生成故事的多样性

发布时间：2024年06月01日

`Agent

理由：这篇论文探讨了如何结合大型语言模型（LLM）和符号方法（如故事规划）来提高故事创作的多样性。通过使用答案集编程（ASP）作为一种高层次、抽象的符号规范来引导LLM进行故事创作，该研究展示了如何通过智能代理（Agent）的方式来增强LLM的应用能力。这种方法涉及创建一个能够理解和执行复杂指令的智能系统，这是Agent研究的核心内容。因此，这篇论文更适合归类于Agent分类。` `文学创作` `人工智能`

> Guiding and Diversifying LLM-Based Story Generation via Answer Set Programming

# 摘要

> 指令调优的LLMs虽能应答开放请求编织故事，但故事的多样性却显得捉襟见肘。相比之下，传统的符号方法（如故事规划）虽能勾勒出更为丰富多彩的情节轮廓，却受限于一套固定的角色动作模板。我们能否将两者的优势融合，同时规避各自的短板？我们的提议是，利用一种高层次、抽象的符号规范——通过答案集编程（ASP）实现——来引导并丰富基于LLM的故事创作。通过语义相似性分析，我们证实了这一方法能产出更为多元的故事，而代码摘录则展示了ASP在生成大纲时的紧凑与灵活，远胜于传统的叙事规划。

> Instruction-tuned large language models (LLMs) are capable of generating stories in response to open-ended user requests, but the resulting stories tend to be limited in their diversity. Older, symbolic approaches to story generation (such as planning) can generate substantially more diverse plot outlines, but are limited to producing stories that recombine a fixed set of hand-engineered character action templates. Can we combine the strengths of these approaches while mitigating their weaknesses? We propose to do so by using a higher-level and more abstract symbolic specification of high-level story structure -- implemented via answer set programming (ASP) -- to guide and diversify LLM-based story generation. Via semantic similarity analysis, we demonstrate that our approach produces more diverse stories than an unguided LLM, and via code excerpts, we demonstrate the improved compactness and flexibility of ASP-based outline generation over full-fledged narrative planning.

![利用答案集编程，引导并丰富大型语言模型生成故事的多样性](../../../paper_images/2406.00554/outlines.jpeg)

![利用答案集编程，引导并丰富大型语言模型生成故事的多样性](../../../paper_images/2406.00554/overall.jpeg)

![利用答案集编程，引导并丰富大型语言模型生成故事的多样性](../../../paper_images/2406.00554/homogeneity.png)

[Arxiv](https://arxiv.org/abs/2406.00554)