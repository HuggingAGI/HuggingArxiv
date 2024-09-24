# 大型语言模型助力证明自动化

发布时间：2024年09月21日

`LLM应用` `软件工程` `人工智能`

> Proof Automation with Large Language Models

# 摘要

> 交互式定理证明器如 Coq 是确保软件正确性的利器，但使用它们需要大量人工和专业知识。尽管大型语言模型 (LLM) 在生成自然语言证明方面表现出色，但在生成正式证明方面却力不从心。我们通过分析 GPT-3.5 的 520 个错误，发现其在高级结构上表现尚可，但在细节处理上频频出错。为此，我们提出了 PALM，一种“生成-修复”方法，先让 LLM 生成初步证明，再通过符号方法逐一修复细节问题。实验表明，PALM 在 10K 定理数据集上表现优异，证明成功率提升 76.6% 至 180.4%，并额外证明了 1270 个现有方法无法解决的定理。此外，PALM 在不同 LLM 间展现出良好的通用性。

> Interactive theorem provers such as Coq are powerful tools to formally guarantee the correctness of software. However, using these tools requires significant manual effort and expertise. While Large Language Models (LLMs) have shown promise in automatically generating informal proofs in natural language, they are less effective at generating formal proofs in interactive theorem provers. In this paper, we conduct a formative study to identify common mistakes made by LLMs when asked to generate formal proofs. By analyzing 520 proof generation errors made by GPT-3.5, we found that GPT-3.5 often identified the correct high-level structure of a proof, but struggled to get the lower-level details correct. Based on this insight, we propose PALM, a novel generate-then-repair approach that first prompts an LLM to generate an initial proof and then leverages targeted symbolic methods to iteratively repair low-level problems. We evaluate PALM on a large dataset that includes more than 10K theorems. Our results show that PALM significantly outperforms other state-of-the-art approaches, successfully proving 76.6% to 180.4% more theorems. Moreover, PALM proves 1270 theorems beyond the reach of existing approaches. We also demonstrate the generalizability of PALM across different LLMs.

[Arxiv](https://arxiv.org/abs/2409.14274)