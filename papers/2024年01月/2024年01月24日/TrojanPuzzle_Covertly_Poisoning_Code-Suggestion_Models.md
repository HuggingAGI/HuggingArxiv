# TrojanPuzzle：潜伏毒化代码推荐模型

发布时间：2024年01月24日

`Agent

理由：这篇论文主要讨论了针对大型语言模型（LLM）的自动代码建议工具（如GitHub Copilot）的攻击方法，特别是通过在非上下文区域植入恶意数据来绕过静态分析的攻击策略。这些攻击方法涉及到对模型的操纵和影响，从而影响其在特定上下文中的行为，这与Agent的概念相符，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类为Agent，因为它关注的是如何通过特定的策略影响和操纵模型，以达到攻击者的目的。` `软件工程` `网络安全`

> TrojanPuzzle: Covertly Poisoning Code-Suggestion Models

# 摘要

> GitHub Copilot等工具的出现，让自动代码建议在软件工程领域成为现实。这些工具依托大型语言模型，通常在未经筛选的公共代码库上进行训练，因此易受数据中毒攻击，攻击者通过注入恶意数据影响模型训练。此类攻击能操控模型在特定上下文中提供不安全的代码建议。以往的攻击通过直接在训练数据中插入不安全代码，使得静态分析工具能识别并清除这些恶意内容。本研究中，我们提出了两种新型攻击方法——COVERT和TROJANPUZZLE，它们通过在文档字符串等非上下文区域植入恶意数据，巧妙绕过静态分析。特别是TROJANPUZZLE，它通过不在中毒数据中明确包含可疑部分，却仍能诱导模型在代码补全时提供完整的不安全代码负载，有效抵御了基于签名的数据集清洗技术。我们的实验表明，这两种攻击对选择用于训练或调整代码建议模型的代码具有显著影响，提醒实践者需谨慎选择训练数据。

> With tools like GitHub Copilot, automatic code suggestion is no longer a dream in software engineering. These tools, based on large language models, are typically trained on massive corpora of code mined from unvetted public sources. As a result, these models are susceptible to data poisoning attacks where an adversary manipulates the model's training by injecting malicious data. Poisoning attacks could be designed to influence the model's suggestions at run time for chosen contexts, such as inducing the model into suggesting insecure code payloads. To achieve this, prior attacks explicitly inject the insecure code payload into the training data, making the poison data detectable by static analysis tools that can remove such malicious data from the training set. In this work, we demonstrate two novel attacks, COVERT and TROJANPUZZLE, that can bypass static analysis by planting malicious poison data in out-of-context regions such as docstrings. Our most novel attack, TROJANPUZZLE, goes one step further in generating less suspicious poison data by never explicitly including certain (suspicious) parts of the payload in the poison data, while still inducing a model that suggests the entire payload when completing code (i.e., outside docstrings). This makes TROJANPUZZLE robust against signature-based dataset-cleansing methods that can filter out suspicious sequences from the training data. Our evaluation against models of two sizes demonstrates that both COVERT and TROJANPUZZLE have significant implications for practitioners when selecting code used to train or tune code-suggestion models.

[Arxiv](https://arxiv.org/abs/2301.02344)