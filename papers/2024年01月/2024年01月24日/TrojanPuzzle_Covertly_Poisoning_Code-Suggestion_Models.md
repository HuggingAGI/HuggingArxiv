# TrojanPuzzle：潜伏毒化代码推荐模型

发布时间：2024年01月24日

`Agent

理由：这篇论文主要讨论了针对大型语言模型（LLM）的自动代码建议工具（如GitHub Copilot）的攻击策略，特别是通过在非上下文区域植入恶意数据来绕过静态分析的方法。这些攻击策略涉及到对模型的操控，以影响其在特定情境下的行为，如推荐不安全代码。这种对模型的操控和影响可以被视为一种“Agent”行为，即攻击者作为Agent试图通过特定策略影响模型的行为。因此，这篇论文更适合归类到Agent分类中。` `软件工程` `网络安全`

> TrojanPuzzle: Covertly Poisoning Code-Suggestion Models

# 摘要

> GitHub Copilot等工具的兴起，使得自动代码建议在软件工程领域成为现实。这些工具依托大型语言模型，通常在从公共来源未经筛选的大量代码库上进行训练。然而，这也使得模型易受数据中毒攻击，攻击者通过注入恶意数据来操控模型训练。此类攻击旨在特定情境下，如运行时，影响模型推荐不安全代码。以往的攻击方法是将不安全代码直接注入训练数据，易被静态分析工具识别并清除。本研究中，我们提出了两种新型攻击策略：COVERT和TROJANPUZZLE，它们通过在文档字符串等非上下文区域植入恶意数据，巧妙绕过静态分析。特别是TROJANPUZZLE，它通过不直接包含可疑代码片段，却能在模型完成代码时诱导其推荐完整的不安全代码，有效对抗基于签名的数据集清洗技术。我们的实验表明，这两种攻击对选择用于训练或调整代码建议模型的代码具有显著影响，提醒实践者需谨慎选择训练数据。

> With tools like GitHub Copilot, automatic code suggestion is no longer a dream in software engineering. These tools, based on large language models, are typically trained on massive corpora of code mined from unvetted public sources. As a result, these models are susceptible to data poisoning attacks where an adversary manipulates the model's training by injecting malicious data. Poisoning attacks could be designed to influence the model's suggestions at run time for chosen contexts, such as inducing the model into suggesting insecure code payloads. To achieve this, prior attacks explicitly inject the insecure code payload into the training data, making the poison data detectable by static analysis tools that can remove such malicious data from the training set. In this work, we demonstrate two novel attacks, COVERT and TROJANPUZZLE, that can bypass static analysis by planting malicious poison data in out-of-context regions such as docstrings. Our most novel attack, TROJANPUZZLE, goes one step further in generating less suspicious poison data by never explicitly including certain (suspicious) parts of the payload in the poison data, while still inducing a model that suggests the entire payload when completing code (i.e., outside docstrings). This makes TROJANPUZZLE robust against signature-based dataset-cleansing methods that can filter out suspicious sequences from the training data. Our evaluation against models of two sizes demonstrates that both COVERT and TROJANPUZZLE have significant implications for practitioners when selecting code used to train or tune code-suggestion models.

[Arxiv](https://arxiv.org/abs/2301.02344)