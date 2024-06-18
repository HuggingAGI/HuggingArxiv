# “未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象

发布时间：2024年06月17日

`LLM应用

这篇论文关注的是大型语言模型（LLMs）的安全性问题，特别是“越狱”现象，即恶意提示导致模型产生有害内容的情况。论文提出了一个新的评估基准（BabyBLUE），旨在更准确地评估和识别真正的越狱风险，并检测越狱中的幻觉现象。这表明论文主要集中在LLM的实际应用和安全性评估上，而不是理论研究或Agent的设计与应用，也不是关于检索增强生成（RAG）的具体研究。因此，将其归类为LLM应用是合适的。` `人工智能安全` `模型评估`

> "Not Aligned" is Not "Malicious": Being Careful about Hallucinations of Large Language Models' Jailbreak

# 摘要

> "越狱"现象对大型语言模型（LLMs）的安全性构成重大威胁，它发生在恶意提示导致模型产生有害内容时，引发了对模型可靠性的担忧。因此，准确评估越狱风险对于制定应对策略至关重要。我们的研究发现，当前评估中识别的许多越狱案例实际上可能是误判，即错误地将某些输出视为安全漏洞。这表明，一些看似的漏洞可能并非真实威胁，暗示我们需要更精准的红队测试基准。为此，我们推出了可靠性越狱幻觉评估基准（BabyBLUE），它不仅强化了现有越狱评估框架，确保识别出真正有害的指令，还新增了一个数据集，专门用于检测和评估越狱中的幻觉现象，以更准确地衡量越狱LLM输出对社会的潜在危害。

> "Jailbreak" is a major safety concern of Large Language Models (LLMs), which occurs when malicious prompts lead LLMs to produce harmful outputs, raising issues about the reliability and safety of LLMs. Therefore, an effective evaluation of jailbreaks is very crucial to develop its mitigation strategies. However, our research reveals that many jailbreaks identified by current evaluations may actually be hallucinations-erroneous outputs that are mistaken for genuine safety breaches. This finding suggests that some perceived vulnerabilities might not represent actual threats, indicating a need for more precise red teaming benchmarks. To address this problem, we propose the $\textbf{B}$enchmark for reli$\textbf{AB}$ilit$\textbf{Y}$ and jail$\textbf{B}$reak ha$\textbf{L}$l$\textbf{U}$cination $\textbf{E}$valuation (BabyBLUE). BabyBLUE introduces a specialized validation framework including various evaluators to enhance existing jailbreak benchmarks, ensuring outputs are useful malicious instructions. Additionally, BabyBLUE presents a new dataset as an augmentation to the existing red teaming benchmarks, specifically addressing hallucinations in jailbreaks, aiming to evaluate the true potential of jailbroken LLM outputs to cause harm to human society.

![“未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象](../../../paper_images/2406.11668/showcase.png)

![“未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象](../../../paper_images/2406.11668/x1.png)

![“未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象](../../../paper_images/2406.11668/pipeline.png)

![“未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象](../../../paper_images/2406.11668/x2.png)

![“未对齐”不等于“恶意”：警惕大型语言模型越狱中的幻觉现象](../../../paper_images/2406.11668/x3.png)

[Arxiv](https://arxiv.org/abs/2406.11668)