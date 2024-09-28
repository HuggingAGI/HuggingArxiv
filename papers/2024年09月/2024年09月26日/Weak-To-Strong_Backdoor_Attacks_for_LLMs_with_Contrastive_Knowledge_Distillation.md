# 针对 LLM 的弱-强后门攻击与对比知识蒸馏

发布时间：2024年09月26日

`LLM理论` `网络安全` `人工智能`

> Weak-To-Strong Backdoor Attacks for LLMs with Contrastive Knowledge Distillation

# 摘要

> 尽管大型语言模型 (LLM) 因其卓越能力而被广泛应用，但它们易受后门攻击。这些攻击通过毒化训练样本和全参数微调引入目标漏洞，但这种攻击因需大量计算资源而受限。参数高效微调 (PEFT) 虽提供替代方案，但其受限的参数更新可能阻碍触发器与目标标签的对齐。本研究首先验证了 PEFT 后门攻击在实现可行性能方面的挑战。为解决这些问题并提升 PEFT 后门攻击的有效性，我们提出了一种基于对比知识蒸馏 (W2SAttack) 的新型后门攻击算法。具体而言，我们通过全参数微调毒化小规模语言模型作为教师模型，再通过 PEFT 的对比知识蒸馏，秘密地将后门转移到大规模学生模型。理论分析表明，W2SAttack 能增强后门攻击的有效性。实验结果显示，W2SAttack 在分类任务中的成功率接近 100%。

> Despite being widely applied due to their exceptional capabilities, Large Language Models (LLMs) have been proven to be vulnerable to backdoor attacks. These attacks introduce targeted vulnerabilities into LLMs by poisoning training samples and full-parameter fine-tuning. However, this kind of backdoor attack is limited since they require significant computational resources, especially as the size of LLMs increases. Besides, parameter-efficient fine-tuning (PEFT) offers an alternative but the restricted parameter updating may impede the alignment of triggers with target labels. In this study, we first verify that backdoor attacks with PEFT may encounter challenges in achieving feasible performance. To address these issues and improve the effectiveness of backdoor attacks with PEFT, we propose a novel backdoor attack algorithm from weak to strong based on contrastive knowledge distillation (W2SAttack). Specifically, we poison small-scale language models through full-parameter fine-tuning to serve as the teacher model. The teacher model then covertly transfers the backdoor to the large-scale student model through contrastive knowledge distillation, which employs PEFT. Theoretical analysis reveals that W2SAttack has the potential to augment the effectiveness of backdoor attacks. We demonstrate the superior performance of W2SAttack on classification tasks across four language models, four backdoor attack algorithms, and two different architectures of teacher models. Experimental results indicate success rates close to 100% for backdoor attacks targeting PEFT.

[Arxiv](https://arxiv.org/abs/2409.17946)