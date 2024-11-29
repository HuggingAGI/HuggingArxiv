# WaterPark：对语言模型水印的鲁棒性评估
发布时间：2024年11月20日


> WaterPark: A Robustness Assessment of Language Model Watermarking
>
> 为减轻大型语言模型（LLMs）被滥用的情况，比如传播虚假信息、自动网络钓鱼以及学术作弊等，迫切需要拥有识别 LLM 生成文本的能力。水印技术成为颇具前景的解决方案：它在 LLM 的生成过程中植入统计信号，随后验证 LLM 是否生成了给定的文本。各类水印方法（“水印器”）已被提出；然而，因缺乏统一的评估平台，诸多关键问题尚未得到充分探究：其一，各种水印器的长处与局限是什么，尤其是它们的抗攻击能力？其二，各种设计选择如何影响其鲁棒性？其三，如何在对抗环境中最优地操作水印器？
  为填补这一空缺，我们对现有的 LLM 水印器和水印去除攻击加以系统化，描绘出它们的设计空间。接着，我们开发出 WaterPark，这是一个集成了 10 种先进水印器和 12 种代表性攻击的统一平台。更为重要的是，借助 WaterPark，我们对现有的水印器展开了全面评估，揭示出各种设计选择对其抗攻击能力的影响。例如，水印器抵御日益强烈攻击的能力取决于其对上下文的依赖程度。我们进一步探索了在对抗环境中操作水印器的最佳实践。比如，将通用检测器与特定于水印的检测器配合使用，能够提升易受攻击的水印器的安全性。我们认为，我们的研究为当前的 LLM 水印技术带来了启示，而 WaterPark 则作为一个宝贵的测试平台，有助于推动未来的研究。
>
> https://arxiv.org/abs/2411.13425

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.13425](https://arxiv.org/abs/2411.13425)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)