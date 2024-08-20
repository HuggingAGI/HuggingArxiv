# Anim-Director：一款由大型多模态模型赋能的代理，专为可控动画视频创作而生。

发布时间：2024年08月19日

`LLM应用` `动画制作` `人工智能`

> Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation

# 摘要

> 传统动画制作依赖于人工标注数据的多阶段训练，成本高昂且效果受限。为此，我们创新性地采用大型多模态模型（LMMs）为核心，打造了自主动画制作系统Anim-Director。该系统通过LMMs与生成AI工具的协同，能从简要叙述或指令出发，自动创作动画视频。制作过程分为三步：首先，系统根据用户输入构建连贯故事线，并细化至角色与场景的详细描述；其次，利用LMMs结合图像生成工具，确保各场景视觉一致性；最后，基于场景图像，LMMs引导动画视频的生成。整个流程高度自动化，无需人工介入，系统自主评估并优化最终动画效果。

> Traditional animation generation methods depend on training generative models with human-labelled data, entailing a sophisticated multi-stage pipeline that demands substantial human effort and incurs high training costs. Due to limited prompting plans, these methods typically produce brief, information-poor, and context-incoherent animations. To overcome these limitations and automate the animation process, we pioneer the introduction of large multimodal models (LMMs) as the core processor to build an autonomous animation-making agent, named Anim-Director. This agent mainly harnesses the advanced understanding and reasoning capabilities of LMMs and generative AI tools to create animated videos from concise narratives or simple instructions. Specifically, it operates in three main stages: Firstly, the Anim-Director generates a coherent storyline from user inputs, followed by a detailed director's script that encompasses settings of character profiles and interior/exterior descriptions, and context-coherent scene descriptions that include appearing characters, interiors or exteriors, and scene events. Secondly, we employ LMMs with the image generation tool to produce visual images of settings and scenes. These images are designed to maintain visual consistency across different scenes using a visual-language prompting method that combines scene descriptions and images of the appearing character and setting. Thirdly, scene images serve as the foundation for producing animated videos, with LMMs generating prompts to guide this process. The whole process is notably autonomous without manual intervention, as the LMMs interact seamlessly with generative tools to generate prompts, evaluate visual quality, and select the best one to optimize the final output.

[Arxiv](https://arxiv.org/abs/2408.09787)