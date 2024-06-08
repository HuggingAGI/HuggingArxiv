# TrojanPuzzle：暗中污染代码推荐模型

发布时间：2024年01月24日

`Agent

理由：这篇论文主要讨论了针对大型语言模型（LLM）的自动代码建议工具（如GitHub Copilot）的攻击方法，特别是新型的数据中毒攻击——COVERT和TROJANPUZZLE。这些攻击方法通过在非上下文区域植入恶意数据来操控模型，从而在特定上下文中诱导模型生成不安全的代码建议。这种研究更偏向于Agent的范畴，因为它涉及对模型行为的操控和影响，以及如何通过特定的策略（如COVERT和TROJANPUZZLE）来实现这种操控。这与LLM的应用或理论研究不同，因为它侧重于模型的外部操控和安全威胁，而不是模型的内部机制或应用场景。` `软件工程` `网络安全`

> TrojanPuzzle: Covertly Poisoning Code-Suggestion Models

# 摘要

> GitHub Copilot等工具的出现，让自动代码建议在软件工程中成为现实。这些工具依托大型语言模型，通常在未经筛选的公共代码库上进行训练，因此易受数据中毒攻击，攻击者通过注入恶意数据来操控模型。此类攻击能在特定上下文中诱导模型生成不安全的代码建议。以往的攻击通过直接在训练数据中插入不安全代码，但这种方法易被静态分析工具识别并清除。本研究提出了两种新型攻击——COVERT和TROJANPUZZLE，它们通过在文档字符串等非上下文区域植入恶意数据，巧妙绕过静态分析。特别是TROJANPUZZLE，它通过不直接包含可疑部分，却能在模型完成代码时诱导其生成完整的不安全代码负载，有效抵抗基于签名的数据集清洗方法。对两种规模模型的测试显示，这两种攻击对选择训练或调整代码建议模型的代码具有显著影响。

> With tools like GitHub Copilot, automatic code suggestion is no longer a dream in software engineering. These tools, based on large language models, are typically trained on massive corpora of code mined from unvetted public sources. As a result, these models are susceptible to data poisoning attacks where an adversary manipulates the model's training by injecting malicious data. Poisoning attacks could be designed to influence the model's suggestions at run time for chosen contexts, such as inducing the model into suggesting insecure code payloads. To achieve this, prior attacks explicitly inject the insecure code payload into the training data, making the poison data detectable by static analysis tools that can remove such malicious data from the training set. In this work, we demonstrate two novel attacks, COVERT and TROJANPUZZLE, that can bypass static analysis by planting malicious poison data in out-of-context regions such as docstrings. Our most novel attack, TROJANPUZZLE, goes one step further in generating less suspicious poison data by never explicitly including certain (suspicious) parts of the payload in the poison data, while still inducing a model that suggests the entire payload when completing code (i.e., outside docstrings). This makes TROJANPUZZLE robust against signature-based dataset-cleansing methods that can filter out suspicious sequences from the training data. Our evaluation against models of two sizes demonstrates that both COVERT and TROJANPUZZLE have significant implications for practitioners when selecting code used to train or tune code-suggestion models.

[Arxiv](https://arxiv.org/abs/2301.02344)