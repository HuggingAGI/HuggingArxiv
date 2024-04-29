# 针对大型语言模型第三方接口的攻击

发布时间：2024年04月24日

`LLM应用` `网络安全` `人工智能`

> Attacks on Third-Party APIs of Large Language Models

# 摘要

> 近期，大型语言模型（LLM）服务推出了插件生态系统，以便与第三方API服务进行互动，这不仅扩展了LLM的功能，也带来了安全隐患，因为这些第三方插件的可信度难以保证。本研究提出了一种新的攻击框架，旨在探究整合了第三方服务的LLM平台的安全与安全隐患。通过将该框架应用于多个广泛使用的LLM，我们发现了多个领域中的第三方API所遭受的真实世界恶意攻击，这些攻击能够悄无声息地改变LLM的输出结果。文章深入讨论了第三方API整合所带来的独特挑战，并提出了提升LLM生态系统未来安全性与安全性的战略性建议。相关代码已在 https://github.com/vk0812/Third-Party-Attacks-on-LLMs 上公开。

> Large language model (LLM) services have recently begun offering a plugin ecosystem to interact with third-party API services. This innovation enhances the capabilities of LLMs, but it also introduces risks, as these plugins developed by various third parties cannot be easily trusted. This paper proposes a new attacking framework to examine security and safety vulnerabilities within LLM platforms that incorporate third-party services. Applying our framework specifically to widely used LLMs, we identify real-world malicious attacks across various domains on third-party APIs that can imperceptibly modify LLM outputs. The paper discusses the unique challenges posed by third-party API integration and offers strategic possibilities to improve the security and safety of LLM ecosystems moving forward. Our code is released at https://github.com/vk0812/Third-Party-Attacks-on-LLMs.

[Arxiv](https://arxiv.org/abs/2404.16891)