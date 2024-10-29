# LongReward：利用人工智能反馈改进长上下文大型语言模型

发布时间：2024年10月28日

`LLM应用` `语言模型`

> LongReward: Improving Long-context Large Language Models with AI Feedback

# 摘要

> 尽管在开发长上下文大型语言模型（LLM）方面已经取得了显著的进展，但用于监督微调（SFT）的 LLM 合成数据的质量受损往往会影响 SFT 模型的长上下文性能，并导致内在的局限性。原则上，具有适当奖励信号的强化学习（RL）可以进一步增强模型的能力。然而，如何在长上下文场景中获得可靠的奖励仍未被探索。为此，我们提出了 LongReward，这是一种新颖的方法，利用现成的 LLM 从四个人类重视的维度为长上下文模型的响应提供奖励：有用性、逻辑性、忠实性和完整性，每个维度都有精心设计的评估管道。通过将 LongReward 和离线 RL 算法 DPO 相结合，我们能够有效地改进长上下文 SFT 模型。我们的实验表明，LongReward 不仅显著提高了模型的长上下文性能，而且增强了它们遵循短指令的能力。我们还发现，带有 LongReward 的长上下文 DPO 和传统的短上下文 DPO 可以一起使用，而不会损害任何一方的性能。

> Though significant advancements have been achieved in developing long-context large language models (LLMs), the compromised quality of LLM-synthesized data for supervised fine-tuning (SFT) often affects the long-context performance of SFT models and leads to inherent limitations. In principle, reinforcement learning (RL) with appropriate reward signals can further enhance models' capacities. However, how to obtain reliable rewards in long-context scenarios remains unexplored. To this end, we propose LongReward, a novel method that utilizes an off-the-shelf LLM to provide rewards for long-context model responses from four human-valued dimensions: helpfulness, logicality, faithfulness, and completeness, each with a carefully designed assessment pipeline. By combining LongReward and offline RL algorithm DPO, we are able to effectively improve long-context SFT models. Our experiments indicate that LongReward not only significantly improves models' long-context performance but also enhances their ability to follow short instructions. We also find that long-context DPO with LongReward and conventional short-context DPO can be used together without hurting either one's performance.

[Arxiv](https://arxiv.org/abs/2410.21252)