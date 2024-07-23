# 视觉-语言模型间的通用图像越狱何时发生转移？

发布时间：2024年07月21日

`LLM应用` `人工智能` `网络安全`

> When Do Universal Image Jailbreaks Transfer Between Vision-Language Models?

# 摘要

> 将新模态融入尖端AI系统，虽然带来了激动人心的功能，但也增加了系统被恶意操纵的风险。本研究聚焦于视觉-语言模型（VLMs），这类模型能根据视觉与文本输入生成文本。我们开展了一项大规模实证研究，评估了基于梯度的通用图像“越狱”技术的可迁移性，涉及超过40种开放参数的VLM，包括我们新发布的18种。研究发现，获取可迁移的图像越狱技术极为困难。即便针对单个或一组VLM成功实施越狱，其效果也难以迁移至其他VLM。迁移效果不受VLM间视觉骨干或语言模型是否匹配、语言模型是否经过指令遵循或安全对齐训练等因素影响。仅在相同预训练和初始化的VLM间，或同一VLM的不同训练阶段间，观察到有限的迁移效果。基于此，我们进一步证明，通过攻击更多“高度相似”的VLM，可以显著提升对特定目标VLM的越狱迁移效果。这一发现与现有研究形成对比，现有研究显示语言模型易受通用文本越狱攻击，图像分类器易受对抗性攻击，而VLM似乎对基于梯度的迁移攻击更具抵抗力。

> The integration of new modalities into frontier AI systems offers exciting capabilities, but also increases the possibility such systems can be adversarially manipulated in undesirable ways. In this work, we focus on a popular class of vision-language models (VLMs) that generate text outputs conditioned on visual and textual inputs. We conducted a large-scale empirical study to assess the transferability of gradient-based universal image "jailbreaks" using a diverse set of over 40 open-parameter VLMs, including 18 new VLMs that we publicly release. Overall, we find that transferable gradient-based image jailbreaks are extremely difficult to obtain. When an image jailbreak is optimized against a single VLM or against an ensemble of VLMs, the jailbreak successfully jailbreaks the attacked VLM(s), but exhibits little-to-no transfer to any other VLMs; transfer is not affected by whether the attacked and target VLMs possess matching vision backbones or language models, whether the language model underwent instruction-following and/or safety-alignment training, or many other factors. Only two settings display partially successful transfer: between identically-pretrained and identically-initialized VLMs with slightly different VLM training data, and between different training checkpoints of a single VLM. Leveraging these results, we then demonstrate that transfer can be significantly improved against a specific target VLM by attacking larger ensembles of "highly-similar" VLMs. These results stand in stark contrast to existing evidence of universal and transferable text jailbreaks against language models and transferable adversarial attacks against image classifiers, suggesting that VLMs may be more robust to gradient-based transfer attacks.

[Arxiv](https://arxiv.org/abs/2407.15211)