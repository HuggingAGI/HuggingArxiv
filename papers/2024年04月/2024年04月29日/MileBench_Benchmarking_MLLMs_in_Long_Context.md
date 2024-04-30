# MileBench：长文本场景下的大型机器学习语言模型性能评估

发布时间：2024年04月29日

`LLM应用` `人工智能` `机器学习`

> MileBench: Benchmarking MLLMs in Long Context

# 摘要

> 尽管多模态大型语言模型（MLLMs）在标准测试中表现卓越，但其在现实世界中的长文本、多图像任务中的表现尚不明确，因为现有测试往往局限于单一图像和短文本。为了克服这一局限，我们推出了MileBench，这是一个创新的评估工具，专门用于检验MLLMs处理多模态长文本的能力。MileBench包含多模态长文本和多样化任务，旨在全面测试模型的理解与生成能力。我们设计了诊断性和现实性两套评估体系，以系统化地评价MLLMs对长文本的适应性和在长文本环境中的任务完成能力。通过对20种模型的测试，我们发现尽管闭源的GPT-4(Vision)和Gemini 1.5领先于其他模型，但大多数开源MLLMs在处理长文本时仍面临挑战。特别值得注意的是，图像数量的增加会导致性能差异更加显著。我们强烈建议学术界和工业界加大研究力度，以提升MLLMs在长文本处理上的能力，特别是在多图像环境中的应用。

> Despite the advancements and impressive performance of Multimodal Large Language Models (MLLMs) on benchmarks, their effectiveness in real-world, long-context, and multi-image tasks is unclear due to the benchmarks' limited scope. Existing benchmarks often focus on single-image and short-text samples, and when assessing multi-image tasks, they either limit the image count or focus on specific task (e.g time-series captioning), potentially obscuring the performance challenges of MLLMs. To address these limitations, we introduce MileBench, a pioneering benchmark designed to test the MultImodal Long-contExt capabilities of MLLMs. This benchmark comprises not only multimodal long contexts, but also multiple tasks requiring both comprehension and generation. We establish two distinct evaluation sets, diagnostic and realistic, to systematically assess MLLMs' long-context adaptation capacity and their ability to complete tasks in long-context scenarios. Our experimental results, obtained from testing 20 models, revealed that while the closed-source GPT-4(Vision) and Gemini 1.5 outperform others, most open-source MLLMs struggle in long-context situations. Interestingly, the performance gap tends to widen with an increase in the number of images. We strongly encourage an intensification of research efforts towards enhancing MLLMs' long-context capabilities, especially in scenarios involving multiple images.

[Arxiv](https://arxiv.org/abs/2404.18532)