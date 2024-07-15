# 在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。

发布时间：2024年07月12日

`LLM应用` `网络安全` `人工智能`

> Refuse Whenever You Feel Unsafe: Improving Safety in LLMs via Decoupled Refusal Training

# 摘要

> 本研究针对大型语言模型（LLM）安全调优中的关键问题，通过解决安全数据中的拒绝偏差，提升了模型拒绝生成不安全内容的能力。我们提出的解耦拒绝训练（DeRTa）方法，通过两个创新技术——有害响应前缀的最大似然估计和强化过渡优化，增强了模型在面对有害提示时的安全响应能力。实证测试显示，DeRTa不仅提升了安全性，还在防御攻击方面超越了GPT-4等模型，有效抵御了如CodeAttack等高级攻击。详细代码和数据已公开在GitHub上。

> This study addresses a critical gap in safety tuning practices for Large Language Models (LLMs) by identifying and tackling a refusal position bias within safety tuning data, which compromises the models' ability to appropriately refuse generating unsafe content. We introduce a novel approach, Decoupled Refusal Training (DeRTa), designed to empower LLMs to refuse compliance to harmful prompts at any response position, significantly enhancing their safety capabilities. DeRTa incorporates two novel components: (1) Maximum Likelihood Estimation (MLE) with Harmful Response Prefix, which trains models to recognize and avoid unsafe content by appending a segment of harmful response to the beginning of a safe response, and (2) Reinforced Transition Optimization (RTO), which equips models with the ability to transition from potential harm to safety refusal consistently throughout the harmful response sequence. Our empirical evaluation, conducted using LLaMA3 and Mistral model families across six attack scenarios, demonstrates that our method not only improves model safety without compromising performance but also surpasses well-known models such as GPT-4 in defending against attacks. Importantly, our approach successfully defends recent advanced attack methods (e.g., CodeAttack) that have jailbroken GPT-4 and LLaMA3-70B-Instruct. Our code and data can be found at https://github.com/RobustNLP/DeRTa.

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x1.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x2.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x3.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x4.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x5.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x6.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x7.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x8.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x9.png)

![在感到不安全时勇敢说“不”：通过解耦拒绝训练策略，提升 LLM 的安全性。](../../../paper_images/2407.09121/x10.png)

[Arxiv](https://arxiv.org/abs/2407.09121)