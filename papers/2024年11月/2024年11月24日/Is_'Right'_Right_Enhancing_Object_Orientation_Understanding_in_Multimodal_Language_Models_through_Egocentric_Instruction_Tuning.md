# “正确”真就正确吗？借助以自我为中心的指令调优来增强多模态语言模型中的对象定向理解

发布时间：2024年11月24日

`LLM应用` `多模态` `人工智能`

> Is 'Right' Right? Enhancing Object Orientation Understanding in Multimodal Language Models through Egocentric Instruction Tuning

# 摘要

> 多模态大型语言模型（MLLMs）作为关键接口，在多模态应用里将人类和人工智能技术相联结。然而，由于训练数据中物体方向标注不一致，当下的 MLLMs 在精确解读图像中物体方向时遭遇难题，阻碍了连贯的方向理解的形成。为化解此难题，我们提出了以自我为中心的指令调整，它依据从用户自我视角得出的统一标注标准，让 MLLMs 的方向理解与用户视角相符。我们先是生成以自我为中心的指令数据，该数据借助 MLLMs 识别物体细节的能力，并运用先验知识来进行方向理解。凭借这些数据，我们开展指令调整以提升模型准确解读方向的能力。另外，我们引入了 EgoOrientBench，这是一个基准，运用从不同领域采集的图像，通过三个任务来评估 MLLMs 的方向理解。在这个基准上的实验结果显示，以自我为中心的指令调整大幅提升了方向理解，且未影响 MLLM 的整体性能。指令数据和基准数据集可在我们的项目页面 https://github.com/jhCOR/EgoOrientBench 上获取。

> Multimodal large language models (MLLMs) act as essential interfaces, connecting humans with AI technologies in multimodal applications. However, current MLLMs face challenges in accurately interpreting object orientation in images due to inconsistent orientation annotations in training data, hindering the development of a coherent orientation understanding. To overcome this, we propose egocentric instruction tuning, which aligns MLLMs' orientation understanding with the user's perspective, based on a consistent annotation standard derived from the user's egocentric viewpoint. We first generate egocentric instruction data that leverages MLLMs' ability to recognize object details and applies prior knowledge for orientation understanding. Using this data, we perform instruction tuning to enhance the model's capability for accurate orientation interpretation. In addition, we introduce EgoOrientBench, a benchmark that evaluates MLLMs' orientation understanding across three tasks using images collected from diverse domains. Experimental results on this benchmark show that egocentric instruction tuning significantly improves orientation understanding without compromising overall MLLM performance. The instruction data and benchmark dataset are available on our project page at https://github.com/jhCOR/EgoOrientBench.

[Arxiv](https://arxiv.org/abs/2411.16761)