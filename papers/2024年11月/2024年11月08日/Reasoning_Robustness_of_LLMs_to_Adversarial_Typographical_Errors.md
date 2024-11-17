# LLMs 针对对抗性排版错误的推理稳健性

发布时间：2024年11月08日

`LLM应用` `模型评估`

> Reasoning Robustness of LLMs to Adversarial Typographical Errors

# 摘要

> 大型语言模型（LLMs）借助思维链（CoT）提示进行推理的能力令人瞩目。不过，CoT 易受用户指令左右。在此项工作中，我们探究了 LLMs 对于排版错误的推理稳健性，这类错误在用户查询中时有发生。我们设计了一种对抗性排版错误攻击（$	exttt{ATA}$）算法，它会对查询中关键单词反复采样排版错误，并选取最有可能成功攻击的编辑。结果显示，LLMs 对细微的对抗性排版变动颇为敏感。要特别指出的是，在 GSM8K 数据集上，仅 1 个字符的编辑，Mistral-7B-Instruct 的准确率就从 43.7%降至 38.6%，而 8 个字符的编辑会让性能进一步下滑至 19.2%。为将评估拓展至更大规模的闭源 LLMs，我们开发了 $	exttt{R$^2$ATA}$ 基准，用于评估模型对 $underline{R}$easoning $underline{R}$obustness to $underline{	exttt{ATA}}$ 的情况。它涵盖了通过对开源 LLMs 应用 $	exttt{ATA}$ 从三个广泛运用的推理数据集——GSM8K、BBH 和 MMLU 中衍生出的对抗性排版问题。$	exttt{R$^2$ATA}$ 具有显著的可迁移性，致使多个超大型和闭源 LLMs 的性能大幅下降。

> Large Language Models (LLMs) have demonstrated impressive capabilities in reasoning using Chain-of-Thought (CoT) prompting. However, CoT can be biased by users' instruction. In this work, we study the reasoning robustness of LLMs to typographical errors, which can naturally occur in users' queries. We design an Adversarial Typo Attack ($\texttt{ATA}$) algorithm that iteratively samples typos for words that are important to the query and selects the edit that is most likely to succeed in attacking. It shows that LLMs are sensitive to minimal adversarial typographical changes. Notably, with 1 character edit, Mistral-7B-Instruct's accuracy drops from 43.7% to 38.6% on GSM8K, while with 8 character edits the performance further drops to 19.2%. To extend our evaluation to larger and closed-source LLMs, we develop the $\texttt{R$^2$ATA}$ benchmark, which assesses models' $underline{R}$easoning $underline{R}$obustness to $underline{\texttt{ATA}}$. It includes adversarial typographical questions derived from three widely used reasoning datasets-GSM8K, BBH, and MMLU-by applying $\texttt{ATA}$ to open-source LLMs. $\texttt{R$^2$ATA}$ demonstrates remarkable transferability and causes notable performance drops across multiple super large and closed-source LLMs.

[Arxiv](https://arxiv.org/abs/2411.05345)