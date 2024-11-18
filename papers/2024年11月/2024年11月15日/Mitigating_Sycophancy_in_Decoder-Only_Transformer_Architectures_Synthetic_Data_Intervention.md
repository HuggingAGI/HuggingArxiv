# 减轻仅解码器的 Transformer 架构中的谄媚问题：采用合成数据进行干预

发布时间：2024年11月15日

`LLM应用` `语言模型` `数据干预`

> Mitigating Sycophancy in Decoder-Only Transformer Architectures: Synthetic Data Intervention

# 摘要

> 为解决大型语言模型中因基于人类反馈的强化学习而产生的阿谀奉承问题，本研究把合成数据干预技术应用于仅解码器的转换器架构。依据现有文献中的研究空缺，研究人员设计了实验流程，通过生成多元的数据来降低模型迎合的趋向，并以 GPT4o 作为实验工具加以验证。此次实验采用了 100 个真假问题，在多项指标上对比了经合成数据干预训练的模型与原始未训练模型的表现。结果显示，SDI 训练模型在准确率和阿谀奉承率方面为该技术提供了支持，在减少阿谀奉承现象上成效显著。特别要提到的是，数据集、实验流程、代码和数据结果已上传至 Github，链接是 https://github.com/brucewang123456789/GeniusTrail.git。

> To address the sycophancy problem caused by reinforcement learning from human feedback in large language models, this research applies synthetic data intervention technology to the decoder-only transformer architecture. Based on the research gaps in the existing literature, the researcher designed an experimental process to reduce the tendency of models to cater by generating diversified data, and used GPT4o as an experimental tool for verification. The experiment used 100 true and false questions, and compared the performance of the model trained with synthetic data intervention and the original untrained model on multiple indicators. The results show that the SDI training model supports the technology in terms of accuracy rate and sycophancy rate and has significant effectiveness in reducing sycophancy phenomena. Notably, the data set, experimental process, code and data results have been uploaded to Github, the link is https://github.com/brucewang123456789/GeniusTrail.git.

[Arxiv](https://arxiv.org/abs/2411.10156)