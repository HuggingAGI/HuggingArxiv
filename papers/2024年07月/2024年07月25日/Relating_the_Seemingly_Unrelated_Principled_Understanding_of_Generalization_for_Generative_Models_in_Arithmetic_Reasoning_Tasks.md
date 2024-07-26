# 揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理

发布时间：2024年07月25日

`LLM理论` `人工智能`

> Relating the Seemingly Unrelated: Principled Understanding of Generalization for Generative Models in Arithmetic Reasoning Tasks

# 摘要

> 大型语言模型虽在多任务中表现出色，但其泛化能力仍待深入探究。算术任务为此提供了关键视角。过往研究中，一些谜团依旧未解：模型虽能处理未见的长加法，但在乘法等复杂任务中效果不一；在特定模数（如模 100）下，模型对长未见加法表现良好，但在接近模数（如模 101）下则表现欠佳。我们认为，先前研究过于关注模型改进，忽略了任务本质差异。我们的理论框架揭示了这一点：数字加法的平移不变性自然与相对位置编码相匹配，使得加法能泛化至更长领域。模 100 与模 101 的差异在于基数，模 100 与十进制兼容，任务中无需额外数字信息。实验验证了我们的理论，深化了泛化机制的理解，并推动了更高效模型训练和目标导向的 AI 发展。

> Large language models (LLMs) have demonstrated impressive versatility across numerous tasks, yet their generalization capabilities remain poorly understood. To investigate these behaviors, arithmetic tasks serve as important venues. In previous studies, seemingly unrelated mysteries still exist -- (1) models with appropriate positional embeddings can correctly perform longer unseen arithmetic operations such as addition, but their effectiveness varies in more complex tasks like multiplication; (2) models perform well for longer unseen cases in modular addition under specific moduli (e.g., modulo 100) but struggle under very close moduli (e.g., modulo 101), regardless of the positional encoding used. We believe previous studies have been treating the symptoms rather than addressing the root cause -- they have paid excessive attention to improving model components, while overlooking the differences in task properties that may be the real drivers. This is confirmed by our unified theoretical framework for different arithmetic scenarios. For example, unlike multiplication, the digital addition task has the property of translation invariance which naturally aligns with the relative positional encoding, and this combination leads to successful generalization of addition to unseen longer domains. The discrepancy in operations modulo 100 and 101 arises from the base. Modulo 100, unlike 101, is compatible with the decimal system (base 10), such that unseen information in digits beyond the units digit and the tens digit is actually not needed for the task. Extensive experiments with GPT-like models validate our theoretical predictions. These findings deepen our understanding of the generalization mechanisms, and facilitate more data-efficient model training and objective-oriented AI alignment.

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc1.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc2.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc3.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc4.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc5.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_acc6.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_mathcalD_4.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_mathcalD_5.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_mathcalD_45.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/training_loss_addition.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/training_loss_addition_robust.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_accuracy_robust.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc1.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc2.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc3.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc4.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc5.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc6.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc7.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc8.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_acc9.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_corr_mathcalD_4.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_corr_mathcalD_5.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_corr_mathcalD_45_ref4.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/DBD45_Comparison_digit_r2_corr_mathcalD_45_ref5.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/AbacusPE_Addition.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_modular_addition_digit_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_modular_addition_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_multiplication_digit_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_multiplication_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/AbacusPE_Multiplication.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_modular_multiplication_digit_accuracy.png)

![揭秘看似无关的联系：深入理解生成模型在算术推理任务中的泛化原理](../../../paper_images/2407.17963/in_sample_modular_multiplication_accuracy.png)

[Arxiv](https://arxiv.org/abs/2407.17963)