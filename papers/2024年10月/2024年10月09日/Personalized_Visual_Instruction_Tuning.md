# 定制化视觉指导调优

发布时间：2024年10月09日

`LLM应用` `人工智能` `机器人`

> Personalized Visual Instruction Tuning

# 摘要

> 多模态大型语言模型（MLLM）虽有显著进步，但存在“面盲症”问题，即能进行一般对话，却无法针对特定个体进行个性化交流。这限制了其在个性化场景中的应用，如定制视觉助手或家庭机器人。为此，我们提出个性化视觉指令调优（PVIT），通过自主生成个性化对话数据，使MLLM能识别图像中个体并进行连贯对话。我们还创建了P-Bench基准，实验显示，微调后MLLM的个性化性能大幅提升。

> Recent advancements in multimodal large language models (MLLMs) have demonstrated significant progress; however, these models exhibit a notable limitation, which we refer to as "face blindness". Specifically, they can engage in general conversations but fail to conduct personalized dialogues targeting at specific individuals. This deficiency hinders the application of MLLMs in personalized settings, such as tailored visual assistants on mobile devices, or domestic robots that need to recognize members of the family. In this paper, we introduce Personalized Visual Instruction Tuning (PVIT), a novel data curation and training framework designed to enable MLLMs to identify target individuals within an image and engage in personalized and coherent dialogues. Our approach involves the development of a sophisticated pipeline that autonomously generates training data containing personalized conversations. This pipeline leverages the capabilities of various visual experts, image generation models, and (multi-modal) large language models. To evaluate the personalized potential of MLLMs, we present a benchmark called P-Bench, which encompasses various question types with different levels of difficulty. The experiments demonstrate a substantial personalized performance enhancement after fine-tuning with our curated dataset.

[Arxiv](https://arxiv.org/abs/2410.07113)