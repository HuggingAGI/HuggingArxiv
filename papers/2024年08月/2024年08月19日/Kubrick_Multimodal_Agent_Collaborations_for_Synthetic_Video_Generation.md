# Kubrick：多模态代理协作，助力合成视频创作

发布时间：2024年08月19日

`Agent` `电影制作` `视频生成`

> Kubrick: Multimodal Agent Collaborations for Synthetic Video Generation

# 摘要

> 文本转视频生成领域长期由端到端扩散模型和自回归模型主导。尽管这些模型提供了多样性，但它们在物理正确性、光照效果、摄像机运动和时间一致性方面存在不足。相比之下，电影行业采用手动编辑的3D CGI，虽解决了这些问题，但过程繁琐且需专业合作。本文提出了一种基于VLM代理协作的自动视频生成流程。通过自然语言描述，多个VLM代理协同工作，自动生成与描述匹配的Blender脚本。借鉴电影制作灵感，结合Blender电影制作知识，导演代理将文本描述分解为子任务，程序员代理据此编写Python脚本，审查员代理则提供反馈以优化脚本。最终生成的视频在质量和指令遵循方面超越了商业模型，并在用户研究中表现出色。

> Text-to-video generation has been dominated by end-to-end diffusion-based or autoregressive models. On one hand, those novel models provide plausible versatility, but they are criticized for physical correctness, shading and illumination, camera motion, and temporal consistency. On the other hand, film industry relies on manually-edited Computer-Generated Imagery (CGI) using 3D modeling software. Human-directed 3D synthetic videos and animations address the aforementioned shortcomings, but it is extremely tedious and requires tight collaboration between movie makers and 3D rendering experts. In this paper, we introduce an automatic synthetic video generation pipeline based on Vision Large Language Model (VLM) agent collaborations. Given a natural language description of a video, multiple VLM agents auto-direct various processes of the generation pipeline. They cooperate to create Blender scripts which render a video that best aligns with the given description. Based on film making inspiration and augmented with Blender-based movie making knowledge, the Director agent decomposes the input text-based video description into sub-processes. For each sub-process, the Programmer agent produces Python-based Blender scripts based on customized function composing and API calling. Then, the Reviewer agent, augmented with knowledge of video reviewing, character motion coordinates, and intermediate screenshots uses its compositional reasoning ability to provide feedback to the Programmer agent. The Programmer agent iteratively improves the scripts to yield the best overall video outcome. Our generated videos show better quality than commercial video generation models in 5 metrics on video quality and instruction-following performance. Moreover, our framework outperforms other approaches in a comprehensive user study on quality, consistency, and rationality.

[Arxiv](https://arxiv.org/abs/2408.10453)