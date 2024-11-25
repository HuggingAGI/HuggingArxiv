# 自适应视频理解代理：借助动态帧采样和反馈驱动推理提升效率

发布时间：2024年10月26日

`Agent` `人工智能`

> Adaptive Video Understanding Agent: Enhancing efficiency with dynamic frame sampling and feedback-driven reasoning

# 摘要

> 理解长格式视频内容面临重大挑战，因其时间复杂度高且所需计算资源庞大。在本研究中，我们提出一种基于代理的方法，借助大型语言模型（LLMs）及其工具运用能力，提升长格式视频理解的效率与效果。我们方法的关键在于查询自适应帧采样，它凭借LLMs的推理能力，实时仅处理最相关的帧，解决了现有方法常出现的采样冗余或无关帧的重要局限。为增强视频理解代理的推理能力，我们利用LLMs的自我反思能力为代理提供口头强化，从而在减少访问帧数的同时提高性能。我们在多个视频理解基准上对该方法进行评估，结果表明它不仅提升了前沿性能，还通过减少采样帧数提高了效率。

> Understanding long-form video content presents significant challenges due to its temporal complexity and the substantial computational resources required. In this work, we propose an agent-based approach to enhance both the efficiency and effectiveness of long-form video understanding by utilizing large language models (LLMs) and their tool-harnessing ability. A key aspect of our method is query-adaptive frame sampling, which leverages the reasoning capabilities of LLMs to process only the most relevant frames in real-time, and addresses an important limitation of existing methods which typically involve sampling redundant or irrelevant frames. To enhance the reasoning abilities of our video-understanding agent, we leverage the self-reflective capabilities of LLMs to provide verbal reinforcement to the agent, which leads to improved performance while minimizing the number of frames accessed. We evaluate our method across several video understanding benchmarks and demonstrate that not only it enhances state-of-the-art performance but also improves efficiency by reducing the number of frames sampled.

[Arxiv](https://arxiv.org/abs/2410.20252)