# 我的模型被合并了吗？探究大型语言模型知识产权防护措施在抵御模型合并攻击时的坚固程度。

发布时间：2024年04月08日

`LLM理论` `知识产权保护` `模型融合`

> Have You Merged My Model? On The Robustness of Large Language Model IP Protection Methods Against Model Merging

# 摘要

> 模型融合技术以其轻量级和无需昂贵硬件或特定训练数据的优势，正成为模型增强的热门选择。它通过调整上游模型参数来吸收其处理下游任务的能力。然而，这种融合过程若未经授权，可能会触犯原始模型的知识产权。本文首次探讨了在模型融合中保护知识产权的方法的稳定性，对比了量化水印和指令指纹等两种尖端保护技术，以及任务算术、TIES-MERGING等模型融合技术。研究发现，现行的LLM水印技术在模型融合后难以保持有效，而模型指纹技术则显示出较强的生存能力。我们的研究意在提醒，模型融合对评估模型知识产权保护技术的稳定性至关重要，这有助于推动开源LLM社区的良性发展。

> Model merging is a promising lightweight model empowerment technique that does not rely on expensive computing devices (e.g., GPUs) or require the collection of specific training data. Instead, it involves editing different upstream model parameters to absorb their downstream task capabilities. However, uncertified model merging can infringe upon the Intellectual Property (IP) rights of the original upstream models. In this paper, we conduct the first study on the robustness of IP protection methods in model merging scenarios. We investigate two state-of-the-art IP protection techniques: Quantization Watermarking and Instructional Fingerprint, along with various advanced model merging technologies, such as Task Arithmetic, TIES-MERGING, and so on. Experimental results indicate that current Large Language Model (LLM) watermarking techniques cannot survive in the merged models, whereas model fingerprinting techniques can. Our research aims to highlight that model merging should be an indispensable consideration in the robustness assessment of model IP protection techniques, thereby promoting the healthy development of the open-source LLM community.

[Arxiv](https://arxiv.org/abs/2404.05188)