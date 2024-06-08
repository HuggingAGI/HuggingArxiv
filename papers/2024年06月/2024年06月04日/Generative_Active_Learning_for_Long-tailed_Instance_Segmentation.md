# 利用生成式主动学习优化长尾实例分割

发布时间：2024年06月04日

`Agent

理由：这篇论文主要探讨了如何通过主动学习方法优化生成数据的选择和利用，以提升特定任务（长尾实例分割）的性能。论文中提出的BSGAL算法是一种针对生成数据的主动学习策略，它通过梯度缓存来评估生成数据的贡献，并有效地处理大量生成数据和复杂的分割任务。这种主动学习策略可以被视为一种智能代理（Agent），因为它能够自主地选择和利用数据来优化任务性能。因此，这篇论文更适合归类为Agent。` `计算机视觉` `机器学习`

> Generative Active Learning for Long-tailed Instance Segmentation

# 摘要

> 近期，大规模语言-图像生成模型备受瞩目，众多研究利用其生成的数据来提升感知任务的性能。然而，并非所有生成数据都对下游模型有益，且现有方法未充分挖掘如何优化选择和利用这些数据。同时，针对生成数据的主动学习研究尚显匮乏。本文聚焦于长尾实例分割任务，探索了如何针对生成数据实施主动学习，并提出了BSGAL算法，该算法通过梯度缓存在线评估生成数据的贡献。BSGAL能高效应对大量生成数据及复杂分割任务。实验结果显示，BSGAL超越了基线方法，显著提升了长尾分割任务的性能。相关代码已发布于https://github.com/aim-uofa/DiverGen。

> Recently, large-scale language-image generative models have gained widespread attention and many works have utilized generated data from these models to further enhance the performance of perception tasks. However, not all generated data can positively impact downstream models, and these methods do not thoroughly explore how to better select and utilize generated data. On the other hand, there is still a lack of research oriented towards active learning on generated data. In this paper, we explore how to perform active learning specifically for generated data in the long-tailed instance segmentation task. Subsequently, we propose BSGAL, a new algorithm that online estimates the contribution of the generated data based on gradient cache. BSGAL can handle unlimited generated data and complex downstream segmentation tasks effectively. Experiments show that BSGAL outperforms the baseline approach and effectually improves the performance of long-tailed segmentation. Our code can be found at https://github.com/aim-uofa/DiverGen.

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x1.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x2.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x3.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x4.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x5.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/vis_noised_imgs_cifar10.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x6.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x7.png)

![利用生成式主动学习优化长尾实例分割](../../../paper_images/2406.02435/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02435)