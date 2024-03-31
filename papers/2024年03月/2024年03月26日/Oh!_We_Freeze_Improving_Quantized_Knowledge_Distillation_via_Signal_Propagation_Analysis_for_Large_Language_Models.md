# 哎呀！冻结啦：探究信号传播分析提升大型语言模型量化知识蒸馏效果之道

发布时间：2024年03月26日

`LLM理论` `边缘计算` `知识蒸馏`

> Oh! We Freeze: Improving Quantized Knowledge Distillation via Signal Propagation Analysis for Large Language Models

# 摘要

> 大型生成模型如LLMs和扩散模型在NLP和计算机视觉领域取得了突破性进展。但它们在边缘设备上的部署受限于缓慢的推理速度和高资源需求。本研究提出了一种轻量化的知识蒸馏量化微调技术（KD-QAT），通过4位权重量化提升LLMs性能，以便在设备上运行流行的聊天应用。我们通过分析训练中的梯度传播，深入探讨了KD-QAT在低比特量化误差下的稳定性问题。据此，我们提出了ov-freeze技术来稳定微调过程。在7B LLaMAv2-Chat模型的实验中，我们展示了ov-freeze技术能够在4位量化水平下保持接近浮点数精度的性能，准确度损失控制在0.7%以内。

> Large generative models, such as large language models (LLMs) and diffusion models have as revolutionized the fields of NLP and computer vision respectively. However, their slow inference, high computation and memory requirement makes it challenging to deploy them on edge devices. In this study, we propose a light-weight quantization aware fine tuning technique using knowledge distillation (KD-QAT) to improve the performance of 4-bit weight quantized LLMs using commonly available datasets to realize a popular language use case, on device chat applications. To improve this paradigm of finetuning, as main contributions, we provide insights into stability of KD-QAT by empirically studying the gradient propagation during training to better understand the vulnerabilities of KD-QAT based approaches to low-bit quantization errors. Based on our insights, we propose ov-freeze, a simple technique to stabilize the KD-QAT process. Finally, we experiment with the popular 7B LLaMAv2-Chat model at 4-bit quantization level and demonstrate that ov-freeze results in near float-point precision performance, i.e., less than 0.7% loss of accuracy on Commonsense Reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2403.18159)