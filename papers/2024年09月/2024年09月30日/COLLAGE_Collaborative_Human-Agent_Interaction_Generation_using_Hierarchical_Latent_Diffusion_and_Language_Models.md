# COLLAGE：通过分层潜在扩散与语言模型实现人机协作交互生成

发布时间：2024年09月30日

`LLM应用` `机器人` `计算机视觉`

> COLLAGE: Collaborative Human-Agent Interaction Generation using Hierarchical Latent Diffusion and Language Models

# 摘要

> 我们提出了 COLLAGE 框架，利用 LLM 和分层 VQ-VAEs 生成协作的代理-对象-代理交互。通过结合 LLM 的知识和推理能力，我们的模型解决了数据集不足的问题，并利用分层 VQ-VAE 捕捉多层次的运动特征，避免冗余，实现高效的多分辨率表示。我们引入的扩散模型在潜在空间中运行，结合 LLM 生成的运动规划提示，实现更具控制性和多样性的运动生成。实验结果显示，COLLAGE 在生成真实且多样的协作交互方面优于现有方法，为机器人、图形和计算机视觉等领域建模复杂交互提供了新思路。

> We propose a novel framework COLLAGE for generating collaborative agent-object-agent interactions by leveraging large language models (LLMs) and hierarchical motion-specific vector-quantized variational autoencoders (VQ-VAEs). Our model addresses the lack of rich datasets in this domain by incorporating the knowledge and reasoning abilities of LLMs to guide a generative diffusion model. The hierarchical VQ-VAE architecture captures different motion-specific characteristics at multiple levels of abstraction, avoiding redundant concepts and enabling efficient multi-resolution representation. We introduce a diffusion model that operates in the latent space and incorporates LLM-generated motion planning cues to guide the denoising process, resulting in prompt-specific motion generation with greater control and diversity. Experimental results on the CORE-4D, and InterHuman datasets demonstrate the effectiveness of our approach in generating realistic and diverse collaborative human-object-human interactions, outperforming state-of-the-art methods. Our work opens up new possibilities for modeling complex interactions in various domains, such as robotics, graphics and computer vision.

[Arxiv](https://arxiv.org/abs/2409.20502)