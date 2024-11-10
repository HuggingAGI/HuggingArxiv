# SpectraFM：调谐到恒星基础模型

发布时间：2024年11月07日

`其他` `天体物理` `机器学习`

> SpectraFM: Tuning into Stellar Foundation Models

# 摘要

> 在天体物理学中，机器学习模型通常在范围上受到限制，并且不能适应来自新仪器或任务的数据。我们引入了 SpectraFM，这是一种基于 Transformer 的基础模型架构，可以在来自任何波长范围和仪器的恒星光谱上进行预训练。SpectraFM 通过将灵活性与预训练的知识转移相结合，在泛化方面表现出色，使其能够超越传统的机器学习方法，特别是在训练数据有限的情况下。我们的模型在大约 90k 个合成光谱的示例上进行了预训练，以预测恒星的化学丰度（Fe、Mg、O）、温度和比重。然后，我们在真实光谱上对模型进行微调以使其适应观测数据，然后在不同波长范围内的受限 100 星训练集上进一步微调以预测铁丰度。尽管真实光谱的富铁训练集很小，但从合成光谱预训练的迁移学习使模型能够在贫铁恒星上表现良好。相比之下，从头开始训练的神经网络无法完成此任务。我们研究了 Transformer 注意力机制，发现受到关注的波长携带有关化学成分的物理信息。通过利用预训练的知识及其处理非光谱输入的能力，SpectraFM 减少了对大型训练数据集的需求，并实现了跨仪器和跨领域的研究。它的适应性使其非常适合应对天体物理学中的新挑战，例如从多模态数据集中提取见解。

> Machine learning models in astrophysics are often limited in scope and cannot adapt to data from new instruments or tasks. We introduce SpectraFM, a Transformer-based foundation model architecture that can be pre-trained on stellar spectra from any wavelength range and instrument. SpectraFM excels in generalization by combining flexibility with knowledge transfer from pre-training, allowing it to outperform traditional machine learning methods, especially in scenarios with limited training data. Our model is pre-trained on approximately 90k examples of synthetic spectra to predict the chemical abundances (Fe, Mg, O), temperature, and specific gravity of stars. We then fine-tune the model on real spectra to adapt it to observational data before fine-tuning it further on a restricted 100-star training set in a different wavelength range to predict iron abundance. Despite a small iron-rich training set of real spectra, transfer learning from the synthetic spectra pre-training enables the model to perform well on iron-poor stars. In contrast, a neural network trained from scratch fails at this task. We investigate the Transformer attention mechanism and find that the wavelengths receiving attention carry physical information about chemical composition. By leveraging the knowledge from pre-training and its ability to handle non-spectra inputs, SpectraFM reduces the need for large training datasets and enables cross-instrument and cross-domain research. Its adaptability makes it well-suited for tackling emerging challenges in astrophysics, like extracting insights from multi-modal datasets.

[Arxiv](https://arxiv.org/abs/2411.04750)