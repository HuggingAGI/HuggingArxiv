# 几何感知生成自动编码器，专为扭曲黎曼度量学习和数据流形上的生成建模而设计

发布时间：2024年10月16日

`其他` `生物信息学` `基因组学`

> Geometry-Aware Generative Autoencoders for Warped Riemannian Metric Learning and Generative Modeling on Data Manifolds

# 摘要

> 摘要：高维数据集的迅猛增长，尤其是在单细胞RNA测序和空间基因组学领域，为科学探索开辟了新天地，但也带来了计算与统计上的独特挑战。传统方法在处理几何感知数据生成、有意义轨迹插值及群体路径传输时力不从心。为此，我们推出了几何感知生成自编码器（GAGA），这一创新框架融合了流形学习与生成建模。GAGA构建的神经网络嵌入空间，不仅尊重流形学习揭示的本征几何，还学习了数据空间上的新型扭曲黎曼度量。此度量结合了流形上的点与流形外的负样本，从而描绘出整个潜在空间的丰富几何特征。借助这一度量，GAGA能均匀采样流形点、沿测地线生成点，并在学习流形上实现群体插值。在模拟与真实数据集上，GAGA表现出色，尤其在单细胞群体级轨迹推断中，性能超越了最先进方法30%。

> 
Abstract:Rapid growth of high-dimensional datasets in fields such as single-cell RNA sequencing and spatial genomics has led to unprecedented opportunities for scientific discovery, but it also presents unique computational and statistical challenges. Traditional methods struggle with geometry-aware data generation, interpolation along meaningful trajectories, and transporting populations via feasible paths. To address these issues, we introduce Geometry-Aware Generative Autoencoder (GAGA), a novel framework that combines extensible manifold learning with generative modeling. GAGA constructs a neural network embedding space that respects the intrinsic geometries discovered by manifold learning and learns a novel warped Riemannian metric on the data space. This warped metric is derived from both the points on the data manifold and negative samples off the manifold, allowing it to characterize a meaningful geometry across the entire latent space. Using this metric, GAGA can uniformly sample points on the manifold, generate points along geodesics, and interpolate between populations across the learned manifold. GAGA shows competitive performance in simulated and real world datasets, including a 30% improvement over the state-of-the-art methods in single-cell population-level trajectory inference.
    

[Arxiv](https://arxiv.org/pdf/2410.12779)