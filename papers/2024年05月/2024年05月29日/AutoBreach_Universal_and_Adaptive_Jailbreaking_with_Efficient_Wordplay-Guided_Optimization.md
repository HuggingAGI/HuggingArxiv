# AutoBreach：一种通用且自适应的越狱方法，通过高效的文字游戏策略进行优化，旨在突破各种限制。

发布时间：2024年05月29日

`Agent

这篇论文主要讨论了一种名为AutoBreach的越狱技术，该技术专门设计来攻击大型语言模型（LLMs），以检测其安全漏洞。论文从攻击者的视角出发，提出了新的越狱策略，并详细介绍了AutoBreach的工作原理和优化方法。这种技术利用了文字游戏的灵活性和LLMs的自动总结与推理功能，以生成对抗性提示，从而实现对LLMs的越狱。此外，论文还提到了AutoBreach在多种LLMs上的应用和成功率，显示了其在实际应用中的有效性。因此，这篇论文更符合Agent分类，因为它描述了一种专门用于攻击和测试LLMs安全性的自动化工具或代理。` `信息安全` `人工智能`

> AutoBreach: Universal and Adaptive Jailbreaking with Efficient Wordplay-Guided Optimization

# 摘要

> 尽管大型语言模型（LLMs）在多领域广泛应用，但它们易受越狱攻击，这可能削弱其防御能力。以往的越狱研究常因通用性不足、效率低下及过度依赖人工设计而受限。为此，我们重新审视了LLMs的越狱策略，并从攻击者视角明确了三个关键属性，以指导越狱技术的发展。我们创新性地提出了AutoBreach，一种仅需黑盒访问的越狱技术。借鉴文字游戏的灵活性，AutoBreach采用文字游戏引导的映射规则采样，生成多样化的通用映射规则，用以构建对抗性提示，同时利用LLMs的自动总结与推理功能，减轻了人工负担。为提升越狱成功率，我们建议采用句子压缩和基于思维链的映射规则，以修正目标LLMs中的错误和文字游戏误解。此外，我们设计了一种两阶段映射规则优化策略，先优化规则再查询目标LLMs，以增强AutoBreach的效率。AutoBreach能高效检测多种LLMs的安全漏洞，包括Claude-3、GPT-3.5、GPT-4 Turbo等专有模型及Bingchat、GPT-4 Web等平台，平均成功率达80%以上，且查询次数控制在10次以内。

> Despite the widespread application of large language models (LLMs) across various tasks, recent studies indicate that they are susceptible to jailbreak attacks, which can render their defense mechanisms ineffective. However, previous jailbreak research has frequently been constrained by limited universality, suboptimal efficiency, and a reliance on manual crafting. In response, we rethink the approach to jailbreaking LLMs and formally define three essential properties from the attacker' s perspective, which contributes to guiding the design of jailbreak methods. We further introduce AutoBreach, a novel method for jailbreaking LLMs that requires only black-box access. Inspired by the versatility of wordplay, AutoBreach employs a wordplay-guided mapping rule sampling strategy to generate a variety of universal mapping rules for creating adversarial prompts. This generation process leverages LLMs' automatic summarization and reasoning capabilities, thus alleviating the manual burden. To boost jailbreak success rates, we further suggest sentence compression and chain-of-thought-based mapping rules to correct errors and wordplay misinterpretations in target LLMs. Additionally, we propose a two-stage mapping rule optimization strategy that initially optimizes mapping rules before querying target LLMs to enhance the efficiency of AutoBreach. AutoBreach can efficiently identify security vulnerabilities across various LLMs, including three proprietary models: Claude-3, GPT-3.5, GPT-4 Turbo, and two LLMs' web platforms: Bingchat, GPT-4 Web, achieving an average success rate of over 80% with fewer than 10 queries

[Arxiv](https://arxiv.org/abs/2405.19668)