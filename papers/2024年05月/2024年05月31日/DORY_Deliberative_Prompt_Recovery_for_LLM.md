# DORY：大型语言模型的深思熟虑提示恢复机制

发布时间：2024年05月31日

`LLM应用

这篇论文主要关注的是在大规模语言模型（LLMs）中进行提示恢复的技术，特别是在有限输出的情况下通过分析概率不确定性来提高提示恢复的成功率。论文中提出的Deliberative PrOmpt RecoverY（DORY）技术，是一种专门用于从LLM输出中精准恢复提示的新方法。这种方法在多个LLMs和提示基准测试中展示了优越的性能，并且仅依赖单一LLM，无需外部资源或额外模型，因此属于LLM应用的范畴。` `人工智能` `隐私保护`

> DORY: Deliberative Prompt Recovery for LLM

# 摘要

> 在大规模语言模型（LLMs）中，提示恢复是理解其运作机制和解决隐私、版权等问题的关键。然而，仅推理API的流行限制了对关键输出的访问，增加了任务难度。为此，我们通过分析有限输出的概率不确定性，发现其与提示恢复成功率呈负相关。基于此，我们开发了Deliberative PrOmpt RecoverY（DORY），一种利用不确定性精准恢复提示的新技术。DORY通过从输出中构建草稿，借助提示进行优化，并依据不确定性排除干扰，实现了高效的提示恢复。在多个LLMs和提示基准测试中，DORY的表现超越了现有技术，提升了约10.82%的性能，创下了新的行业标杆。尤为重要的是，DORY仅依赖单一LLM，无需外部资源或额外模型，提供了一种经济实惠且用户友好的提示恢复方案。

> Prompt recovery in large language models (LLMs) is crucial for understanding how LLMs work and addressing concerns regarding privacy, copyright, etc. The trend towards inference-only APIs complicates this task by restricting access to essential outputs for recovery. To tackle this challenge, we extract prompt-related information from limited outputs and identify a strong(negative) correlation between output probability-based uncertainty and the success of prompt recovery. This finding led to the development of Deliberative PrOmpt RecoverY (DORY), our novel approach that leverages uncertainty to recover prompts accurately. DORY involves reconstructing drafts from outputs, refining these with hints, and filtering out noise based on uncertainty. Our evaluation across diverse LLMs and prompt benchmarks shows that DORY outperforms existing baselines, improving performance by approximately 10.82% and establishing a new state-of-the-art record in prompt recovery tasks. Significantly, DORY operates using a single LLM without any external resources or model, offering a cost-effective, user-friendly prompt recovery solution.

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x1.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x2.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x3.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x4.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x5.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x6.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x7.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x8.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x9.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x10.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x11.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x12.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x13.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x14.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x15.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/alpaca-tasks.png)

![DORY：大型语言模型的深思熟虑提示恢复机制](../../../paper_images/2405.20657/x16.png)

[Arxiv](https://arxiv.org/abs/2405.20657)