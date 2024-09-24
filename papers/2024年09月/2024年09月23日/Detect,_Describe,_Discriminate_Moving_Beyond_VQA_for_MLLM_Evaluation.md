# 检测、描述、区分：迈向超越 VQA 的多模态语言模型评估

发布时间：2024年09月23日

`LLM应用` `计算机视觉` `人工智能`

> Detect, Describe, Discriminate: Moving Beyond VQA for MLLM Evaluation

# 摘要

> 多选题 VQA 虽然能可靠检测特定视觉能力，但模型从选项中选答案比生成答案更简单。我们提出新视角：通过 MLLM 描述极相似图像间细微差异的能力，评估其对特定视觉概念的理解。我们用自检索测试 MLLM 捕捉视觉差异的能力，即用生成描述检索目标图像，另一图像为干扰。D3 基准包含 247 对高度相似图像，模型需：(1) 发现差异，(2) 独特描述目标图像，(3) 区分目标与干扰。D3 自检索在六种视觉模式下进行白盒评估，显示当前模型在细粒度视觉差异辨别上仍有不足，开源模型表现甚至不如随机猜测。

> Visual Question Answering (VQA) with multiple choice questions enables a vision-centric evaluation of Multimodal Large Language Models (MLLMs). Although it reliably checks the existence of specific visual abilities, it is easier for the model to select an answer from multiple choices (VQA evaluation) than to generate the answer itself. In this work, we offer a novel perspective: we evaluate how well an MLLM understands a specific visual concept by its ability to uniquely describe two extremely similar images that differ only in the targeted visual concept. Specifically, we assess the ability of MLLMs to capture specific points of visual differences using self-retrieval, i.e., by retrieving the target image using its generated caption against the other image in the pair serving as the distractor. We curate 247 highly similar image pairs as part of the D3 benchmark. For each image pair, the model is prompted to: (1) Detect a specific visual difference, and (2) Describe the target image uniquely such that it (3) Discriminates the target image from the distractor. Self-retrieval within D3 enables whitebox evaluation across six different visual patterns, revealing that current models struggle to independently discern fine-grained visual differences, with open-source models failing to outperform random guess.

[Arxiv](https://arxiv.org/abs/2409.15125)