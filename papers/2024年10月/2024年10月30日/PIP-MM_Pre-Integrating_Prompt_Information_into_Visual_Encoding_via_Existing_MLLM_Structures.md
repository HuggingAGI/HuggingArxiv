# PIP-MM：借助现有的 MLLM 结构，将提示信息预先融入视觉编码

发布时间：2024年10月30日

`LLM应用` `多模态` `语言模型`

> PIP-MM: Pre-Integrating Prompt Information into Visual Encoding via Existing MLLM Structures

# 摘要

> 多模态大型语言模型（MLLMs）通过融合视觉信息，激活了大型语言模型（LLMs）解决视觉语言任务的能力。现有的 MLLMs 通常采用这样的方法：利用图像编码器提取视觉特征，通过适配器把这些特征转化为视觉标记，再将其与提示一同整合进 LLM。但由于图像编码过程不依赖提示，所提取的视觉特征仅能对图像进行粗略描述，难以聚焦提示的需求。一方面，图像特征容易缺失提示指定对象的信息，致使响应效果不佳。另一方面，视觉特征包含大量无关信息，这不但加重了内存负担，还削弱了生成效果。为应对上述问题，我们提出了	extbf{PIP-MM}，这是一个利用 MLLMs 现有模块将提示信息预先融入视觉编码过程的框架。具体而言，我们借助 MLLM 中的冻结 LLM 把输入提示矢量化，从而概括提示的要求。接着，将提示向量输入我们训练的多层感知机（MLP），使其与视觉输入要求相匹配，然后替换图像编码器中的类别嵌入。由于我们的模型仅需添加一个可训练的 MLP，所以它能应用于任何 MLLM。为验证 PIP-MM 的有效性，我们在多个基准上开展了实验。自动评估指标和人工评估都显示 PIP-MM 性能强劲。尤其值得一提的是，即便视觉标记减少一半，我们的模型仍能保持出色的生成结果。

> The Multimodal Large Language Models (MLLMs) have activated the capabilitiesof Large Language Models (LLMs) in solving visual-language tasks by integratingvisual information. The prevailing approach in existing MLLMs involvesemploying an image encoder to extract visual features, converting thesefeatures into visual tokens via an adapter, and then integrating them with theprompt into the LLM. However, because the process of image encoding isprompt-agnostic, the extracted visual features only provide a coarsedescription of the image, impossible to focus on the requirements of theprompt. On one hand, it is easy for image features to lack information aboutthe prompt-specified objects, resulting in unsatisfactory responses. On theother hand, the visual features contain a large amount of irrelevantinformation, which not only increases the burden on memory but also worsens thegeneration effectiveness. To address the aforementioned issues, we propose\textbf{PIP-MM}, a framework that \textbf{P}re-\textbf{I}ntegrates\textbf{P}rompt information into the visual encoding process using existingmodules of MLLMs. Specifically, We utilize the frozen LLM in the MLLM tovectorize the input prompt, which summarizes the requirements of the prompt.Then, we input the prompt vector into our trained Multi-Layer Perceptron (MLP)to align with the visual input requirements, and subsequently replace the classembedding in the image encoder. Since our model only requires adding atrainable MLP, it can be applied to any MLLM. To validate the effectiveness ofPIP-MM, we conducted experiments on multiple benchmarks. Automated evaluationmetrics and manual assessments demonstrate the strong performance of PIP-MM.Particularly noteworthy is that our model maintains excellent generationresults even when half of the visual tokens are reduced.

[Arxiv](https://arxiv.org/abs/2410.23089)