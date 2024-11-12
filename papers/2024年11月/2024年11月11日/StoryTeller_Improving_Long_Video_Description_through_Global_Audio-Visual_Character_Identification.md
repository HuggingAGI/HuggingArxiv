# StoryTeller：通过全球视听角色识别改进长视频描述

发布时间：2024年11月11日

`LLM应用`

> StoryTeller: Improving Long Video Description through Global Audio-Visual Character Identification

# 摘要

> 现有的大型视觉语言模型（LVLMs）在很大程度上仅限于处理短的、几秒钟长的视频，并且在为几分钟或更长时间的扩展视频生成连贯描述方面存在困难。长视频描述带来了新的挑战，例如描述中的情节级一致性。为了解决这些问题，我们认为视听角色识别，即将角色名称与每个对话匹配，是一个关键因素。我们提出了 StoryTeller，这是一个用于生成长视频密集描述的系统，它结合了低级视觉概念和高级情节信息。StoryTeller 使用一个多模态大型语言模型，该模型集成了视觉、音频和文本模态，对分钟长的视频剪辑进行视听角色识别。然后将结果输入到 LVLMs 中，以增强视频描述的一致性。我们在电影描述任务上验证了我们的方法，并引入了 MovieStory101，这是一个具有三分钟电影剪辑密集描述的数据集。为了评估长视频描述，我们创建了 MovieQA，这是一个针对 MovieStory101 测试集的大型多项选择题集。我们通过将描述输入到 GPT-4 中来回答这些问题来评估描述，使用准确性作为自动评估指标。实验表明，StoryTeller 在 MovieQA 上优于所有开源和闭源基线，比最强的基线 Gemini-1.5-pro 准确率高出 9.5％，并且在人工并排评估中显示出 +15.56％的优势。此外，从 StoryTeller 引入视听角色识别提高了所有视频描述模型的性能，Gemini-1.5-pro 和 GPT-4o 在 MovieQA 上的准确率分别相对提高了 5.5％和 13.0％。

> Existing large vision-language models (LVLMs) are largely limited to processing short, seconds-long videos and struggle with generating coherent descriptions for extended video spanning minutes or more. Long video description introduces new challenges, such as plot-level consistency across descriptions. To address these, we figure out audio-visual character identification, matching character names to each dialogue, as a key factor. We propose StoryTeller, a system for generating dense descriptions of long videos, incorporating both low-level visual concepts and high-level plot information. StoryTeller uses a multimodal large language model that integrates visual, audio, and text modalities to perform audio-visual character identification on minute-long video clips. The results are then fed into a LVLM to enhance consistency of video description. We validate our approach on movie description tasks and introduce MovieStory101, a dataset with dense descriptions for three-minute movie clips. To evaluate long video descriptions, we create MovieQA, a large set of multiple-choice questions for the MovieStory101 test set. We assess descriptions by inputting them into GPT-4 to answer these questions, using accuracy as an automatic evaluation metric. Experiments show that StoryTeller outperforms all open and closed-source baselines on MovieQA, achieving 9.5% higher accuracy than the strongest baseline, Gemini-1.5-pro, and demonstrating a +15.56% advantage in human side-by-side evaluations. Additionally, incorporating audio-visual character identification from StoryTeller improves the performance of all video description models, with Gemini-1.5-pro and GPT-4o showing relative improvement of 5.5% and 13.0%, respectively, in accuracy on MovieQA.

[Arxiv](https://arxiv.org/abs/2411.07076)