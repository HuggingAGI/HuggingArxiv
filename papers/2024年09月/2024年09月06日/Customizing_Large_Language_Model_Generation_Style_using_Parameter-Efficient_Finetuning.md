# 通过参数高效微调，定制大型语言模型的生成风格

发布时间：2024年09月06日

`LLM应用` `写作辅助` `人工智能`

> Customizing Large Language Model Generation Style using Parameter-Efficient Finetuning

# 摘要

> 通用 LLM 在写作辅助方面应用广泛，但其固定风格未必适合所有用户。若能根据个人需求定制 LLM 的写作风格，其辅助效果将更上一层楼。本文探讨了低秩适应的参数高效微调 (PEFT) 是否能有效调整 LLM 的生成风格。我们通过 PEFT 将 LLaMA-2 定制为十位不同作者的风格，发现生成的文本在词汇、句法和表面层次上与目标作者高度一致，但在内容记忆方面仍有提升空间。这一研究揭示了 PEFT 在高效实现用户级 LLM 定制方面的巨大潜力。

> One-size-fits-all large language models (LLMs) are increasingly being used to help people with their writing. However, the style these models are trained to write in may not suit all users or use cases. LLMs would be more useful as writing assistants if their idiolect could be customized to match each user. In this paper, we explore whether parameter-efficient finetuning (PEFT) with Low-Rank Adaptation can effectively guide the style of LLM generations. We use this method to customize LLaMA-2 to ten different authors and show that the generated text has lexical, syntactic, and surface alignment with the target author but struggles with content memorization. Our findings highlight the potential of PEFT to support efficient, user-level customization of LLMs.

[Arxiv](https://arxiv.org/abs/2409.04574)