# Medico：迈向多源证据融合的幻觉检测与校正

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Medico: Towards Hallucination Detection and Correction with Multi-source Evidence Fusion

# 摘要

> 众所周知，大型语言模型 (LLM) 中普遍存在幻觉现象，生成的内容虽然连贯但事实不正确，严重影响了其广泛应用。先前研究表明，LLM 可能会自信地陈述不存在的事实，而不是回答“我不知道”。因此，借助外部知识检测和纠正幻觉内容显得尤为重要。由于手动检测和纠正事实错误费时费力，开发自动端到端的幻觉检查方法势在必行。为此，我们推出了 Medico，一种多源证据融合增强的幻觉检测和纠正框架。Medico 融合多源证据，自动检测并提供判断依据，迭代修正幻觉内容。实验结果显示，Medico 在证据检索、幻觉检测和纠正方面表现优异，展现了巨大潜力。Medico 的视频演示可在 https://youtu.be/RtsO6CSesBI 观看。

> As we all know, hallucinations prevail in Large Language Models (LLMs), where the generated content is coherent but factually incorrect, which inflicts a heavy blow on the widespread application of LLMs. Previous studies have shown that LLMs could confidently state non-existent facts rather than answering ``I don't know''. Therefore, it is necessary to resort to external knowledge to detect and correct the hallucinated content. Since manual detection and correction of factual errors is labor-intensive, developing an automatic end-to-end hallucination-checking approach is indeed a needful thing. To this end, we present Medico, a Multi-source evidence fusion enhanced hallucination detection and correction framework. It fuses diverse evidence from multiple sources, detects whether the generated content contains factual errors, provides the rationale behind the judgment, and iteratively revises the hallucinated content. Experimental results on evidence retrieval (0.964 HR@5, 0.908 MRR@5), hallucination detection (0.927-0.951 F1), and hallucination correction (0.973-0.979 approval rate) manifest the great potential of Medico. A video demo of Medico can be found at https://youtu.be/RtsO6CSesBI.

[Arxiv](https://arxiv.org/abs/2410.10408)