# 准备好了吗？通过精心管理数据，在 LLM 的每个定制环节中提升其稳定性。

发布时间：2024年10月03日

`LLM应用` `人工智能安全` `网络安全`

> Buckle Up: Robustifying LLMs at Every Customization Stage via Data Curation

# 摘要

> 大型语言模型（LLM）通过“定制化”过程广泛应用于下游任务，其中微调是整合领域专业知识的常用手段。然而，最新研究表明，使用恶意样本微调 LLM 会削弱其鲁棒性，甚至放大有害内容，这种攻击被称为“越狱”。为应对这一威胁，我们提出了一种利用数据管理的防御框架，通过修订常识文本，从 LLM 视角提升其安全性。这一框架可在定制化过程的各个阶段发挥作用：定制前预防未来越狱尝试，定制中中和风险，定制后修复受损模型。由于管理后的数据通过标准微调流程强化了 LLM，我们在推理阶段无需添加额外模块，保持了定制过程的原貌。实验表明，越狱效果显著降低，生成负责任响应的成功率高达 100%。尤其值得一提的是，即使使用常识文本，我们的方法依然有效，这些文本通常比安全相关数据更易获取。通过全阶段的防御框架和实验验证，这项工作在缓解越狱风险和确保 LLM 安全定制方面取得了重要进展。

> Large language models (LLMs) are extensively adapted for downstream applications through a process known as "customization," with fine-tuning being a common method for integrating domain-specific expertise. However, recent studies have revealed a vulnerability that tuning LLMs with malicious samples can compromise their robustness and amplify harmful content, an attack known as "jailbreaking." To mitigate such attack, we propose an effective defensive framework utilizing data curation to revise commonsense texts and enhance their safety implication from the perspective of LLMs. The curated texts can mitigate jailbreaking attacks at every stage of the customization process: before customization to immunize LLMs against future jailbreak attempts, during customization to neutralize jailbreaking risks, or after customization to restore the compromised models. Since the curated data strengthens LLMs through the standard fine-tuning workflow, we do not introduce additional modules during LLM inference, thereby preserving the original customization process. Experimental results demonstrate a substantial reduction in jailbreaking effects, with up to a 100% success in generating responsible responses. Notably, our method is effective even with commonsense texts, which are often more readily available than safety-relevant data. With the every-stage defensive framework and supporting experimental performance, this work represents a significant advancement in mitigating jailbreaking risks and ensuring the secure customization of LLMs.

[Arxiv](https://arxiv.org/abs/2410.02220)