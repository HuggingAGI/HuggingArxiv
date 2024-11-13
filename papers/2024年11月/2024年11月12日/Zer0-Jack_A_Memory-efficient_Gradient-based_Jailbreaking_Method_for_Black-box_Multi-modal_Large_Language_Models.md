# Zer0-Jack：一种用于黑箱多模态大型语言模型的内存高效的基于梯度的越狱方法

发布时间：2024年11月12日

`LLM应用` `网络安全` `人工智能`

> Zer0-Jack: A Memory-efficient Gradient-based Jailbreaking Method for Black-box Multi-modal Large Language Models

# 摘要

> 越狱方法，诱导多模态大型语言模型（MLLMs）输出有害响应，引发了重大的安全担忧。在这些方法中，基于梯度的方法，即使用梯度生成恶意提示，由于在白盒环境中成功率高，即可以完全访问模型，已被广泛研究。然而，这些方法有显著的局限性：它们需要白盒访问，这并不总是可行的，并且涉及高内存使用。为了解决无法进行白盒访问的情况，攻击者经常采用转移攻击。在转移攻击中，使用白盒模型生成的恶意输入应用于黑盒模型，但这通常会导致攻击性能降低。为了克服这些挑战，我们提出了 Zer0-Jack，一种通过利用零阶优化绕过白盒访问需求的方法。我们提出了补丁坐标下降，以有效地生成恶意图像输入来直接攻击黑盒 MLLMs，这进一步显著降低了内存使用。通过大量实验，Zer0-Jack 在各种模型中实现了高攻击成功率，超过了以前的基于转移的方法，并与现有的白盒越狱技术表现相当。值得注意的是，Zer0-Jack 在黑盒设置下对带有有害行为多模态数据集的 MiniGPT-4 实现了 95％的攻击成功率，证明了其有效性。此外，我们表明 Zer0-Jack 可以直接攻击商业 MLLMs，如 GPT-4o。补充材料中提供了代码。

> Jailbreaking methods, which induce Multi-modal Large Language Models (MLLMs) to output harmful responses, raise significant safety concerns. Among these methods, gradient-based approaches, which use gradients to generate malicious prompts, have been widely studied due to their high success rates in white-box settings, where full access to the model is available. However, these methods have notable limitations: they require white-box access, which is not always feasible, and involve high memory usage. To address scenarios where white-box access is unavailable, attackers often resort to transfer attacks. In transfer attacks, malicious inputs generated using white-box models are applied to black-box models, but this typically results in reduced attack performance. To overcome these challenges, we propose Zer0-Jack, a method that bypasses the need for white-box access by leveraging zeroth-order optimization. We propose patch coordinate descent to efficiently generate malicious image inputs to directly attack black-box MLLMs, which significantly reduces memory usage further. Through extensive experiments, Zer0-Jack achieves a high attack success rate across various models, surpassing previous transfer-based methods and performing comparably with existing white-box jailbreak techniques. Notably, Zer0-Jack achieves a 95\% attack success rate on MiniGPT-4 with the Harmful Behaviors Multi-modal Dataset on a black-box setting, demonstrating its effectiveness. Additionally, we show that Zer0-Jack can directly attack commercial MLLMs such as GPT-4o. Codes are provided in the supplement.

[Arxiv](https://arxiv.org/abs/2411.07559)