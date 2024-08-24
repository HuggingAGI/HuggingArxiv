# CaRDiff：通过链式思维推理扩散，实现视频显著对象的排序与显著性预测

发布时间：2024年08月21日

`LLM应用` `视频处理` `人工智能`

> CaRDiff: Video Salient Object Ranking Chain of Thought Reasoning for Saliency Prediction with Diffusion

# 摘要

> 视频显著性预测旨在找出视频中吸引观众注意的区域，这些区域受视频底层特征和高级认知过程（如记忆和认知）的影响。在这些高级影响中，语言通过塑造视觉信息的解读方式，在引导注意力方面扮演关键角色。现有方法多聚焦于感知信息的建模，却忽视了语言在推理过程中的作用，而排名线索正是这一过程的关键输出和显著性预测的实际指导。为此，我们提出了CaRDiff框架，通过整合多模态大型语言模型、定位模块和扩散模型，模仿并增强视频显著性预测。我们创新性地引入了VSOR-CoT提示方法，利用MLLM和定位模块为视频内容生成标题，并推断出显著对象及其排名和位置，进而生成可被扩散模型利用的排名图，以精确解码视频的显著性图。实验证明，VSOR-CoT能有效提升视频显著性预测的性能。CaRDiff在MVS数据集上超越了现有最先进模型，并在DHF1k数据集上通过零-shot评估展示了跨数据集的能力。

> Video saliency prediction aims to identify the regions in a video that attract human attention and gaze, driven by bottom-up features from the video and top-down processes like memory and cognition. Among these top-down influences, language plays a crucial role in guiding attention by shaping how visual information is interpreted. Existing methods primarily focus on modeling perceptual information while neglecting the reasoning process facilitated by language, where ranking cues are crucial outcomes of this process and practical guidance for saliency prediction. In this paper, we propose CaRDiff (Caption, Rank, and generate with Diffusion), a framework that imitates the process by integrating a multimodal large language model (MLLM), a grounding module, and a diffusion model, to enhance video saliency prediction. Specifically, we introduce a novel prompting method VSOR-CoT (Video Salient Object Ranking Chain of Thought), which utilizes an MLLM with a grounding module to caption video content and infer salient objects along with their rankings and positions. This process derives ranking maps that can be sufficiently leveraged by the diffusion model to decode the saliency maps for the given video accurately. Extensive experiments show the effectiveness of VSOR-CoT in improving the performance of video saliency prediction. The proposed CaRDiff performs better than state-of-the-art models on the MVS dataset and demonstrates cross-dataset capabilities on the DHF1k dataset through zero-shot evaluation.

[Arxiv](https://arxiv.org/abs/2408.12009)