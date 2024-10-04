# 创意故事生成的集体评判

发布时间：2024年10月03日

`LLM应用` `文学创作` `人工智能`

> Collective Critics for Creative Story Generation

# 摘要

> 生成数千字的长篇故事，且保持叙事连贯性，一直是大型语言模型 (LLM) 面临的难题。以往的研究虽提出了多种框架来创建故事计划并生成长篇故事，但主要集中在叙事连贯性上，忽略了故事计划中的创造性和故事的表现力，这些恰恰是吸引读者的重要因素。为此，我们提出了创意故事生成框架 (CritiCS)，包含计划细化阶段 (CrPlan) 和故事生成阶段 (CrText)，通过集体修订机制，在长篇故事生成过程中促进创造性和表现力。具体而言，每个阶段中，一组 LLM 评论家与一位领导者合作，通过多轮迭代逐步完善计划和故事草稿。人类评估表明，CritiCS 不仅能显著提升故事的创造性和读者参与度，还能保持叙事连贯性。此外，该框架允许人类作家在评论过程中以任何角色参与，实现人机交互协作，共同创作故事。

> Generating a long story of several thousand words with narrative coherence using Large Language Models (LLMs) has been a challenging task. Previous research has addressed this challenge by proposing different frameworks that create a story plan and generate a long story based on that plan. However, these frameworks have been mainly focusing on maintaining narrative coherence in stories, often overlooking creativity in story planning and the expressiveness of the stories generated from those plans, which are desirable properties to captivate readers' interest. In this paper, we propose Collective Critics for Creative Story Generation framework (CritiCS), which is composed of plan refining stage (CrPlan) and story generation stage (CrText), to integrate a collective revision mechanism that promotes those properties into long-form story generation process. Specifically, in each stage, a group of LLM critics and one leader collaborate to incrementally refine drafts of plan and story throughout multiple rounds. Extensive human evaluation shows that the CritiCS can significantly enhance story creativity and reader engagement, while also maintaining narrative coherence. Furthermore, the design of the framework allows active participation from human writers in any role within the critique process, enabling interactive human-machine collaboration in story writing.

[Arxiv](https://arxiv.org/abs/2410.02428)