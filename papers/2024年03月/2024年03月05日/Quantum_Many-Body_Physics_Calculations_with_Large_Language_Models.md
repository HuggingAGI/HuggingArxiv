# [借助大型语言模型探索量子多体物理问题的计算解决之道]

发布时间：2024年03月05日

`LLM应用`

> Quantum Many-Body Physics Calculations with Large Language Models

> LLMs在跨学科执行复杂任务方面展现出了卓越的能力，尤其在引导下可精确进行理论物理领域的关键计算。聚焦于量子物理中广泛应用的哈特里-福克方法，我们设计了精巧的提示，使LLMs能够分步解析并推导出近似哈密顿量及配套自洽方程。我们采用多步骤模板法，将复杂的计算流程标准化，并预留位置填写具体问题信息，以此运用GPT-4处理过去十年内15篇研究论文的关键计算。实验显示，经过对中间步骤校正后，GPT-4在13例中成功推导出正确的哈特里-福克哈密顿量，仅有2例存在细微误差，各步骤执行的平均得分高达87.5分（满分100）。这些计算技巧相当于量子凝聚态理论硕士研究生层次。此外，我们还借助LLMs有效解决了这一过程中两大难题：提取论文信息填充模板以及自动化评分计算步骤，两者皆取得良好成效。这一强劲表现标志着迈向大规模自动探索理论假设新算法的重要一步。

> Large language models (LLMs) have demonstrated an unprecedented ability to perform complex tasks in multiple domains, including mathematical and scientific reasoning. We demonstrate that with carefully designed prompts, LLMs can accurately carry out key calculations in research papers in theoretical physics. We focus on a broadly used approximation method in quantum physics: the Hartree-Fock method, requiring an analytic multi-step calculation deriving approximate Hamiltonian and corresponding self-consistency equations. To carry out the calculations using LLMs, we design multi-step prompt templates that break down the analytic calculation into standardized steps with placeholders for problem-specific information. We evaluate GPT-4's performance in executing the calculation for 15 research papers from the past decade, demonstrating that, with correction of intermediate steps, it can correctly derive the final Hartree-Fock Hamiltonian in 13 cases and makes minor errors in 2 cases. Aggregating across all research papers, we find an average score of 87.5 (out of 100) on the execution of individual calculation steps. Overall, the requisite skill for doing these calculations is at the graduate level in quantum condensed matter theory. We further use LLMs to mitigate the two primary bottlenecks in this evaluation process: (i) extracting information from papers to fill in templates and (ii) automatic scoring of the calculation steps, demonstrating good results in both cases. The strong performance is the first step for developing algorithms that automatically explore theoretical hypotheses at an unprecedented scale.

[Arxiv](https://arxiv.org/abs/2403.03154)