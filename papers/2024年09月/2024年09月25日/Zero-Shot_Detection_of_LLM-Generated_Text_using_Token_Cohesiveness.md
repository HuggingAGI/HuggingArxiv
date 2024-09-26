# 利用 Token 内聚性实现 LLM 生成文本的零-Shot 检测

发布时间：2024年09月25日

`LLM应用` `网络安全`

> Zero-Shot Detection of LLM-Generated Text using Token Cohesiveness

# 摘要

> 随着大型语言模型（LLM）的能力和应用范围不断扩大，自动检测 LLM 生成文本的需求日益凸显。零-shot 检测器因其无需训练的特性而备受关注并取得了显著成功。本文中，我们发现了一个新特征——token 内聚性，它对零-shot 检测极为有用。实验表明，LLM 生成的文本比人类书写的文本具有更高的 token 内聚性。基于此，我们提出了 TOCSIN，一种利用 token 内聚性作为即插即用模块的双通道检测范式，以提升现有零-shot 检测器的性能。TOCSIN 仅需几轮随机 token 删除和语义差异测量，特别适用于生成模型不可访问的实际黑箱场景。在多个数据集和评估设置上对四种最先进检测器的广泛实验，验证了该方法的有效性和广泛适用性。代码已开源：\url{https://github.com/Shixuan-Ma/TOCSIN}。

> The increasing capability and widespread usage of large language models (LLMs) highlight the desirability of automatic detection of LLM-generated text. Zero-shot detectors, due to their training-free nature, have received considerable attention and notable success. In this paper, we identify a new feature, token cohesiveness, that is useful for zero-shot detection, and we demonstrate that LLM-generated text tends to exhibit higher token cohesiveness than human-written text. Based on this observation, we devise TOCSIN, a generic dual-channel detection paradigm that uses token cohesiveness as a plug-and-play module to improve existing zero-shot detectors. To calculate token cohesiveness, TOCSIN only requires a few rounds of random token deletion and semantic difference measurement, making it particularly suitable for a practical black-box setting where the source model used for generation is not accessible. Extensive experiments with four state-of-the-art base detectors on various datasets, source models, and evaluation settings demonstrate the effectiveness and generality of the proposed approach. Code available at: \url{https://github.com/Shixuan-Ma/TOCSIN}.

[Arxiv](https://arxiv.org/abs/2409.16914)