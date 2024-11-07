# 注释效率：通过阻塞稀疏线性老虎机识别困难样本

发布时间：2024年10月26日

`其他` `图像分类` `数据标注`

> Annotation Efficiency: Identifying Hard Samples via Blocked Sparse Linear Bandits

# 摘要

> 摘要：本文考虑在标签稀缺的环境中，使用专家仅进行几轮标注来标注数据点的问题。我们提议除了真实标签外，还向专家征求关于标注数据点难度的可靠反馈。在主动学习或核心集选择方面的现有文献与我们的设定相关性较小，因为它们假定存在可靠的训练模型，而在标签稀缺的情况下不存在。然而，关于核心集选择的文献强调在训练集中存在困难数据点，以便在下游任务中进行监督学习（Mindermann 等人，2022）。因此，对于给定的固定标注预算$\mathsf{T}$轮，我们在稀疏线性强盗框架中对选择哪些（困难）数据点进行标注的顺序决策问题进行建模，约束是任何臂不能被拉超过一次（阻塞约束）。在对数据点的温和假设下，我们的（计算高效）探索-然后-提交算法 BSLB 实现了遗憾保证为$\widetilde{\mathsf{O}}(k^{rac{1}{3}} \mathsf{T}^{rac{2}{3}} +k^{-rac{1}{2}} eta_k + k^{-rac{1}{12}} eta_k^{rac{1}{2}}\mathsf{T}^{rac{5}{6}})$，其中未知参数向量在稀疏度水平$k$处具有尾部幅度$eta_k$。为此，我们展示了具有温和限制特征值（RE）条件的 Lasso 估计器的离线统计保证，该条件对稀疏性也具有鲁棒性。最后，我们提出了一种元算法 C-BSLB，它不需要以无遗憾成本了解最优稀疏性参数。我们在 PASCAL-VOC 数据集上的图像分类任务的标签稀缺设置中展示了我们的 BSLB 算法用于标注的有效性，其中我们使用了真实世界的标注难度分数。

> 
Abstract:This paper considers the problem of annotating datapoints using an expert with only a few annotation rounds in a label-scarce setting. We propose soliciting reliable feedback on difficulty in annotating a datapoint from the expert in addition to ground truth label. Existing literature in active learning or coreset selection turns out to be less relevant to our setting since they presume the existence of a reliable trained model, which is absent in the label-scarce regime. However, the literature on coreset selection emphasizes the presence of difficult data points in the training set to perform supervised learning in downstream tasks (Mindermann et al., 2022). Therefore, for a given fixed annotation budget of $\mathsf{T}$ rounds, we model the sequential decision-making problem of which (difficult) datapoints to choose for annotation in a sparse linear bandits framework with the constraint that no arm can be pulled more than once (blocking constraint). With mild assumptions on the datapoints, our (computationally efficient) Explore-Then-Commit algorithm BSLB achieves a regret guarantee of $\widetilde{\mathsf{O}}(k^{\frac{1}{3}} \mathsf{T}^{\frac{2}{3}} +k^{-\frac{1}{2}} \beta_k + k^{-\frac{1}{12}} \beta_k^{\frac{1}{2}}\mathsf{T}^{\frac{5}{6}})$ where the unknown parameter vector has tail magnitude $\beta_k$ at sparsity level $k$. To this end, we show offline statistical guarantees of Lasso estimator with mild Restricted Eigenvalue (RE) condition that is also robust to sparsity. Finally, we propose a meta-algorithm C-BSLB that does not need knowledge of the optimal sparsity parameters at a no-regret cost. We demonstrate the efficacy of our BSLB algorithm for annotation in the label-scarce setting for an image classification task on the PASCAL-VOC dataset, where we use real-world annotation difficulty scores.
    

[Arxiv](https://arxiv.org/pdf/2410.20041)