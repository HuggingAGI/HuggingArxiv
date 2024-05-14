# 零-shot视频字幕生成通过检索增强技术得到提升，本研究探索了如何利用检索机制来优化视频内容的自动描述过程。

发布时间：2024年05月11日

`Agent

这篇论文探讨了如何利用预训练的视觉与语言模型，在无需监督数据的情况下，通过测试时适应直接生成视频字幕。这种方法涉及构建一个Agent，该Agent能够理解视频内容并生成相应的字幕，而不依赖于传统的全监督学习方法。论文中提出的方法通过使用可学习标记作为模型之间的沟通桥梁，并利用精心设计的损失函数来训练这些标记，从而使GPT-2能够捕捉视频信息并生成字幕。这种方法在多个数据集上的实验结果表明了其有效性，因此将其归类为Agent。` `视频字幕生成` `零-shot学习`

> Retrieval Enhanced Zero-Shot Video Captioning

# 摘要

> 尽管全监督视频字幕技术已取得显著成就，但零-shot方法的探索仍显不足。本文提出利用预训练的视觉与语言模型，通过测试时适应直接生成视频字幕。我们采用XCLIP、CLIP和GPT-2三个模型，因其源码开放，作为视频与文本的桥梁。关键挑战在于如何让GPT-2充分理解视频内容以生成恰当字幕。为此，我们提出使用可学习标记作为GPT-2与XCLIP、CLIP之间的沟通桥梁。不同于传统训练方式，我们通过精心设计的损失函数，利用推理数据的伪目标来训练这些标记，使其能够为GPT-2捕捉视频信息。这一过程仅需数轮迭代（实验中为16轮），无需真实数据。在MSR-VTT、MSVD和VATEX三个数据集上的实验表明，我们的方法在CIDEr指标上比现有技术提升了4%至20%。

> Despite the significant progress of fully-supervised video captioning, zero-shot methods remain much less explored. In this paper, we propose to take advantage of existing pre-trained large-scale vision and language models to directly generate captions with test time adaptation. Specifically, we bridge video and text using three key models: a general video understanding model XCLIP, a general image understanding model CLIP, and a text generation model GPT-2, due to their source-code availability. The main challenge is how to enable the text generation model to be sufficiently aware of the content in a given video so as to generate corresponding captions. To address this problem, we propose using learnable tokens as a communication medium between frozen GPT-2 and frozen XCLIP as well as frozen CLIP. Differing from the conventional way to train these tokens with training data, we update these tokens with pseudo-targets of the inference data under several carefully crafted loss functions which enable the tokens to absorb video information catered for GPT-2. This procedure can be done in just a few iterations (we use 16 iterations in the experiments) and does not require ground truth data. Extensive experimental results on three widely used datasets, MSR-VTT, MSVD, and VATEX, show 4% to 20% improvements in terms of the main metric CIDEr compared to the existing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2405.07046)