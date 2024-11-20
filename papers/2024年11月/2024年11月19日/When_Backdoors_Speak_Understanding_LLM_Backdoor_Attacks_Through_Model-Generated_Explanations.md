# 当后门“开口”：借由模型生成的解释来洞悉 LLM 后门攻击

发布时间：2024年11月19日

`LLM应用` `语言模型` `网络安全`

> When Backdoors Speak: Understanding LLM Backdoor Attacks Through Model-Generated Explanations

# 摘要

> 大型语言模型（LLMs）易受后门攻击，隐藏的触发因素会恶意操控模型行为。尽管已提出若干后门攻击方法，可后门在LLMs中的运作机制仍未被充分探究。本文中，我们不再局限于攻击LLMs，而是透过自然语言解释这一新颖视角来研究后门功能。具体而言，我们借助LLMs的生成能力为其决策生成人类能理解的解释，从而得以对比干净样本和中毒样本的解释。我们探索了各类后门攻击，并将后门嵌入LLaMA模型以用于多项任务。实验表明，被植入后门的模型为干净数据生成的解释质量更高，而针对中毒数据生成的解释比干净数据更具一致性。我们进一步剖析了解释生成过程，发现在令牌层面，中毒样本的解释令牌仅在LLM的最后几个转换层中出现。在句子层面，注意力动态显示，生成解释时，中毒输入会将注意力从输入上下文转移。这些发现深化了我们对LLMs中后门攻击机制的认识，并通过可解释性技术为检测此类漏洞提供了框架，有助于开发更安全的LLMs。

> Large Language Models (LLMs) are vulnerable to backdoor attacks, where hidden triggers can maliciously manipulate model behavior. While several backdoor attack methods have been proposed, the mechanisms by which backdoor functions operate in LLMs remain underexplored. In this paper, we move beyond attacking LLMs and investigate backdoor functionality through the novel lens of natural language explanations. Specifically, we leverage LLMs' generative capabilities to produce human-understandable explanations for their decisions, allowing us to compare explanations for clean and poisoned samples. We explore various backdoor attacks and embed the backdoor into LLaMA models for multiple tasks. Our experiments show that backdoored models produce higher-quality explanations for clean data compared to poisoned data, while generating significantly more consistent explanations for poisoned data than for clean data. We further analyze the explanation generation process, revealing that at the token level, the explanation token of poisoned samples only appears in the final few transformer layers of the LLM. At the sentence level, attention dynamics indicate that poisoned inputs shift attention from the input context when generating the explanation. These findings deepen our understanding of backdoor attack mechanisms in LLMs and offer a framework for detecting such vulnerabilities through explainability techniques, contributing to the development of more secure LLMs.

[Arxiv](https://arxiv.org/abs/2411.12701)