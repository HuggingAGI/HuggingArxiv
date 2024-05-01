# Espresso：文本到图像模型中的稳健概念筛选

发布时间：2024年04月29日

`LLM应用` `图像生成` `内容过滤`

> Espresso: Robust Concept Filtering in Text-to-Image Models

# 摘要

> 基于扩散原理的文本到图像（T2I）模型能够根据文本提示生成高清晰度的图像，这些模型通常在互联网上搜集的大型数据集上进行训练，但这些数据集可能潜藏不当内容，如侵权或不适宜的内容。在剔除了训练数据中的不当概念后，重新训练T2I模型不仅效率低下，还会影响其功能性。因此，迫切需要一种能够有效移除不当概念、保留适当概念的实用性，并且能够抵御对抗性提示的概念移除技术（CRTs）。目前，尚无现有的过滤和微调CRTs能够完全满足这些需求。我们在此推出Espresso，这是首个基于对比性语言-图像预训练（CLIP）的鲁棒性概念过滤器。Espresso通过将生成图像的嵌入向量投影到联合文本-图像嵌入空间中，连接不可接受与可接受概念的向量上，来辨识出不当概念。这种方法通过限制对手只能在该向量上，朝向可接受概念的方向添加噪声，从而确保了系统的鲁棒性。Espresso进一步经过微调，以区分可接受与不可接受概念的嵌入，同时保持它们与图像嵌入的对应关系，这样既保证了效果也兼顾了实用性。我们在11个概念上对Espresso进行了评估，结果表明其具有高效果（在不可接受概念上的CLIP准确率约为5%），实用性（在可接受概念上的CLIP得分约为93%），以及鲁棒性（在对抗性提示的不可接受概念上的CLIP准确率约为4%）。最后，我们为Espresso面对对抗性提示的认证鲁棒性提供了理论界限，并进行了实证分析。

> Diffusion-based text-to-image (T2I) models generate high-fidelity images for given textual prompts. They are trained on large datasets scraped from the Internet, potentially containing unacceptable concepts (e.g., copyright infringing or unsafe). Retraining T2I models after filtering out unacceptable concepts in the training data is inefficient and degrades utility. Hence, there is a need for concept removal techniques (CRTs) which are effective in removing unacceptable concepts, utility-preserving on acceptable concepts, and robust against evasion with adversarial prompts. None of the prior filtering and fine-tuning CRTs satisfy all these requirements simultaneously.
  We introduce Espresso, the first robust concept filter based on Contrastive Language-Image Pre-Training (CLIP). It identifies unacceptable concepts by projecting the generated image's embedding onto the vector connecting unacceptable and acceptable concepts in the joint text-image embedding space. This ensures robustness by restricting the adversary to adding noise only along this vector, in the direction of the acceptable concept. Further fine-tuning Espresso to separate embeddings of acceptable and unacceptable concepts, while preserving their pairing with image embeddings, ensures both effectiveness and utility. We evaluate Espresso on eleven concepts to show that it is effective (~5% CLIP accuracy on unacceptable concepts), utility-preserving (~93% normalized CLIP score on acceptable concepts), and robust (~4% CLIP accuracy on adversarial prompts for unacceptable concepts). Finally, we present theoretical bounds for the certified robustness of Espresso against adversarial prompts, and an empirical analysis.

[Arxiv](https://arxiv.org/abs/2404.19227)