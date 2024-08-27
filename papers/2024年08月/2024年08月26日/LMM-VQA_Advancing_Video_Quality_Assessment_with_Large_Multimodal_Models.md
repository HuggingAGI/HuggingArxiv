# LMM-VQA：借助大型多模态模型，推动视频质量评估的进步

发布时间：2024年08月26日

`LLM应用` `流媒体` `视频质量评估`

> LMM-VQA: Advancing Video Quality Assessment with Large Multimodal Models

# 摘要

> 随着流媒体平台上视频数量的激增，有效监控和优化视频质量的需求日益迫切。尽管视频质量评估（VQA）任务因内容多样性和时空失真复杂性而充满挑战，但大型多模态模型（如GPT-4V）在视觉理解方面的强大能力为我们提供了新的解决方案。我们首次提出了大型多模态视频质量评估（LMM-VQA）模型，通过创新的空间-时间视觉建模策略，精准提取视频质量特征。该模型将质量评估问题转化为问答任务，并设计了专门的空间-时间视觉编码器，有效提取并映射视频特征至语言空间，最终通过大型语言模型生成精确的质量评分。实验结果显示，LMM-VQA在多个VQA基准测试中表现卓越，泛化能力显著提升。此外，其在一般视频理解任务中的优异表现，进一步证明了其全面有效性。相关代码即将在GitHub上公开。

> The explosive growth of videos on streaming media platforms has underscored the urgent need for effective video quality assessment (VQA) algorithms to monitor and perceptually optimize the quality of streaming videos. However, VQA remains an extremely challenging task due to the diverse video content and the complex spatial and temporal distortions, thus necessitating more advanced methods to address these issues. Nowadays, large multimodal models (LMMs), such as GPT-4V, have exhibited strong capabilities for various visual understanding tasks, motivating us to leverage the powerful multimodal representation ability of LMMs to solve the VQA task. Therefore, we propose the first Large Multi-Modal Video Quality Assessment (LMM-VQA) model, which introduces a novel spatiotemporal visual modeling strategy for quality-aware feature extraction. Specifically, we first reformulate the quality regression problem into a question and answering (Q&A) task and construct Q&A prompts for VQA instruction tuning. Then, we design a spatiotemporal vision encoder to extract spatial and temporal features to represent the quality characteristics of videos, which are subsequently mapped into the language space by the spatiotemporal projector for modality alignment. Finally, the aligned visual tokens and the quality-inquired text tokens are aggregated as inputs for the large language model (LLM) to generate the quality score and level. Extensive experiments demonstrate that LMM-VQA achieves state-of-the-art performance across five VQA benchmarks, exhibiting an average improvement of $5\%$ in generalization ability over existing methods. Furthermore, due to the advanced design of the spatiotemporal encoder and projector, LMM-VQA also performs exceptionally well on general video understanding tasks, further validating its effectiveness. Our code will be released at https://github.com/Sueqk/LMM-VQA.

[Arxiv](https://arxiv.org/abs/2408.14008)