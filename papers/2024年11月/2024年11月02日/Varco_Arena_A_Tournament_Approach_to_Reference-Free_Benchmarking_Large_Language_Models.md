# Varco Arena：一种针对大型语言模型进行无参考基准测试的竞赛式方法

发布时间：2024年11月02日

`LLM应用` `语言模型` `基准测试`

> Varco Arena: A Tournament Approach to Reference-Free Benchmarking Large Language Models

# 摘要

> 大型语言模型（LLMs）发展迅猛，这就迫切需要强有力的评估方法。当下的基准测试手段往往是把模型输出和预先设定的提示及参考输出作对比。依赖预先设定的参考输出，不利于基准灵活适应LLMs快速演进的能力，所以需要定期筹备新的基准。为了跟上LLMs能力的快速发展，我们提出了一种更灵活的基准测试方法。我们的方法——	extit{	extbf{Varco Arena}}，以竞赛形式为LLMs提供了无参考的基准测试。	extit{	extbf{Varco Arena}}直接对比各种提示下的LLM输出，通过单淘汰竞赛结构确定模型排名。这种直接的两两比较有两大关键优势：（1）直接比较，不受参考文本的干扰，能更有效地给竞争的LLMs排序，得出更可靠的排名；（2）无参考的基准测试方式，由于无需高质量参考，在更新基准提示时更具灵活性。我们的实证结果有模拟实验支撑，表明	extit{	extbf{Varco Arena}}竞赛方法与当前用于LLMs基准测试的Elo模型更契合。这种契合度通过斯皮尔曼相关性来衡量，相比使用参考输出作为比较	extit{锚点}的当前基准测试实践有了改进。

> The rapid advancement of Large Language Models (LLMs) necessitates robust evaluation methodologies. Current benchmarking approaches often rely on comparing model outputs against predefined prompts and reference outputs. Relying on predefined reference outputs hinders flexible adaptation of benchmarks to the rapidly evolving capabilities of LLMs. This limitation necessitates periodic efforts to prepare new benchmarks. To keep pace with rapidly evolving LLM capabilities, we propose a more flexible benchmarking approach. Our method, \textit{\textbf{Varco Arena}}, provides reference-free benchmarking of LLMs in tournament style. \textit{\textbf{Varco Arena}} directly compares LLM outputs across a diverse set of prompts, determining model rankings through a single-elimination tournament structure. This direct pairwise comparison offers two key advantages: (1) Direct comparison, unmediated by reference text, more effectively orders competing LLMs, resulting in more reliable rankings, and (2) reference-free approach to benchmarking adds flexibility in updating benchmark prompts by eliminating the need for quality references. Our empirical results, supported by simulation experiments, demonstrate that the \textit{\textbf{Varco Arena}} tournament approach aligns better with the current Elo model for benchmarking LLMs. The alignment is measured in terms of Spearman correlation, showing improvement over current practice of benchmarking that use reference outputs as comparison \textit{anchor}s.

[Arxiv](https://arxiv.org/abs/2411.01281)