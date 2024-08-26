# Transfusion：用单一多模态模型预测下一词并扩散图像

发布时间：2024年08月20日

`LLM应用` `人工智能` `多模态学习`

> Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model

# 摘要

> 我们提出了 Transfusion，这是一种在离散与连续数据上训练多模态模型的创新方法。它通过结合语言建模与扩散技术，训练单一变换器处理混合模态数据。我们从零开始，预训练了多个高达 70 亿参数的 Transfusion 模型，并针对多种单一及跨模态基准测试，确立了其缩放规律。实验表明，Transfusion 在扩展性上远超传统的图像量化与离散图像标记语言模型训练方法。通过加入模态专属的编码解码层，我们不仅提升了 Transfusion 的性能，还能将图像压缩至仅 16 个区块。此外，我们将 Transfusion 扩展至 70 亿参数与 2 万亿多模态标记，成功打造出一个能与同等规模扩散模型及语言模型相匹敌的图像与文本生成模型，充分融合了两者的优势。

> 
Abstract:We introduce Transfusion, a recipe for training a multi-modal model over discrete and continuous data. Transfusion combines the language modeling loss function (next token prediction) with diffusion to train a single transformer over mixed-modality sequences. We pretrain multiple Transfusion models up to 7B parameters from scratch on a mixture of text and image data, establishing scaling laws with respect to a variety of uni- and cross-modal benchmarks. Our experiments show that Transfusion scales significantly better than quantizing images and training a language model over discrete image tokens. By introducing modality-specific encoding and decoding layers, we can further improve the performance of Transfusion models, and even compress each image to just 16 patches. We further demonstrate that scaling our Transfusion recipe to 7B parameters and 2T multi-modal tokens produces a model that can generate images and text on a par with similar scale diffusion models and language models, reaping the benefits of both worlds.
    

[Arxiv](https://arxiv.org/pdf/2408.11039)