# JourneyBench：一个集挑战性与综合性于一体的生成图像视觉语言理解基准

发布时间：2024年09月19日

`LLM应用` `人工智能` `计算机视觉`

> JourneyBench: A Challenging One-Stop Vision-Language Understanding Benchmark of Generated Images

# 摘要

> 现有的视觉-语言基准主要基于常见场景中的对象图像，导致多模态大模型仅凭浅层视觉理解和语言偏差就能表现良好。然而，这并不意味着它们具备强大的视觉理解能力。为此，我们推出了 JourneyBench，一个全面的人工注释生成图像基准，旨在评估模型在五个任务中的细粒度多模态推理能力。JourneyBench 要求模型在不寻常的想象场景中进行细粒度推理，超越了语言偏差和整体图像理解。我们测试了最先进的模型，发现即使在细粒度维度上，这些模型也面临巨大挑战，表明其视觉推理能力远不如表面看起来那么强大。我们探讨了这些发现的意义，并提出了未来研究的方向。

> Existing vision-language understanding benchmarks largely consist of images of objects in their usual contexts. As a consequence, recent multimodal large language models can perform well with only a shallow visual understanding by relying on background language biases. Thus, strong performance on these benchmarks does not necessarily correlate with strong visual understanding. In this paper, we release JourneyBench, a comprehensive human-annotated benchmark of generated images designed to assess the model's fine-grained multimodal reasoning abilities across five tasks: complementary multimodal chain of thought, multi-image VQA, imaginary image captioning, VQA with hallucination triggers, and fine-grained retrieval with sample-specific distractors. Unlike existing benchmarks, JourneyBench explicitly requires fine-grained multimodal reasoning in unusual imaginary scenarios where language bias and holistic image gist are insufficient. We benchmark state-of-the-art models on JourneyBench and analyze performance along a number of fine-grained dimensions. Results across all five tasks show that JourneyBench is exceptionally challenging for even the best models, indicating that models' visual reasoning abilities are not as strong as they first appear. We discuss the implications of our findings and propose avenues for further research.

[Arxiv](https://arxiv.org/abs/2409.12953)