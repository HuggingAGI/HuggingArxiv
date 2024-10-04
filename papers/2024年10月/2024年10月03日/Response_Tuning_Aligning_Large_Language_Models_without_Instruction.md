# 响应调优：无指令对齐大型语言模型

发布时间：2024年10月03日

`LLM理论` `人工智能` `聊天助手`

> Response Tuning: Aligning Large Language Models without Instruction

# 摘要

> 指令调优是将预训练 LLM 转化为有用且安全的聊天助手的关键步骤。我们假设，建立适当的输出空间能充分利用预训练 LLM 的固有能力。为此，我们提出了响应调优 (RT)，专注于响应空间的监督，跳过指令条件步骤。实验显示，仅通过响应训练的 RT 模型能有效应对多样指令，且其有用性与指令调优模型相当。此外，控制响应分布能显著提升用户偏好，甚至引导模型拒绝不安全请求。这些发现强调了输出空间在模型一致性中的重要性，揭示了预训练 LLM 的巨大潜力。

> Instruction tuning-supervised fine-tuning using instruction-response pairs-is a foundational step in transitioning pre-trained Large Language Models (LLMs) into helpful and safe chat assistants. Our hypothesis is that establishing an adequate output space can enable such a transition given the capabilities inherent in pre-trained LLMs. To verify this, we propose Response Tuning (RT), which eliminates the instruction-conditioning step in instruction tuning and solely focuses on response space supervision. Our experiments demonstrate that RT models, trained only using responses, can effectively respond to a wide range of instructions and exhibit helpfulness comparable to that of their instruction-tuned counterparts. Furthermore, we observe that controlling the training response distribution can significantly improve their user preference or elicit target behaviors such as refusing assistance for unsafe queries. Our findings illuminate the role of establishing an adequate output space in alignment, highlighting the potential of the extensive inherent capabilities of pre-trained LLMs.

[Arxiv](https://arxiv.org/abs/2410.02465)