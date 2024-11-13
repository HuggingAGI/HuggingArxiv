# 大型语言模型的对抗性攻击可以归因吗？

发布时间：2024年11月12日

`LLM理论` `网络安全` `语言模型`

> Can adversarial attacks by large language models be attributed?

# 摘要

> 在对抗性环境（如网络攻击和虚假信息）中归因于大型语言模型（LLM）的输出带来了重大挑战，这些挑战可能会变得越来越重要。我们使用形式语言理论来研究这个归因问题，特别是 Gold 提出并由 Angluin 扩展的极限语言识别。通过将 LLM 的输出建模为形式语言，我们分析有限的文本样本是否能够唯一地指出来源模型。我们的结果表明，由于某些语言类别的不可识别性，在对微调模型的重叠输出的一些温和假设下，从理论上讲，不可能确定地将输出归因于特定的 LLM。当考虑到 Transformer 架构的表达能力限制时，情况也是如此。即使有直接的模型访问或全面的监控，重大的计算障碍也阻碍了归因工作。这些发现强调了迫切需要采取积极措施来减轻对抗性 LLM 使用所带来的风险，因为它们的影响在继续扩大。

> Attributing outputs from Large Language Models (LLMs) in adversarial settings-such as cyberattacks and disinformation-presents significant challenges that are likely to grow in importance. We investigate this attribution problem using formal language theory, specifically language identification in the limit as introduced by Gold and extended by Angluin. By modeling LLM outputs as formal languages, we analyze whether finite text samples can uniquely pinpoint the originating model. Our results show that due to the non-identifiability of certain language classes, under some mild assumptions about overlapping outputs from fine-tuned models it is theoretically impossible to attribute outputs to specific LLMs with certainty. This holds also when accounting for expressivity limitations of Transformer architectures. Even with direct model access or comprehensive monitoring, significant computational hurdles impede attribution efforts. These findings highlight an urgent need for proactive measures to mitigate risks posed by adversarial LLM use as their influence continues to expand.

[Arxiv](https://arxiv.org/abs/2411.08003)