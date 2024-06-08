# TrojanPuzzle：潜伏毒化代码推荐模型

发布时间：2024年01月24日

`Agent

这篇论文主要讨论了针对GitHub Copilot等自动代码建议工具的新型攻击策略，即COVERT和TROJANPUZZLE。这些攻击策略通过在非上下文区域植入恶意数据，绕过了传统的静态分析检测，从而影响模型的训练和输出。这种研究关注的是如何通过特定的攻击手段影响智能Agent（如GitHub Copilot）的行为，因此属于Agent分类。这与RAG（检索增强生成）、LLM应用（大型语言模型的应用）或LLM理论（大型语言模型的理论研究）不符，因为它的重点在于Agent的安全性和攻击策略，而不是模型的应用或理论基础。` `软件工程` `网络安全`

> TrojanPuzzle: Covertly Poisoning Code-Suggestion Models

# 摘要

> GitHub Copilot等工具的出现，让自动代码建议不再是软件工程的幻想。这些工具依托大型语言模型，通常在未经筛选的公共代码库上进行训练。然而，这也使得它们容易遭受数据中毒攻击，攻击者通过注入恶意数据来操控模型训练。以往的攻击通过直接在训练数据中插入不安全代码，使得静态分析工具能够识别并清除这些恶意内容。本研究中，我们提出了两种新型攻击策略：COVERT和TROJANPUZZLE，它们通过在文档字符串等非上下文区域植入恶意数据，巧妙地避开了静态分析的检测。特别是TROJANPUZZLE，它通过不在中毒数据中明确包含可疑部分，却能在模型完成代码时诱导其生成完整的不安全代码负载，从而对基于签名的数据集清洗方法具有抵抗力。我们的实验表明，这两种攻击对选择用于训练或调整代码建议模型的代码具有显著影响，提醒实践者需谨慎选择训练数据。

> With tools like GitHub Copilot, automatic code suggestion is no longer a dream in software engineering. These tools, based on large language models, are typically trained on massive corpora of code mined from unvetted public sources. As a result, these models are susceptible to data poisoning attacks where an adversary manipulates the model's training by injecting malicious data. Poisoning attacks could be designed to influence the model's suggestions at run time for chosen contexts, such as inducing the model into suggesting insecure code payloads. To achieve this, prior attacks explicitly inject the insecure code payload into the training data, making the poison data detectable by static analysis tools that can remove such malicious data from the training set. In this work, we demonstrate two novel attacks, COVERT and TROJANPUZZLE, that can bypass static analysis by planting malicious poison data in out-of-context regions such as docstrings. Our most novel attack, TROJANPUZZLE, goes one step further in generating less suspicious poison data by never explicitly including certain (suspicious) parts of the payload in the poison data, while still inducing a model that suggests the entire payload when completing code (i.e., outside docstrings). This makes TROJANPUZZLE robust against signature-based dataset-cleansing methods that can filter out suspicious sequences from the training data. Our evaluation against models of two sizes demonstrates that both COVERT and TROJANPUZZLE have significant implications for practitioners when selecting code used to train or tune code-suggestion models.

[Arxiv](https://arxiv.org/abs/2301.02344)