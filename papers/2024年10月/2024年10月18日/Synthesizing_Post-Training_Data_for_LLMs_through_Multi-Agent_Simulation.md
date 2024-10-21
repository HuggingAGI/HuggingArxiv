# 利用多智能体模拟技术，为大型语言模型生成训练后的数据。

发布时间：2024年10月18日

`Agent` `人工智能`

> Synthesizing Post-Training Data for LLMs through Multi-Agent Simulation

# 摘要

> 训练后是让大型语言模型 (LLM) 遵循人类指令的关键。受 LLM 模拟人类社会成功的启发，我们通过多代理模拟自动生成多样化的文本场景，捕捉真实世界的需求。我们设计了 MATRIX，一个真实且可扩展的多代理模拟器。基于此，我们推出了 MATRIX-Gen，一种场景驱动的指令生成器，用于高度真实的数据合成。实验证明，我们的框架能有效生成通用和特定领域的数据。特别地，在 AlpacaEval 2 和 Arena-Hard 测试中，Llama-3-8B-Base 在仅用 20K 指令-响应对训练后，超越了在 10M 对数据上训练的 Meta 的 Llama-3-8B-Instruct 模型。项目详情请访问 https://github.com/ShuoTang123/MATRIX-Gen。

> Post-training is essential for enabling large language models (LLMs) to follow human instructions. Inspired by the recent success of using LLMs to simulate human society, we leverage multi-agent simulation to automatically generate diverse text-based scenarios, capturing a wide range of real-world human needs. We propose MATRIX, a multi-agent simulator that creates realistic and scalable scenarios. Leveraging these outputs, we introduce a novel scenario-driven instruction generator MATRIX-Gen for controllable and highly realistic data synthesis. Extensive experiments demonstrate that our framework effectively generates both general and domain-specific data. Notably, on AlpacaEval 2 and Arena-Hard benchmarks, Llama-3-8B-Base, post-trained on datasets synthesized by MATRIX-Gen with just 20K instruction-response pairs, outperforms Meta's Llama-3-8B-Instruct model, which was trained on over 10M pairs; see our project at https://github.com/ShuoTang123/MATRIX-Gen.

[Arxiv](https://arxiv.org/abs/2410.14251)