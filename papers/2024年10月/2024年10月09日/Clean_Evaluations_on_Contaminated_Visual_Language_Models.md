# 对受污染视觉语言模型的纯净评估

发布时间：2024年10月09日

`LLM应用` `计算机视觉` `人工智能`

> Clean Evaluations on Contaminated Visual Language Models

# 摘要

> 评估大型语言模型 (LLMs) 的纯净性已成为重要研究课题，但视觉语言模型 (VLMs) 的纯净评估仍待探索。我们通过视觉数据增强提出新方法，构建了包含数千实例的视觉清洁评估基准。实验表明，传统视觉数据增强虽有效，但易被滥用为训练数据。我们提出 BGR 增强切换色彩通道，简单有效减少数据污染，且不适用于训练，防止恶意整合。此技术有望纯净评估视觉 LLMs，相关代码、数据及模型权重将在发表后公开。

> How to evaluate large language models (LLMs) cleanly has been established as an important research era to genuinely report the performance of possibly contaminated LLMs. Yet, how to cleanly evaluate the visual language models (VLMs) is an under-studied problem. We propose a novel approach to achieve such goals through data augmentation methods on the visual input information. We then craft a new visual clean evaluation benchmark with thousands of data instances. Through extensive experiments, we found that the traditional visual data augmentation methods are useful, but they are at risk of being used as a part of the training data as a workaround. We further propose using BGR augmentation to switch the colour channel of the visual information. We found that it is a simple yet effective method for reducing the effect of data contamination and fortunately, it is also harmful to be used as a data augmentation method during training. It means that it is hard to integrate such data augmentation into training by malicious trainers and it could be a promising technique to cleanly evaluate visual LLMs. Our code, data, and model weights will be released upon publication.

[Arxiv](https://arxiv.org/abs/2410.07030)