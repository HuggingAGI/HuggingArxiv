# 语言模型中不确定性估计的语义多样性语言生成

发布时间：2024年06月06日

`LLM理论

理由：该论文摘要讨论了大型语言模型（LLMs）在生成文本时出现幻觉的问题，并提出了一种名为语义多样性语言生成（SDLG）的技术来量化和处理这种不确定性。这涉及到对LLMs内部机制的深入理解和改进，特别是在处理预测不确定性方面的理论探讨。因此，这项工作更偏向于LLM的理论研究，而不是具体的应用、Agent设计或RAG（检索增强生成）技术。` `问答系统`

> Semantically Diverse Language Generation for Uncertainty Estimation in Language Models

# 摘要

> 大型语言模型（LLMs）在生成文本时易出现幻觉，这使得它们在社会和工业应用中变得不可靠。目前，LLMs通过预测并添加文本令牌来自回归地生成内容。当LLMs对下一个文本令牌的语义含义不确定时，幻觉便可能产生。因此，幻觉被认为是源于预测不确定性。我们提出的语义多样性语言生成（SDLG）技术，旨在量化LLMs中的这种不确定性。SDLG促使LLMs为初始文本生成多种语义上可能的替代方案，从而精确衡量了语义上的偶然性不确定性，并判断初始文本是否可能为幻觉。在问答任务的实验中，SDLG不仅持续超越现有方法，而且在计算效率上达到了最高水平，为LLMs中的不确定性估计树立了新标杆。

> Large language models (LLMs) can suffer from hallucinations when generating text. These hallucinations impede various applications in society and industry by making LLMs untrustworthy. Current LLMs generate text in an autoregressive fashion by predicting and appending text tokens. When an LLM is uncertain about the semantic meaning of the next tokens to generate, it is likely to start hallucinating. Thus, it has been suggested that hallucinations stem from predictive uncertainty. We introduce Semantically Diverse Language Generation (SDLG) to quantify predictive uncertainty in LLMs. SDLG steers the LLM to generate semantically diverse yet likely alternatives for an initially generated text. This approach provides a precise measure of aleatoric semantic uncertainty, detecting whether the initial text is likely to be hallucinated. Experiments on question-answering tasks demonstrate that SDLG consistently outperforms existing methods while being the most computationally efficient, setting a new standard for uncertainty estimation in LLMs.

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x1.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x2.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x3.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x4.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x5.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x6.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x7.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x8.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x9.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x10.png)

![语言模型中不确定性估计的语义多样性语言生成](../../../paper_images/2406.04306/x11.png)

[Arxiv](https://arxiv.org/abs/2406.04306)