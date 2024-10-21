# 利用弱到强知识蒸馏技术，帮助大型语言模型摆脱后门攻击的困扰。

发布时间：2024年10月18日

`LLM理论` `网络安全` `人工智能`

> Unlearning Backdoor Attacks for LLMs with Weak-to-Strong Knowledge Distillation

# 摘要

> 参数高效微调 (PEFT) 虽能连接大型语言模型 (LLM) 与下游任务，却易受恶意攻击。研究发现，即使经过 PEFT，中毒的 LLM 在遇到特定触发器时仍会激活后门。为此，我们提出了一种基于特征对齐知识蒸馏的弱到强遗忘算法，名为 W2SDefense。首先，我们通过全参数微调训练一个小规模语言模型作为教师模型，然后利用 PEFT 指导中毒的学生模型遗忘后门。理论分析显示，W2SDefense 能有效增强学生模型遗忘后门的能力，防止其激活。实验结果表明，W2SDefense 在防御后门攻击方面表现优异，且不影响模型性能。

> Parameter-efficient fine-tuning (PEFT) can bridge the gap between large language models (LLMs) and downstream tasks. However, PEFT has been proven vulnerable to malicious attacks. Research indicates that poisoned LLMs, even after PEFT, retain the capability to activate internalized backdoors when input samples contain predefined triggers. In this paper, we introduce a novel weak-to-strong unlearning algorithm to defend against backdoor attacks based on feature alignment knowledge distillation, named W2SDefense. Specifically, we first train a small-scale language model through full-parameter fine-tuning to serve as the clean teacher model. Then, this teacher model guides the large-scale poisoned student model in unlearning the backdoor, leveraging PEFT. Theoretical analysis suggests that W2SDefense has the potential to enhance the student model's ability to unlearn backdoor features, preventing the activation of the backdoor. We conduct experiments on text classification tasks involving three state-of-the-art language models and three different backdoor attack algorithms. Our empirical results demonstrate the outstanding performance of W2SDefense in defending against backdoor attacks without compromising model performance.

[Arxiv](https://arxiv.org/abs/2410.14425)