# TextHawk2：一款大型视觉语言模型，以 16 倍更少的标记在双语 OCR 和定位任务中大放异彩。

发布时间：2024年10月07日

`LLM应用` `计算机视觉`

> TextHawk2: A Large Vision-Language Model Excels in Bilingual OCR and Grounding with 16x Fewer Tokens

# 摘要

> TextHawk2 是一款双语视觉-语言模型，专为高效处理密集文本阅读和图像物体定位而设计。相较于之前的模型，如 GPT-4o，TextHawk2 在同时完成这两项任务时表现更为出色，且每张图像所需的标记数量减少了 16 倍，大大降低了资源消耗。其关键创新包括：标记压缩技术，使模型训练和部署更加高效；视觉编码器的强化，使其在处理中文 OCR 和基础任务时更具潜力；以及数据源的多样化，确保了预训练数据的广泛性和代表性。在多个基准测试中，TextHawk2 均表现优异，超越了同规模的闭源模型，如在 OCRBench 上准确率达到 78.4%，在 ChartQA 上达到 81.4%，在 DocVQA 上 ANLS 达到 89.6%，在 RefCOCOg-test 上准确率@0.5 达到 88.1%。

> Reading dense text and locating objects within images are fundamental abilities for Large Vision-Language Models (LVLMs) tasked with advanced jobs. Previous LVLMs, including superior proprietary models like GPT-4o, have struggled to excel in both tasks simultaneously. Moreover, previous LVLMs with fine-grained perception cost thousands of tokens per image, making them resource-intensive. We present TextHawk2, a bilingual LVLM featuring efficient fine-grained perception and demonstrating cutting-edge performance across general-purpose, OCR, and grounding tasks with 16 times fewer image tokens. Critical improvements include: (1) Token Compression: Building on the efficient architecture of its predecessor, TextHawk2 significantly reduces the number of tokens per image by 16 times, facilitating training and deployment of the TextHawk series with minimal resources. (2) Visual Encoder Reinforcement: We enhance the visual encoder through LVLM co-training, unlocking its potential for previously unseen tasks like Chinese OCR and grounding. (3) Data Diversity: We maintain a comparable scale of 100 million samples while diversifying the sources of pre-training data. We assess TextHawk2 across multiple benchmarks, where it consistently delivers superior performance and outperforms closed-source models of similar scale, such as achieving 78.4% accuracy on OCRBench, 81.4% accuracy on ChartQA, 89.6% ANLS on DocVQA, and 88.1% accuracy@0.5 on RefCOCOg-test.

[Arxiv](https://arxiv.org/abs/2410.05261)