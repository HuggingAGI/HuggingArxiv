# 图链思考：借助图谱推理，提升大型语言模型的智能水平。

发布时间：2024年04月10日

`LLM应用` `学术研究` `图数据增强`

> Graph Chain-of-Thought: Augmenting Large Language Models by Reasoning on Graphs

# 摘要

> 尽管大型语言模型（LLMs）展现出卓越的性能，但在处理知识密集型任务时，它们常常会“幻觉”。为了解决这一问题，先前的研究建议通过整合外部知识库中的文本单元来增强LLMs。然而，在众多领域，文本之间存在着错综复杂的联系（比如，学术文章通过引用和合著关系在文献图中相互串联），构成了一个文本属性图。这类图中的知识不仅蕴含于单个文本或节点，还体现在它们之间的联系上。为了推动利用图数据增强LLMs的研究，我们手工打造了一个名为GRBench的图推理基准数据集，内含1740个问题，这些问题都能借助10个专业领域图的知识来解答。接着，我们提出了一个名为图链式思维（Graph-CoT）的框架，通过激励LLMs对图数据进行迭代推理，实现了用图数据来增强LLMs的目的。Graph-CoT的每一轮迭代由三个子步骤组成：LLM推理、LLM与图的互动以及图的执行。我们在GRBench数据集上，基于三种不同的LLM架构进行了全面实验，结果表明Graph-CoT的性能始终超越了基准水平。相关代码已在https://github.com/PeterGriffinJin/Graph-CoT上公开。

> Large language models (LLMs), while exhibiting exceptional performance, suffer from hallucinations, especially on knowledge-intensive tasks. Existing works propose to augment LLMs with individual text units retrieved from external knowledge corpora to alleviate the issue. However, in many domains, texts are interconnected (e.g., academic papers in a bibliographic graph are linked by citations and co-authorships) which form a (text-attributed) graph. The knowledge in such graphs is encoded not only in single texts/nodes but also in their associated connections. To facilitate the research of augmenting LLMs with graphs, we manually construct a Graph Reasoning Benchmark dataset called GRBench, containing 1,740 questions that can be answered with the knowledge from 10 domain graphs. Then, we propose a simple and effective framework called Graph Chain-of-thought (Graph-CoT) to augment LLMs with graphs by encouraging LLMs to reason on the graph iteratively. Each Graph-CoT iteration consists of three sub-steps: LLM reasoning, LLM-graph interaction, and graph execution. We conduct systematic experiments with three LLM backbones on GRBench, where Graph-CoT outperforms the baselines consistently. The code is available at https://github.com/PeterGriffinJin/Graph-CoT.

[Arxiv](https://arxiv.org/abs/2404.07103)