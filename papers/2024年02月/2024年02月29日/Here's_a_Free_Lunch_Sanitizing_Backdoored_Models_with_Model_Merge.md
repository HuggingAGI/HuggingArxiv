# [惊喜呈现：运用模型融合技术，轻松净化遭后门侵入的模型，实现安全“白吃午餐”](https://arxiv.org/abs/2402.19334)

发布时间：2024年02月29日

`LLM应用`

> Here's a Free Lunch: Sanitizing Backdoored Models with Model Merge

> 开源运动使得预训练语言模型得以广泛应用，有力推进创新并让更多人接触到前沿技术。但同时也伴随着安全隐患，如后门攻击——利用特定输入激活隐匿的恶意行为，对NLP系统的完整性和可信度构成威胁。本文提出，即便模型并非绝对安全，也能通过将含后门模型与其他同类模型进行融合以缓解后门漏洞问题。实验中，我们研究了多种模型组合（如BERT-Base、RoBERTa-Large、Llama2-7B 以及 Mistral-7B）及数据集（例如 SST-2、OLID、AG News 和 QNLI）。相较于现有多种高级防御手段，我们的方法无需额外资源和专业知识，在推理阶段就提供了高效对抗后门攻击的有效防护，并且表现持续超越其他先进基准，平均降幅高达攻击成功率75%。由于模型融合本就是提升模型性能的常用策略，其所带来的防御层面的额外优势堪称无价之宝。

> The democratization of pre-trained language models through open-source initiatives has rapidly advanced innovation and expanded access to cutting-edge technologies. However, this openness also brings significant security risks, including backdoor attacks, where hidden malicious behaviors are triggered by specific inputs, compromising natural language processing (NLP) system integrity and reliability. This paper suggests that merging a backdoored model with other homogeneous models can remediate backdoor vulnerabilities even if such models are not entirely secure. In our experiments, we explore various models (BERT-Base, RoBERTa-Large, Llama2-7B, and Mistral-7B) and datasets (SST-2, OLID, AG News, and QNLI). Compared to multiple advanced defensive approaches, our method offers an effective and efficient inference-stage defense against backdoor attacks without additional resources or specific knowledge. Our approach consistently outperforms the other advanced baselines, leading to an average of 75% reduction in the attack success rate. Since model merging has been an established approach for improving model performance, the extra advantage it provides regarding defense can be seen as a cost-free bonus.