# 自动优化提示以提升文本与图像间的协调性

发布时间：2024年03月26日

`LLM应用` `图像生成` `文本到图像转换`

> Improving Text-to-Image Consistency via Automatic Prompt Optimization

# 摘要

> 文本到图像生成模型取得了显著进展，诞生了许多能生成高质量逼真图像的高性能模型。然而，这些模型在生成与文本提示保持一致性的图像方面仍面临挑战，常常无法准确捕捉对象的数量、关系和属性。现有提升提示-图像一致性的方法存在诸多问题：（1）通常需要对模型进行精细调整，（2）仅关注相邻的提示样本，（3）在图像质量、表达多样性和提示-图像一致性之间存在不利的权衡。本文提出了一个名为OPT2I的T2I优化-提示框架，该框架借助大型语言模型（LLM）的力量，旨在提升T2I模型中的提示-图像一致性。框架以用户输入的提示为起点，通过迭代生成修订提示，力求最大化一致性评分。在MSCOCO和PartiPrompts两个数据集上的广泛验证显示，OPT2I能够将初始的DSG一致性评分提高至多24.9%，同时保持FID不变并提升生成图像与真实图像间的匹配度。我们的研究为构建更为可靠和强健的T2I系统开辟了新路径，充分发挥了LLM的潜力。

> Impressive advances in text-to-image (T2I) generative models have yielded a plethora of high performing models which are able to generate aesthetically appealing, photorealistic images. Despite the progress, these models still struggle to produce images that are consistent with the input prompt, oftentimes failing to capture object quantities, relations and attributes properly. Existing solutions to improve prompt-image consistency suffer from the following challenges: (1) they oftentimes require model fine-tuning, (2) they only focus on nearby prompt samples, and (3) they are affected by unfavorable trade-offs among image quality, representation diversity, and prompt-image consistency. In this paper, we address these challenges and introduce a T2I optimization-by-prompting framework, OPT2I, which leverages a large language model (LLM) to improve prompt-image consistency in T2I models. Our framework starts from a user prompt and iteratively generates revised prompts with the goal of maximizing a consistency score. Our extensive validation on two datasets, MSCOCO and PartiPrompts, shows that OPT2I can boost the initial consistency score by up to 24.9% in terms of DSG score while preserving the FID and increasing the recall between generated and real data. Our work paves the way toward building more reliable and robust T2I systems by harnessing the power of LLMs.

[Arxiv](https://arxiv.org/abs/2403.17804)