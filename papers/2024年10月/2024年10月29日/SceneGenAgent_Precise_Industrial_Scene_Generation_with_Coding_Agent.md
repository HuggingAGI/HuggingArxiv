# SceneGenAgent：借助编码代理实现精准的工业场景生成

发布时间：2024年10月29日

`Agent` `制造业`

> SceneGenAgent: Precise Industrial Scene Generation with Coding Agent

# 摘要

> 工业场景的建模在工业制造模拟中极为关键。尽管大型语言模型（LLMs）在依据文本描述生成普通 3D 场景方面成果斐然，但由于工业场景对精准测量和定位有要求，用 LLMs 生成工业场景面临独特挑战，需要对空间布局进行复杂规划。为应对此挑战，我们推出了 SceneGenAgent，这是一个基于 LLM 、通过 C# 代码生成工业场景的代理。SceneGenAgent 借助结构化且可计算的格式、布局验证和迭代优化，确保了精确的布局规划，满足工业场景的定量需求。实验结果显示，由 SceneGenAgent 驱动的 LLMs 超越了原性能，在实际工业场景生成任务中成功率达 81.0%，有效满足了多数场景生成要求。为进一步提升可访问性，我们构建了 SceneInstruct 数据集，用于微调开源 LLMs 以融入 SceneGenAgent 。实验表明，在 SceneInstruct 上微调开源 LLMs 能显著提升性能，Llama3.1-70B 接近 GPT-4o 的水平。我们的代码和数据可在 https://github.com/THUDM/SceneGenAgent 获取。

> The modeling of industrial scenes is essential for simulations in industrial manufacturing. While large language models (LLMs) have shown significant progress in generating general 3D scenes from textual descriptions, generating industrial scenes with LLMs poses a unique challenge due to their demand for precise measurements and positioning, requiring complex planning over spatial arrangement. To address this challenge, we introduce SceneGenAgent, an LLM-based agent for generating industrial scenes through C# code. SceneGenAgent ensures precise layout planning through a structured and calculable format, layout verification, and iterative refinement to meet the quantitative requirements of industrial scenarios. Experiment results demonstrate that LLMs powered by SceneGenAgent exceed their original performance, reaching up to 81.0% success rate in real-world industrial scene generation tasks and effectively meeting most scene generation requirements. To further enhance accessibility, we construct SceneInstruct, a dataset designed for fine-tuning open-source LLMs to integrate into SceneGenAgent. Experiments show that fine-tuning open-source LLMs on SceneInstruct yields significant performance improvements, with Llama3.1-70B approaching the capabilities of GPT-4o. Our code and data are available at https://github.com/THUDM/SceneGenAgent .

[Arxiv](https://arxiv.org/abs/2410.21909)