# MoTE：在视觉-语言到视频知识转移中，平衡泛化与专业化

发布时间：2024年10月14日

`LLM应用` `视频识别` `人工智能`

> MoTE: Reconciling Generalization with Specialization for Visual-Language to Video Knowledge Transfer

# 摘要

> 从大规模基础模型中转移视觉-语言知识用于视频识别已被证明有效。然而，随着专用参数的增加，零-shot 泛化能力减弱，使得现有工作成为零-shot 和闭集性能之间的权衡。为此，我们提出了 MoTE 框架，通过调整时间专家的混合，在统一的模型中平衡泛化和专业化。我们引入了 \emph{权重合并正则化}，以保留每个专家的知识，并通过时间特征调制优化测试期间的时间特征贡献。最终，我们在零-shot 和闭集视频识别任务之间实现了良好平衡，并在多个数据集上取得了领先或具有竞争力的结果。代码已开源。

> Transferring visual-language knowledge from large-scale foundation models for video recognition has proved to be effective. To bridge the domain gap, additional parametric modules are added to capture the temporal information. However, zero-shot generalization diminishes with the increase in the number of specialized parameters, making existing works a trade-off between zero-shot and close-set performance. In this paper, we present MoTE, a novel framework that enables generalization and specialization to be balanced in one unified model. Our approach tunes a mixture of temporal experts to learn multiple task views with various degrees of data fitting. To maximally preserve the knowledge of each expert, we propose \emph{Weight Merging Regularization}, which regularizes the merging process of experts in weight space. Additionally with temporal feature modulation to regularize the contribution of temporal feature during test. We achieve a sound balance between zero-shot and close-set video recognition tasks and obtain state-of-the-art or competitive results on various datasets, including Kinetics-400 \& 600, UCF, and HMDB. Code is available at \url{https://github.com/ZMHH-H/MoTE}.

[Arxiv](https://arxiv.org/abs/2410.10589)