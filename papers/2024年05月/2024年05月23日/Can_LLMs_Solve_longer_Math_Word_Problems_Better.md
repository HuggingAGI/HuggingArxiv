# 大型语言模型是否在解决更长的数学文字问题上表现更佳？

发布时间：2024年05月23日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在解决复杂数学文字问题（MWPs）中的应用能力，特别是在处理长篇叙述的数学问题时的表现。论文引入了上下文长度泛化性（CoLeG）这一概念，并针对不同类型的LLMs提出了改进措施。这些内容主要关注LLMs在实际应用中的性能和改进，因此属于LLM应用分类。` `人工智能`

> Can LLMs Solve longer Math Word Problems Better?

# 摘要

> 数学文字问题（MWPs）是评估大型语言模型（LLMs）能力的关键，但现有研究多聚焦于上下文简洁的问题。实际上，现实世界的数学问题往往背景复杂，因此LLMs解决长MWPs的能力对其应用至关重要，但这一领域尚未得到充分研究。本研究首次探讨了LLMs的上下文长度泛化性（CoLeG），即其解决长MWPs的能力，并引入了包含长篇叙述的扩展学校数学（E-GSM）问题集。我们提出了两个新指标来评估LLMs的效能和韧性，并发现无论是专有还是开源LLMs，在CoLeG方面普遍存在不足。为此，我们针对不同类型的LLMs提出了针对性的改进措施：专有LLMs采用新的教学提示以减少长上下文的影响，而开源LLMs则通过数据增强任务提升CoLeG。研究结果不仅在E-GSM上显示出性能提升，还在多个其他MWP基准上展现了泛化性。这些发现为未来LLMs在复杂实际应用中的研究提供了方向，为当前挑战提供了实用解决方案，并为进一步探索模型泛化性和训练方法打开了新的大门。

> Math Word Problems (MWPs) are crucial for evaluating the capability of Large Language Models (LLMs), with current research primarily focusing on questions with concise contexts. However, as real-world math problems often involve complex circumstances, LLMs' ability to solve long MWPs is vital for their applications in these scenarios, yet remains under-explored. This study pioneers the exploration of Context Length Generalizability (CoLeG), the ability of LLMs to solve long MWPs. We introduce Extended Grade-School Math (E-GSM), a collection of MWPs with lengthy narratives. Two novel metrics are proposed to assess the efficacy and resilience of LLMs in solving these problems. Our examination of existing zero-shot prompting techniques and both proprietary and open-source LLMs reveals a general deficiency in CoLeG. To alleviate these challenges, we propose distinct approaches for different categories of LLMs. For proprietary LLMs, a new instructional prompt is proposed to mitigate the influence of long context. For open-source LLMs, a new data augmentation task is developed to improve CoLeG. Our comprehensive results demonstrate the effectiveness of our proposed methods, showing not only improved performance on E-GSM but also generalizability across several other MWP benchmarks. Our findings pave the way for future research in employing LLMs for complex, real-world applications, offering practical solutions to current limitations and opening avenues for further exploration of model generalizability and training methodologies.

[Arxiv](https://arxiv.org/abs/2405.14804)