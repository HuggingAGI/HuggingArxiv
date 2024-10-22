# 机器遗忘与检索增强生成 (RAG) 相遇时，是保守秘密还是遗忘知识？

发布时间：2024年10月19日

`RAG` `人工智能` `数据隐私`

> When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?

# 摘要

> ChatGPT 和 Gemini 等大型语言模型展示了其强大的自然语言生成能力，但训练过程中可能无意中学习并保留敏感信息和有害内容，引发伦理和法律问题。为此，我们提出了一种基于检索增强生成 (RAG) 技术的轻量级遗忘框架，通过修改 RAG 的外部知识库来模拟遗忘效果，而无需直接与 LLM 交互。我们将遗忘知识的构建视为约束优化问题，推导出两个关键组成部分，确保基于 RAG 的遗忘方法的有效性。这种方法特别适用于现有的遗忘方法难以处理的闭源 LLM。通过在多种模型上的广泛实验，我们的框架展示了在有效性、普遍性、无害性、简单性和鲁棒性方面的优势，并可扩展到多模态大型语言模型和基于 LLM 的代理。

> The deployment of large language models (LLMs) like ChatGPT and Gemini has shown their powerful natural language generation capabilities. However, these models can inadvertently learn and retain sensitive information and harmful content during training, raising significant ethical and legal concerns. To address these issues, machine unlearning has been introduced as a potential solution. While existing unlearning methods take into account the specific characteristics of LLMs, they often suffer from high computational demands, limited applicability, or the risk of catastrophic forgetting. To address these limitations, we propose a lightweight unlearning framework based on Retrieval-Augmented Generation (RAG) technology. By modifying the external knowledge base of RAG, we simulate the effects of forgetting without directly interacting with the unlearned LLM. We approach the construction of unlearned knowledge as a constrained optimization problem, deriving two key components that underpin the effectiveness of RAG-based unlearning. This RAG-based approach is particularly effective for closed-source LLMs, where existing unlearning methods often fail. We evaluate our framework through extensive experiments on both open-source and closed-source models, including ChatGPT, Gemini, Llama-2-7b-chat-hf, and PaLM 2. The results demonstrate that our approach meets five key unlearning criteria: effectiveness, universality, harmlessness, simplicity, and robustness. Meanwhile, this approach can extend to multimodal large language models and LLM-based agents.

[Arxiv](https://arxiv.org/abs/2410.15267)