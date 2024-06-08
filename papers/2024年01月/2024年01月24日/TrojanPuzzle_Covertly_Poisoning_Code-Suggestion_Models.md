# TrojanPuzzle：潜伏毒化代码推荐模型

发布时间：2024年01月24日

`Agent

这篇论文主要探讨了针对大型语言模型（LLM）在代码生成领域的安全威胁，特别是通过数据中毒攻击来操控模型的行为。论文中提出的两种新型攻击策略（COVERT和TROJANPUZZLE）展示了如何通过非直接的方式影响模型的输出，从而在特定上下文中生成不安全的代码。这种类型的研究更偏向于Agent的范畴，因为它关注的是如何通过特定的策略或行为（即攻击策略）来影响或操控系统的行为，而不是直接研究LLM的理论或应用。因此，将其归类为Agent是合适的。` `软件工程` `网络安全`

> TrojanPuzzle: Covertly Poisoning Code-Suggestion Models

# 摘要

> GitHub Copilot等工具的出现，使得自动代码建议在软件工程领域成为现实。这些工具依托大型语言模型，通常在从公共来源挖掘的大量代码上进行训练。然而，这也使得它们容易遭受数据中毒攻击，攻击者通过注入恶意数据来操控模型训练。此类攻击旨在特定上下文中影响模型的实时建议，比如诱导模型生成不安全的代码。以往的攻击方法是将不安全代码直接注入训练数据，这使得中毒数据能被静态分析工具检测并清除。本研究中，我们提出了两种新型攻击策略：COVERT和TROJANPUZZLE，它们通过在文档字符串等非上下文区域植入恶意数据，巧妙绕过静态分析。特别是TROJANPUZZLE，它通过不明确包含可疑部分，却仍能诱导模型在完成代码时生成完整的不安全代码负载，从而有效对抗基于签名的数据集清洗方法。我们的实验表明，这两种攻击对选择用于训练或调整代码建议模型的代码具有显著影响，提醒实践者需谨慎选择训练数据。

> With tools like GitHub Copilot, automatic code suggestion is no longer a dream in software engineering. These tools, based on large language models, are typically trained on massive corpora of code mined from unvetted public sources. As a result, these models are susceptible to data poisoning attacks where an adversary manipulates the model's training by injecting malicious data. Poisoning attacks could be designed to influence the model's suggestions at run time for chosen contexts, such as inducing the model into suggesting insecure code payloads. To achieve this, prior attacks explicitly inject the insecure code payload into the training data, making the poison data detectable by static analysis tools that can remove such malicious data from the training set. In this work, we demonstrate two novel attacks, COVERT and TROJANPUZZLE, that can bypass static analysis by planting malicious poison data in out-of-context regions such as docstrings. Our most novel attack, TROJANPUZZLE, goes one step further in generating less suspicious poison data by never explicitly including certain (suspicious) parts of the payload in the poison data, while still inducing a model that suggests the entire payload when completing code (i.e., outside docstrings). This makes TROJANPUZZLE robust against signature-based dataset-cleansing methods that can filter out suspicious sequences from the training data. Our evaluation against models of two sizes demonstrates that both COVERT and TROJANPUZZLE have significant implications for practitioners when selecting code used to train or tune code-suggestion models.

[Arxiv](https://arxiv.org/abs/2301.02344)