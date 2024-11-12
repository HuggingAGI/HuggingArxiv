# IOPO：通过输入输出偏好优化赋予大型语言模型遵循复杂指令的能力

发布时间：2024年11月09日

`LLM应用` `语言模型` `指令优化`

> IOPO: Empowering LLMs with Complex Instruction Following via Input-Output Preference Optimization

# 摘要

> 在大型语言模型（LLMs）的领域中，模型准确遵循指令的能力至关重要，因为越来越多的代理和应用程序利用 LLMs 进行构建，其中指令的复杂性正在迅速增加。然而，一方面，只有一定数量的复杂指令评估数据；另一方面，没有专门的算法来提高遵循复杂指令的能力。为此，本文引入了 TRACE，这是一个用于改进和评估复杂指令遵循能力的基准，它由 120K 个训练数据和 1K 个评估数据组成。此外，我们提出了 IOPO（输入 - 输出偏好优化）对齐方法，该方法同时考虑了输入和输出偏好对，其中 LLMs 不仅迅速与响应偏好对齐，而且还精心探索指令偏好。在域内和域外数据集上的大量实验证实了 IOPO 的有效性，与 SFT 和 DPO 相比，在域内数据上分别显示出 8.15％、2.18％的改进，在域外数据上分别显示出 6.29％、3.13％的改进。

> In the realm of large language models (LLMs), the ability of models to accurately follow instructions is paramount as more agents and applications leverage LLMs for construction, where the complexity of instructions are rapidly increasing. However, on the one hand, there is only a certain amount of complex instruction evaluation data; on the other hand, there are no dedicated algorithms to improve the ability to follow complex instructions. To this end, this paper introduces TRACE, a benchmark for improving and evaluating the complex instructionfollowing ability, which consists of 120K training data and 1K evaluation data. Furthermore, we propose IOPO (Input-Output Preference Optimization) alignment method which takes both input and output preference pairs into consideration, where LLMs not only rapidly align with response preferences but also meticulously explore the instruction preferences. Extensive experiments on both in-domain and outof-domain datasets confirm the effectiveness of IOPO, showing 8.15%, 2.18% improvements on in-domain data and 6.29%, 3.13% on outof-domain data compared to SFT and DPO respectively.

[Arxiv](https://arxiv.org/abs/2411.06208)