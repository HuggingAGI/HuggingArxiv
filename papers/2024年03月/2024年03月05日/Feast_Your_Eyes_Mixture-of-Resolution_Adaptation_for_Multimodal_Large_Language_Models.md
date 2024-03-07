# [标题生动翻译：“饱览盛宴”：探究多模态大型语言模型中的混合分辨率自适应技术](https://arxiv.org/abs/2403.03003)

> Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large Language Models

发布时间：2024年03月05日

> 虽然现有MLLM在精细化视觉识别上的表现已有显著提升，但仍有欠缺。我们另辟蹊径，从图像分辨率角度出发发现，巧妙融合高低分辨率视觉特征能有效弥补这一短板。据此，我们创新性地提出了适用于MLLM的混合分辨率适应方案——MRA。MRA针对不同分辨率图像构建双视觉通路，并借助新型MR-Adapters将高分辨率视觉信息融入低分辨率通路，同时大大缩短了MLLM的输入序列长度。为了验证MRA的实际效果，我们将该方法应用于新锐MLLM LLaVA，升级得到LLaVA-HR。在涵盖11项VL任务的大规模实验中，LLaVA-HR在8项任务上明显优于其他MLLM，例如TextVQA任务性能提升了+9.4%。更值得一提的是，运用MRA技术后，LLaVA-HR无论在训练还是推理阶段都能保持高效运行，如仅需20小时完成训练，推理速度较LLaVA-1.5提高3倍。相关源代码已开放至GitHub：https://github.com/luogen1996/LLaVA-HR。

> Despite remarkable progress, existing multimodal large language models (MLLMs) are still inferior in granular visual recognition. Contrary to previous works, we study this problem from the perspective of image resolution, and reveal that a combination of low- and high-resolution visual features can effectively mitigate this shortcoming. Based on this observation, we propose a novel and efficient method for MLLMs, termed Mixture-of-Resolution Adaptation (MRA). In particular, MRA adopts two visual pathways for images with different resolutions, where high-resolution visual information is embedded into the low-resolution pathway via the novel mixture-of-resolution adapters (MR-Adapters). This design also greatly reduces the input sequence length of MLLMs. To validate MRA, we apply it to a recent MLLM called LLaVA, and term the new model LLaVA-HR. We conduct extensive experiments on 11 vision-language (VL) tasks, which show that LLaVA-HR outperforms existing MLLMs on 8 VL tasks, e.g., +9.4% on TextVQA. More importantly, both training and inference of LLaVA-HR remain efficient with MRA, e.g., 20 training hours and 3$\times$ inference speed than LLaVA-1.5. Source codes are released at: https://github.com/luogen1996/LLaVA-HR.

`LLM应用`