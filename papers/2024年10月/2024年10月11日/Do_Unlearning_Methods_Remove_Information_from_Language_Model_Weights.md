# 遗忘方法能否真正从语言模型权重中移除信息？

发布时间：2024年10月11日

`LLM理论` `网络安全` `生物安全`

> Do Unlearning Methods Remove Information from Language Model Weights?

# 摘要

> 大型语言模型掌握的网络安全攻击、生物武器制造和人类操纵技能，存在被滥用的风险。过去，我们尝试通过消除技术来解决这一问题，但一直不清楚这些技术是彻底删除了模型中的相关信息，还是仅仅使其难以访问。为了明确区分这两种效果，我们设计了一种对抗性评估方法：允许攻击者接触到部分已删除的信息，并利用这些信息尝试恢复其他相关内容。实验结果显示，即使采用当前的消除技术，通过微调仍能恢复88%的原始准确率，这表明现有方法在彻底删除模型信息方面存在明显局限。

> Large Language Models' knowledge of how to perform cyber-security attacks, create bioweapons, and manipulate humans poses risks of misuse. Previous work has proposed methods to unlearn this knowledge. Historically, it has been unclear whether unlearning techniques are removing information from the model weights or just making it harder to access. To disentangle these two objectives, we propose an adversarial evaluation method to test for the removal of information from model weights: we give an attacker access to some facts that were supposed to be removed, and using those, the attacker tries to recover other facts from the same distribution that cannot be guessed from the accessible facts. We show that using fine-tuning on the accessible facts can recover 88% of the pre-unlearning accuracy when applied to current unlearning methods, revealing the limitations of these methods in removing information from the model weights.

[Arxiv](https://arxiv.org/abs/2410.08827)