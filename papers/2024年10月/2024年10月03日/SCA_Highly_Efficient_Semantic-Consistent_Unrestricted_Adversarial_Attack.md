# SCA：高效且语义一致的无限制对抗攻击

发布时间：2024年10月03日

`LLM应用` `计算机视觉` `网络安全`

> SCA: Highly Efficient Semantic-Consistent Unrestricted Adversarial Attack

# 摘要

> 无限制对抗攻击通过改变图像的语义内容（如颜色或纹理）来生成逼真的对抗样本。近期研究通过扩散反演将图像映射到潜在空间，并引入扰动来操纵高级语义，但常导致去噪输出中的语义失真且效率低下。为此，我们提出了语义一致无限制对抗攻击（SCA）框架，利用反演方法提取易于编辑的噪声图，并借助多模态大语言模型（MLLM）提供语义指导。在MLLM丰富的语义信息支持下，我们使用易于编辑的噪声图进行DDPM去噪，并通过DPM Solver++加速，实现高效且语义一致的采样。相比现有方法，SCA能高效生成几乎无语义变化的对抗样本，首次引入语义一致对抗样本（SCAE）。实验显示，SCA平均比最先进方法快12倍。代码见https://github.com/Pan-Zihao/SCA。

> Unrestricted adversarial attacks typically manipulate the semantic content of an image (e.g., color or texture) to create adversarial examples that are both effective and photorealistic. Recent works have utilized the diffusion inversion process to map images into a latent space, where high-level semantics are manipulated by introducing perturbations. However, they often results in substantial semantic distortions in the denoised output and suffers from low efficiency. In this study, we propose a novel framework called Semantic-Consistent Unrestricted Adversarial Attacks (SCA), which employs an inversion method to extract edit-friendly noise maps and utilizes Multimodal Large Language Model (MLLM) to provide semantic guidance throughout the process. Under the condition of rich semantic information provided by MLLM, we perform the DDPM denoising process of each step using a series of edit-friendly noise maps, and leverage DPM Solver++ to accelerate this process, enabling efficient sampling with semantic consistency. Compared to existing methods, our framework enables the efficient generation of adversarial examples that exhibit minimal discernible semantic changes. Consequently, we for the first time introduce Semantic-Consistent Adversarial Examples (SCAE). Extensive experiments and visualizations have demonstrated the high efficiency of SCA, particularly in being on average 12 times faster than the state-of-the-art attacks. Our code can be found at https://github.com/Pan-Zihao/SCA}{https://github.com/Pan-Zihao/SCA.

[Arxiv](https://arxiv.org/abs/2410.02240)