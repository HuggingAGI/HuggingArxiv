# MMEvol：借助 Evol-Instruct 技术，为多模态大型语言模型注入新活力

发布时间：2024年09月09日

`LLM应用` `人工智能` `计算机视觉`

> MMEvol: Empowering Multimodal Large Language Models with Evol-Instruct

# 摘要

> 多模态大型语言模型 (MLLM) 虽有显著进展，但多模态指令数据的数量和质量仍是瓶颈。手动创建此类数据既耗时又低效，且难以生成高复杂指令。从商业模型（如 GPT-4o、GPT-4V）中提取的指令数据往往过于简单，限制了性能。我们提出 MMEvol，一种结合细粒度感知、认知推理和交互进化的多模态指令数据进化框架，突破数据瓶颈，生成复杂多样的图文指令数据集，增强 MLLM 能力。从初始指令集 SEED-163K 出发，MMEvol 系统扩展指令多样性，整合推理步骤增强认知能力，并从图像中提取详细信息提升视觉理解和鲁棒性。我们用进化数据训练 LLaVA-NeXT，在 13 项视觉语言任务中，平均准确率提升 3.1 分，其中 9 项达到最先进水平。

> The development of Multimodal Large Language Models (MLLMs) has seen significant advancements. However, the quantity and quality of multimodal instruction data have emerged as significant bottlenecks in their progress. Manually creating multimodal instruction data is both time-consuming and inefficient, posing challenges in producing instructions of high complexity. Moreover, distilling instruction data from black-box commercial models (e.g., GPT-4o, GPT-4V) often results in simplistic instruction data, which constrains performance to that of these models. The challenge of curating diverse and complex instruction data remains substantial. We propose MMEvol, a novel multimodal instruction data evolution framework that combines fine-grained perception evolution, cognitive reasoning evolution, and interaction evolution. This iterative approach breaks through data quality bottlenecks to generate a complex and diverse image-text instruction dataset, thereby empowering MLLMs with enhanced capabilities. Beginning with an initial set of instructions, SEED-163K, we utilize MMEvol to systematically broadens the diversity of instruction types, integrates reasoning steps to enhance cognitive capabilities, and extracts detailed information from images to improve visual understanding and robustness. To comprehensively evaluate the effectiveness of our data, we train LLaVA-NeXT using the evolved data and conduct experiments across 13 vision-language tasks. Compared to the baseline trained with seed data, our approach achieves an average accuracy improvement of 3.1 points and reaches state-of-the-art (SOTA) performance on 9 of these tasks.

[Arxiv](https://arxiv.org/abs/2409.05840)