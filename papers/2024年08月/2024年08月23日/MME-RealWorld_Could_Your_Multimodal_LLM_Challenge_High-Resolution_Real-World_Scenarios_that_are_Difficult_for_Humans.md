# MME-RealWorld：你的多模态LLM能否应对那些连人类都感到棘手的高分辨率现实场景？

发布时间：2024年08月23日

`LLM应用` `计算机视觉` `人工智能`

> MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?

# 摘要

> 近期，多模态大型语言模型的全面评估在研究领域备受瞩目。然而，现有基准存在诸多障碍，如小规模数据导致的性能波动、模型依赖注释带来的数据质量限制，以及因图像分辨率不足而降低的任务难度。为此，我们推出了MME-RealWorld基准，通过收集并精选超过30万张图像，由25名专业注释者和7位MLLM专家共同完成，形成了涵盖5大现实场景、43个子任务的29,429个问答对，其难度之高，连人类也感到挑战。MME-RealWorld不仅是当前最大规模的手动注释基准，更以其高分辨率和现实应用导向脱颖而出。我们评估了包括GPT-4o、Gemini 1.5 Pro和Claude 3.5 Sonnet在内的28个顶尖MLLM，结果显示，即便是最先进的模型，也难以达到60%的准确率，凸显了高分辨率图像感知与复杂场景理解的紧迫挑战。相关数据与评估代码已公开于https://mme-realworld.github.io/。

> Comprehensive evaluation of Multimodal Large Language Models (MLLMs) has recently garnered widespread attention in the research community. However, we observe that existing benchmarks present several common barriers that make it difficult to measure the significant challenges that models face in the real world, including: 1) small data scale leads to a large performance variance; 2) reliance on model-based annotations results in restricted data quality; 3) insufficient task difficulty, especially caused by the limited image resolution. To tackle these issues, we introduce MME-RealWorld. Specifically, we collect more than $300$K images from public datasets and the Internet, filtering $13,366$ high-quality images for annotation. This involves the efforts of professional $25$ annotators and $7$ experts in MLLMs, contributing to $29,429$ question-answer pairs that cover $43$ subtasks across $5$ real-world scenarios, extremely challenging even for humans. As far as we know, MME-RealWorld is the largest manually annotated benchmark to date, featuring the highest resolution and a targeted focus on real-world applications. We further conduct a thorough evaluation involving $28$ prominent MLLMs, such as GPT-4o, Gemini 1.5 Pro, and Claude 3.5 Sonnet. Our results show that even the most advanced models struggle with our benchmarks, where none of them reach $60\%$ accuracy. The challenges of perceiving high-resolution images and understanding complex real-world scenarios remain urgent issues to be addressed. The data and evaluation code are released at https://mme-realworld.github.io/ .

[Arxiv](https://arxiv.org/abs/2408.13257)