# [采用大模型巧解之道：为基于第一人称视角的文本-音频检索任务自动生成音频描述](https://arxiv.org/abs/2402.19106)

> A SOUND APPROACH: Using Large Language Models to generate audio descriptions for egocentric text-audio retrieval

发布时间：2024年02月29日

> 网络视频数据库为构建文本-音频检索数据集提供了丰富资源，但因其声音和画面呈现的是数据的不同维度，仅将画面描述直接用于音频检索显然不够理想，尤其当音频标签粗略时。为此，我们提出一种利用大型语言模型（LLMs）生成聚焦于音频的描述方法，以便深入挖掘视频-文本数据集中的音频信息。在以第一人称视角视频为主的背景下，我们依据EpicMIR、EgoMCQ任务及EpicSounds数据集创新性地设立了三个新的文本-音频检索标准。实验结果显示，采用我们生成的以音频为核心的描述，在零样本情况下其性能明显优于原生以视觉为主导的描述。不仅如此，通过相同提示方式，我们还能有效利用LLMs提升对EpicSounds数据集的检索准确度，超越使用原有音频类别标签的表现。最终，我们证实LLMs能够评估识别某种声音对应动作的难易程度。

> Video databases from the internet are a valuable source of text-audio retrieval datasets. However, given that sound and vision streams represent different "views" of the data, treating visual descriptions as audio descriptions is far from optimal. Even if audio class labels are present, they commonly are not very detailed, making them unsuited for text-audio retrieval. To exploit relevant audio information from video-text datasets, we introduce a methodology for generating audio-centric descriptions using Large Language Models (LLMs). In this work, we consider the egocentric video setting and propose three new text-audio retrieval benchmarks based on the EpicMIR and EgoMCQ tasks, and on the EpicSounds dataset. Our approach for obtaining audio-centric descriptions gives significantly higher zero-shot performance than using the original visual-centric descriptions. Furthermore, we show that using the same prompts, we can successfully employ LLMs to improve the retrieval on EpicSounds, compared to using the original audio class labels of the dataset. Finally, we confirm that LLMs can be used to determine the difficulty of identifying the action associated with a sound.

`LLM应用`