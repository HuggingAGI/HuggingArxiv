# 紧急呼叫！针对开源大型语言模型的软提示攻击

发布时间：2024年07月03日

`LLM应用` `网络安全` `人工智能`

> SOS! Soft Prompt Attack Against Open-Source Large Language Models

# 摘要

> 开源大型语言模型（LLM）因其可定制、微调及免费使用的特性，在公众和业界广受欢迎。然而，部分开源LLM需经批准方可使用，促使第三方推出更易获取的版本。同时，这些LLM的微调或量化版本也由第三方发布，因其便捷性和较低的计算资源需求而备受青睐。这一趋势却增加了训练期间的攻击风险，威胁到LLM的完整性与安全性。为此，我们提出了一种新型训练时攻击——SOS，该攻击计算需求低，无需清洁数据或修改模型权重，确保模型功能不受影响。SOS能有效应对多种安全威胁，如后门、越狱及提示窃取攻击。实验证明，SOS在所有测试目标上均表现出色。此外，我们还引入了SOS技术的另一创新——版权标记，允许用户为其版权内容打上标记，防止模型滥用。

> Open-source large language models (LLMs) have become increasingly popular among both the general public and industry, as they can be customized, fine-tuned, and freely used. However, some open-source LLMs require approval before usage, which has led to third parties publishing their own easily accessible versions. Similarly, third parties have been publishing fine-tuned or quantized variants of these LLMs. These versions are particularly appealing to users because of their ease of access and reduced computational resource demands. This trend has increased the risk of training time attacks, compromising the integrity and security of LLMs. In this work, we present a new training time attack, SOS, which is designed to be low in computational demand and does not require clean data or modification of the model weights, thereby maintaining the model's utility intact. The attack addresses security issues in various scenarios, including the backdoor attack, jailbreak attack, and prompt stealing attack. Our experimental findings demonstrate that the proposed attack is effective across all evaluated targets. Furthermore, we present the other side of our SOS technique, namely the copyright token -- a novel technique that enables users to mark their copyrighted content and prevent models from using it.

[Arxiv](https://arxiv.org/abs/2407.03160)