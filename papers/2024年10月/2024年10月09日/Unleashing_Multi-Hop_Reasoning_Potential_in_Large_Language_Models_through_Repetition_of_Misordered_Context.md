# 通过重复错序的上下文，激发大型语言模型中的多跳推理潜能

发布时间：2024年10月09日

`LLM应用` `人工智能` `问答系统`

> Unleashing Multi-Hop Reasoning Potential in Large Language Models through Repetition of Misordered Context

# 摘要

> 多跳推理对 LLM 来说依然是个难题，尤其是在处理上下文中的无关文档和文档位置时。我们发现，LLM 的性能还受支持文档呈现顺序的影响，即错序上下文问题。为此，我们提出了上下文重复 (CoRe) 方法，通过反复呈现上下文来优化文档顺序。实验表明，CoRe 在多跳问答任务中提升了高达 30% 的 F1 分数，在合成任务中提高了 70% 的准确率。此外，CoRe 还能缓解 LLM 的“中间迷失”问题，并与基于 CoT 推理的检索方法相辅相成。

> Multi-hop reasoning, which requires multi-step reasoning based on the supporting documents within a given context, remains challenging for large language models (LLMs). LLMs often struggle to filter out irrelevant documents within the context, and their performance is sensitive to the position of supporting documents within that context. In this paper, we identify an additional challenge: LLMs' performance is also sensitive to the order in which the supporting documents are presented. We refer to this as the misordered context problem. To address this issue, we propose a simple yet effective method called context repetition (CoRe), which involves prompting the model by repeatedly presenting the context to ensure the supporting documents are presented in the optimal order for the model. Using CoRe, we improve the F1 score by up to 30%p on multi-hop QA tasks and increase accuracy by up to 70%p on a synthetic task. Additionally, CoRe helps mitigate the well-known "lost-in-the-middle" problem in LLMs and can be effectively combined with retrieval-based approaches utilizing Chain-of-Thought (CoT) reasoning.

[Arxiv](https://arxiv.org/abs/2410.07103)