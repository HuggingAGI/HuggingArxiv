# 逐一列举：开启多模态大型语言模型的新数据源与学习模式

发布时间：2024年04月25日

`LLM应用` `计算机视觉` `人工智能`

> List Items One by One: A New Data Source and Learning Paradigm for Multimodal LLMs

# 摘要

> Set-of-Mark（SoM）提示技术通过在图像中嵌入标签，激发了 GPT-4V 的视觉定位功能，使得模型能够将视觉元素与特定的标签相关联。这些标签采用字母数字编码，可以通过文本标记进行索引，以便于引用。尽管 GPT-4V 展现出卓越的性能，我们发现其他多模态大型语言模型（MLLMs）在识别这些视觉标签上存在挑战。为了帮助开源模型掌握 SoM 提示，我们提出了一种新颖的学习模式——“逐一列举项”，这一模式要求模型依照标签的字母数字顺序，逐一列举并描述图像中的所有视觉标签。通过将我们精选的数据集与现有的视觉指令调整数据集相结合，我们成功地为现有的 MLLMs 赋予了 SoM 提示的能力。我们进一步在五个 MLLM 基准测试中评估了我们的微调 SoM 模型，发现即便是在较小规模的数据集（10k-30k 张带有标签的图像）上，也能显著提升 MLLMs 的视觉推理能力，并减少幻觉现象。令人意外的是，即使在推理过程中省略了输入图像中的视觉标签，这些提升依然能够保持。这表明“逐一列举项”有潜力成为训练 MLLMs 的新范式，它通过在训练阶段使用视觉标签，加强了对象与文本之间的对应关系。最后，我们通过对训练好的模型进行深入分析，揭示了 SoM 的内在工作机制。相关代码和数据已在 \url{https://github.com/zzxslp/SoM-LLaVA} 上公开。

> Set-of-Mark (SoM) Prompting unleashes the visual grounding capability of GPT-4V, by enabling the model to associate visual objects with tags inserted on the image. These tags, marked with alphanumerics, can be indexed via text tokens for easy reference. Despite the extraordinary performance from GPT-4V, we observe that other Multimodal Large Language Models (MLLMs) struggle to understand these visual tags. To promote the learning of SoM prompting for open-source models, we propose a new learning paradigm: "list items one by one," which asks the model to enumerate and describe all visual tags placed on the image following the alphanumeric orders of tags. By integrating our curated dataset with other visual instruction tuning datasets, we are able to equip existing MLLMs with the SoM prompting ability. Furthermore, we evaluate our finetuned SoM models on five MLLM benchmarks. We find that this new dataset, even in a relatively small size (10k-30k images with tags), significantly enhances visual reasoning capabilities and reduces hallucinations for MLLMs. Perhaps surprisingly, these improvements persist even when the visual tags are omitted from input images during inference. This suggests the potential of "list items one by one" as a new paradigm for training MLLMs, which strengthens the object-text alignment through the use of visual tags in the training stage. Finally, we conduct analyses by probing trained models to understand the working mechanism of SoM. Our code and data are available at \url{https://github.com/zzxslp/SoM-LLaVA}.

[Arxiv](https://arxiv.org/abs/2404.16375)