# 逐一列举：开启多模态大型语言模型（LLMs）的新数据源与学习模式。

发布时间：2024年04月25日

`LLM应用` `计算机视觉` `人工智能`

> List Items One by One: A New Data Source and Learning Paradigm for Multimodal LLMs

# 摘要

> Set-of-Mark（SoM）提示技术赋予了 GPT-4V 强大的视觉定位功能，它通过让模型将视觉对象与图像上的标签相联系，实现了这一点。这些标签采用字母数字编码，便于通过文本标记进行索引引用。尽管 GPT-4V 的性能卓越，我们发现其他多模态大型语言模型（MLLMs）在理解这些视觉标签上存在挑战。为此，我们提出了一种创新的学习模式——“逐一列举”，要求模型按标签的字母数字顺序，逐一列举并描述图像上的所有视觉标签。通过结合我们精选的数据集和现有的视觉指令调整数据集，我们成功地为现有的 MLLMs 增加了 SoM 提示的功能。我们在五个 MLLM 基准测试中对我们的微调 SoM 模型进行了评估，发现即使是在规模较小（10k-30k 带标签图像）的数据集上，也能显著提升 MLLMs 的视觉推理能力，并减少幻觉现象。令人惊讶的是，即使在推理过程中省略了输入图像中的视觉标签，这些提升依然存在。这表明“逐一列举”模式在训练 MLLMs 时，通过训练阶段使用视觉标签，有效加强了对象与文本之间的对齐。最后，我们通过深入分析训练模型，揭示了 SoM 的工作机制。相关代码和数据已在 \url{https://github.com/zzxslp/SoM-LLaVA} 上公开。

> Set-of-Mark (SoM) Prompting unleashes the visual grounding capability of GPT-4V, by enabling the model to associate visual objects with tags inserted on the image. These tags, marked with alphanumerics, can be indexed via text tokens for easy reference. Despite the extraordinary performance from GPT-4V, we observe that other Multimodal Large Language Models (MLLMs) struggle to understand these visual tags. To promote the learning of SoM prompting for open-source models, we propose a new learning paradigm: "list items one by one," which asks the model to enumerate and describe all visual tags placed on the image following the alphanumeric orders of tags. By integrating our curated dataset with other visual instruction tuning datasets, we are able to equip existing MLLMs with the SoM prompting ability. Furthermore, we evaluate our finetuned SoM models on five MLLM benchmarks. We find that this new dataset, even in a relatively small size (10k-30k images with tags), significantly enhances visual reasoning capabilities and reduces hallucinations for MLLMs. Perhaps surprisingly, these improvements persist even when the visual tags are omitted from input images during inference. This suggests the potential of "list items one by one" as a new paradigm for training MLLMs, which strengthens the object-text alignment through the use of visual tags in the training stage. Finally, we conduct analyses by probing trained models to understand the working mechanism of SoM. Our code and data are available at \url{https://github.com/zzxslp/SoM-LLaVA}.

[Arxiv](https://arxiv.org/abs/2404.16375)