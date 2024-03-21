# 运用三维地震技术揭示地下结构的奥秘

发布时间：2024年03月20日

`Agent` `地震学` `地球物理`

> Encoding the Subsurface in 3D with Seismic

> 本文介绍了一种创新的自监督生成AI技术，结合Masked AutoEncoder（MAE）与Vision Transformer（ViT）核心结构，用于地震数据处理与解释工作。我们定制了MAE-ViT架构，使其适应分析三维叠后地震小数据块的需求。如同LLMs深度解读文本那样，经过t-SNE可视化验证，MAE模型同样具备对地震特征进行语义分类的强大能力。经过精细调整后的模型，能够在三维空间中实现地震体的插值，展现出实际应用场景的价值。研究选用来自“Onward - Patch the Planet”大赛的开源数据集，有力保证了实验结果的透明度及可复制性。这一研究成果标志着我们在运用尖端技术解决地震数据处理与解释难题上取得了新的突破。

> This article presents a self-supervised generative AI approach to seismic data processing and interpretation using a Masked AutoEncoder (MAE) with a Vision Transformer (ViT) backbone. We modified the MAE-ViT architecture to process 3D seismic mini-cubes to analyze post-stack seismic data. The MAE model can semantically categorize seismic features, demonstrated through t-SNE visualization, much like large language models (LLMs) understand text. After we fine-tune the model, its ability to interpolate seismic volumes in 3D showcases a downstream application. The study's use of an open-source dataset from the "Onward - Patch the Planet" competition ensures transparency and reproducibility of the results. The findings are significant as they represent a step towards utilizing state-of-the-art technology for seismic processing and interpretation tasks.

[Arxiv](https://arxiv.org/abs/2403.13593)