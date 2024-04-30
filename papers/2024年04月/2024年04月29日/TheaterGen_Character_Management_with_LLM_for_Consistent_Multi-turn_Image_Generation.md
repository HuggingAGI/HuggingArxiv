# TheaterGen：运用大型语言模型精心管理角色，打造连贯的多轮次图像生成体验

发布时间：2024年04月29日

`LLM应用` `图像生成`

> TheaterGen: Character Management with LLM for Consistent Multi-turn Image Generation

# 摘要

> 最新进展的扩散模型能够根据文本创作出高品质且引人注目的图像。但在现实世界中需求强烈的多轮次图像生成任务中，保持图像与文本之间的语义连贯性以及同一主题在连续交互中的上下文连贯性，仍然是一大挑战。为应对这一挑战，我们推出了TheaterGen——一个无需训练的框架，它结合了大型语言模型（LLMs）与文本到图像（T2I）模型，以实现多轮次图像生成。在这个框架中，LLMs充当“编剧”，进行多轮互动，创建并管理一个标准化的提示脚本，涵盖目标图像中每个角色的提示和布局设计。据此，TheaterGen生成一系列角色图像并提炼出指导信息，这类似于“彩排”阶段。紧接着，TheaterGen将提示脚本和指导信息整合到T2I扩散模型的逆向去噪流程中，生成最终图像，仿佛在进行“最终演出”。通过有效管理提示脚本和角色图像，TheaterGen显著提升了合成图像的语义和上下文连贯性。此外，我们还推出了一个专门的基准测试集CMIGBench（一致性多轮图像生成基准测试），包含8000条多轮指令。与以往的多轮次基准测试不同，CMIGBench不预设角色定义，而是全面包含了故事生成和多轮编辑任务，以进行综合评估。广泛的实验结果显示，TheaterGen显著超越了现有最先进方法，其在Mini DALLE 3模型上的平均角色-角色相似性提升了21%，在平均文本-图像相似性上提升了19%，树立了新的性能标杆。

> Recent advances in diffusion models can generate high-quality and stunning images from text. However, multi-turn image generation, which is of high demand in real-world scenarios, still faces challenges in maintaining semantic consistency between images and texts, as well as contextual consistency of the same subject across multiple interactive turns. To address this issue, we introduce TheaterGen, a training-free framework that integrates large language models (LLMs) and text-to-image (T2I) models to provide the capability of multi-turn image generation. Within this framework, LLMs, acting as a "Screenwriter", engage in multi-turn interaction, generating and managing a standardized prompt book that encompasses prompts and layout designs for each character in the target image. Based on these, Theatergen generate a list of character images and extract guidance information, akin to the "Rehearsal". Subsequently, through incorporating the prompt book and guidance information into the reverse denoising process of T2I diffusion models, Theatergen generate the final image, as conducting the "Final Performance". With the effective management of prompt books and character images, TheaterGen significantly improves semantic and contextual consistency in synthesized images. Furthermore, we introduce a dedicated benchmark, CMIGBench (Consistent Multi-turn Image Generation Benchmark) with 8000 multi-turn instructions. Different from previous multi-turn benchmarks, CMIGBench does not define characters in advance. Both the tasks of story generation and multi-turn editing are included on CMIGBench for comprehensive evaluation. Extensive experimental results show that TheaterGen outperforms state-of-the-art methods significantly. It raises the performance bar of the cutting-edge Mini DALLE 3 model by 21% in average character-character similarity and 19% in average text-image similarity.

[Arxiv](https://arxiv.org/abs/2404.18919)