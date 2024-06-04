# 探究逻辑推理在 LLMs 中的应用：工具选择的重要性

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）与不同符号求解器结合在逻辑推理任务上的性能比较。研究者们通过实验将LLMs与Z3、Pyke和Prover9三种符号求解器结合，并在特定的逻辑推理数据集上进行了测试。这种研究属于LLM在特定应用场景下的性能优化和比较，因此应归类为LLM应用。` `人工智能` `逻辑推理`

> A Closer Look at Logical Reasoning with LLMs: The Choice of Tool Matters

# 摘要

> 逻辑推理是人类认知的基石，而大型语言模型（LLMs）在解决此类任务上已展现出潜力。为了进一步提升这一能力，研究者们尝试将LLMs与多种符号求解器结合，采用不同的技术和方法。尽管某些组合在特定数据集上表现优异，但其他组合则不尽如人意。目前，我们还不清楚这种性能差异是源于所用的方法还是特定的符号求解器。因此，我们缺乏对这些符号求解器如何影响LLM逻辑推理能力的一致性比较。通过实验，我们将LLMs与Z3、Pyke和Prover9三种符号求解器结合，并在ProofWriter、PrOntoQA和FOLIO三个逻辑推理数据集上进行了性能比较。结果显示，与LLMs结合时，Pyke的性能明显落后于Prover9和Z3。尽管Z3的整体准确性略高，但Prover9能处理更多问题。

> Logical reasoning serves as a cornerstone for human cognition. Recently, the emergence of Large Language Models (LLMs) has demonstrated promising progress in solving logical reasoning tasks effectively. To improve this capability, recent studies have delved into integrating LLMs with various symbolic solvers using diverse techniques and methodologies. While some combinations excel on specific datasets, others fall short. However, it remains unclear whether the variance in performance stems from the methodologies employed or the specific symbolic solvers utilized. Therefore, there is a lack of consistent comparison between symbolic solvers and how they influence LLM's logical reasoning ability. We perform experiments on LLMs integrated with 3 symbolic solvers: Z3, Pyke, and Prover9, and compare their performance on 3 logical reasoning datasets: ProofWriter, PrOntoQA, and FOLIO. Our findings indicate that when combined with LLMs Pyke's performance is significantly inferior to that of Prover9 and Z3. Z3's overall accuracy performance slightly surpasses Prover9, but Prover9 could execute more questions.

[Arxiv](https://arxiv.org/abs/2406.00284)