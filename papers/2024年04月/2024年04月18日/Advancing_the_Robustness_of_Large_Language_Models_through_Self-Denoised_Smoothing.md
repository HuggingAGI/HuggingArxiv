# 本文探讨了一种提升大型语言模型鲁棒性的方法——自我去噪平滑技术。通过这种技术，我们能够有效地增强模型在面对噪声干扰时的稳定性和可靠性。

发布时间：2024年04月18日

`LLM理论` `机器学习`

> Advancing the Robustness of Large Language Models through Self-Denoised Smoothing

# 摘要

> 大型语言模型（LLMs）虽然取得了巨大成就，但其对抗性扰动的易感性，尤其是新兴的越狱攻击，引发了广泛担忧。面对模型规模的扩大和访问限制，提升其鲁棒性变得颇具挑战。在众多防御策略中，随机平滑因其无需完全掌握模型参数或进行对抗性训练微调而展现出巨大潜力。不过，这种方法通过在预测前向输入添加噪声，其效果受限于模型处理噪声数据的能力。为克服这一局限，我们提出一种新颖的自去噪平滑策略，利用LLMs的多任务处理能力，先对噪声输入进行净化，再基于净化后的数据进行预测。与传统的计算机视觉中的去噪平滑技术相比，该方法无需额外训练模型，展现出更高的效率与灵活性。实验结果显示，该策略在经验鲁棒性和认证鲁棒性方面均优于现有方法，有效防御了针对下游任务和人类对齐（越狱攻击）的对抗性攻击。相关代码已在 https://github.com/UCSB-NLP-Chang/SelfDenoise 上公开发布。

> Although large language models (LLMs) have achieved significant success, their vulnerability to adversarial perturbations, including recent jailbreak attacks, has raised considerable concerns. However, the increasing size of these models and their limited access make improving their robustness a challenging task. Among various defense strategies, randomized smoothing has shown great potential for LLMs, as it does not require full access to the model's parameters or fine-tuning via adversarial training. However, randomized smoothing involves adding noise to the input before model prediction, and the final model's robustness largely depends on the model's performance on these noise corrupted data. Its effectiveness is often limited by the model's sub-optimal performance on noisy data. To address this issue, we propose to leverage the multitasking nature of LLMs to first denoise the noisy inputs and then to make predictions based on these denoised versions. We call this procedure self-denoised smoothing. Unlike previous denoised smoothing techniques in computer vision, which require training a separate model to enhance the robustness of LLMs, our method offers significantly better efficiency and flexibility. Our experimental results indicate that our method surpasses existing methods in both empirical and certified robustness in defending against adversarial attacks for both downstream tasks and human alignments (i.e., jailbreak attacks). Our code is publicly available at https://github.com/UCSB-NLP-Chang/SelfDenoise

[Arxiv](https://arxiv.org/abs/2404.12274)