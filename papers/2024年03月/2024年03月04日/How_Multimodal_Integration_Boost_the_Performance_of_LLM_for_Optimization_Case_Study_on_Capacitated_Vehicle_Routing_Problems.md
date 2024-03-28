# 通过研究载量受限车辆路径问题，本文探讨了多模态集成如何显著增强大型语言模型（LLM）在优化任务中的表现。

发布时间：2024年03月04日

`LLM应用`

> How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems

# 摘要

> 近年来，LLMs在应对复杂优化难题上崭露头角，然而现存基于LLM的优化方法在面对高维问题时，仅依赖数值文本提示往往无法有效捕获决策变量间的关系。为此，我们创新性地提出运用能同时处理文本和视觉提示的多模态LLM来深化优化问题理解，并提升优化效果，这就像人类认知过程中综合各种信息源一样。我们构建了一个模仿人类解决问题流程的多模态LLM优化框架，实现了更加细腻和高效的分析。为了验证这一方法的有效性，我们对经典组合优化问题——带容量限制的车辆路径问题进行了大规模实证研究，并将结果与仅使用文本提示的LLM优化算法所得结果对比，有力证明了我们的多模态方法具有明显优势。

> Recently, large language models (LLMs) have notably positioned them as capable tools for addressing complex optimization challenges. Despite this recognition, a predominant limitation of existing LLM-based optimization methods is their struggle to capture the relationships among decision variables when relying exclusively on numerical text prompts, especially in high-dimensional problems. Keeping this in mind, we first propose to enhance the optimization performance using multimodal LLM capable of processing both textual and visual prompts for deeper insights of the processed optimization problem. This integration allows for a more comprehensive understanding of optimization problems, akin to human cognitive processes. We have developed a multimodal LLM-based optimization framework that simulates human problem-solving workflows, thereby offering a more nuanced and effective analysis. The efficacy of this method is evaluated through extensive empirical studies focused on a well-known combinatorial optimization problem, i.e., capacitated vehicle routing problem. The results are compared against those obtained from the LLM-based optimization algorithms that rely solely on textual prompts, demonstrating the significant advantages of our multimodal approach.

[Arxiv](https://arxiv.org/abs/2403.01757)