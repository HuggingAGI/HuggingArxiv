# Sign2GPT：借助大型语言模型实现无词典辅助的美国手语翻译在这项研究中，我们提出了Sign2GPT，这是一种创新的方法，它利用了大型语言模型的强大能力，实现了无需依赖传统手势词典的美国手语翻译。通过这种方法，我们旨在打破传统翻译的局限，为手语用户提供更加流畅和自然的交流体验。

发布时间：2024年05月07日

`Agent

这篇论文介绍了一种名为Sign2GPT的框架，它是一个自动手语翻译系统，结合了计算机视觉和自然语言处理技术，旨在解决手语与口语之间的沟通障碍。该框架通过使用轻量级适配器，将预训练的视觉和语言模型应用于手语翻译，特别适用于数据稀缺和计算资源有限的情况。此外，论文还提出了一种新的预训练策略，使得编码器能够在没有术语顺序信息或注释的情况下，从自动提取的伪术语中学习手语知识。该方法在两个公开数据集上进行了测试，并取得了优异的性能。因此，这篇论文更符合Agent分类，因为它描述了一个具体的系统或代理，该系统能够执行特定的任务（手语翻译），并且展示了如何通过创新的方法来克服实际应用中的挑战。` `手语翻译` `计算机视觉`

> Sign2GPT: Leveraging Large Language Models for Gloss-Free Sign Language Translation

# 摘要

> 自动手语翻译需融合计算机视觉与自然语言处理，以跨越手语与口语间的沟通鸿沟。然而，手语翻译训练数据匮乏，我们需借力口语资源。我们创新推出Sign2GPT框架，它巧妙运用轻量级适配器，将大规模预训练的视觉与语言模型应用于无术语手语翻译。轻量级适配器因数据集有限及长视频训练的计算需求而显得尤为关键。我们还独创了一种预训练策略，让编码器无需术语顺序信息或注释，便能从自动提取的伪术语中汲取手语精髓。在RWTH-PHOENIX-Weather 2014T和CSL-Daily两大公开数据集上，我们的方法不仅经受考验，更在无术语翻译领域刷新了性能标杆。

> Automatic Sign Language Translation requires the integration of both computer vision and natural language processing to effectively bridge the communication gap between sign and spoken languages. However, the deficiency in large-scale training data to support sign language translation means we need to leverage resources from spoken language. We introduce, Sign2GPT, a novel framework for sign language translation that utilizes large-scale pretrained vision and language models via lightweight adapters for gloss-free sign language translation. The lightweight adapters are crucial for sign language translation, due to the constraints imposed by limited dataset sizes and the computational requirements when training with long sign videos. We also propose a novel pretraining strategy that directs our encoder to learn sign representations from automatically extracted pseudo-glosses without requiring gloss order information or annotations. We evaluate our approach on two public benchmark sign language translation datasets, namely RWTH-PHOENIX-Weather 2014T and CSL-Daily, and improve on state-of-the-art gloss-free translation performance with a significant margin.

[Arxiv](https://arxiv.org/abs/2405.04164)