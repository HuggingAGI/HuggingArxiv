# MM-CamObj：专为伪装对象场景设计的多模态综合数据集

发布时间：2024年09月24日

`LLM应用` `计算机视觉` `人工智能`

> MM-CamObj: A Comprehensive Multimodal Dataset for Camouflaged Object Scenarios

# 摘要

> 大型视觉-语言模型（LVLMs）在多个领域大放异彩，但在复杂场景，尤其是涉及伪装对象的场景中，仍显力不从心。这主要归咎于训练数据中缺乏伪装场景的样本。为此，我们首创了MM-CamObj数据集，内含CamObj-Align和CamObj-Instruct两个子集。CamObj-Align包含11,363对图像-文本，旨在强化LVLMs对伪装场景的理解；而CamObj-Instruct则收集了11,363张图像和68,849段对话，助力LVLMs更好地遵循指令。基于此，我们推出了专为伪装场景设计的CamObj-Llava模型，并引入六种模式的课程学习策略，以提升其对伪装对象的认知。此外，我们还构建了CamObj-Bench，用于评估现有LVLMs在伪装场景中的各项能力。该基准包含600张图像和7项任务，共计9,449个问题。实验结果令人瞩目，我们的模型在7项任务中的4项上，性能超越GPT-4o达25.84%。代码与数据集即将在https://github.com/JCruan519/MM-CamObj开放获取。

> Large visual-language models (LVLMs) have achieved great success in multiple applications. However, they still encounter challenges in complex scenes, especially those involving camouflaged objects. This is primarily due to the lack of samples related to camouflaged scenes in the training dataset. To mitigate this issue, we construct the MM-CamObj dataset for the first time, comprising two subsets: CamObj-Align and CamObj-Instruct. Specifically, CamObj-Align contains 11,363 image-text pairs, and it is designed for VL alignment and injecting rich knowledge of camouflaged scenes into LVLMs. CamObj-Instruct is collected for fine-tuning the LVLMs with improved instruction-following capabilities, and it includes 11,363 images and 68,849 conversations with diverse instructions. Based on the MM-CamObj dataset, we propose the CamObj-Llava, an LVLM specifically designed for addressing tasks in camouflaged scenes. To facilitate our model's effective acquisition of knowledge about camouflaged objects and scenes, we introduce a curriculum learning strategy with six distinct modes. Additionally, we construct the CamObj-Bench to evaluate the existing LVLMs' capabilities of understanding, recognition, localization and count in camouflage scenes. This benchmark includes 600 images and 7 tasks, with a total of 9,449 questions. Extensive experiments are conducted on the CamObj-Bench with CamObj-Llava, 8 existing open-source and 3 closed-source LVLMs. Surprisingly, the results indicate that our model achieves a 25.84% improvement in 4 out of 7 tasks compared to GPT-4o. Code and datasets will be available at https://github.com/JCruan519/MM-CamObj.

[Arxiv](https://arxiv.org/abs/2409.16084)