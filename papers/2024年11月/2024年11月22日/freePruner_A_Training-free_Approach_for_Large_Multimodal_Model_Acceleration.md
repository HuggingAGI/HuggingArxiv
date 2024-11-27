# freePruner：一种实现大型多模态模型加速的免训练途径

发布时间：2024年11月22日

`LLM应用` `计算机视觉` `模型加速`

> freePruner: A Training-free Approach for Large Multimodal Model Acceleration

# 摘要

> 大型多模态模型（LMMs）在视觉语言任务方面能力出众，令人赞叹，但其高计算需求致使部署面临重大挑战。近期的令牌精简方法虽有望加速 LMMs，可通常得大量重训或微调，对众多前沿模型，尤其是那些拥有专属训练数据的模型而言，并不实用。我们推出了 freePruner，这是一种无需训练的令牌精简手段，能直接用于任何开源 LMM，无需额外训练。和那些严重依赖令牌合并操作的现有方法不同，freePruner 采用了两阶段令牌选择策略：其一，利用我们设计的贡献度指标，识别出捕获高级语义信息的关键令牌；其二，通过注意力模式分析，选出能保留基本低级视觉细节的补充令牌。大量实验表明，在无需训练的情况下，freePruner 实现了 2 倍加速，同时在主流视觉问答基准测试中的性能相当。而且，freePruner 与其他训练后加速技术（如训练后量化）互不干扰，还能与之结合，为 LMM 的高效部署提供了切实可行的方案。

> Large Multimodal Models (LMMs) have demonstrated impressive capabilities in visual-language tasks but face significant deployment challenges due to their high computational demands. While recent token reduction methods show promise for accelerating LMMs, they typically require extensive retraining or fine-tuning, making them impractical for many state-of-the-art models, especially those with proprietary training data. We propose freePruner, a training-free token reduction approach that can be directly applied to any open-source LMM without additional training. Unlike existing methods that rely heavily on token merging operations, freePruner employs a two-stage token selection strategy: (1) identifying pivotal tokens that capture high-level semantic information using our designed contribution degree metric, and (2) selecting complementary tokens that preserve essential low-level visual details through attention pattern analysis. Extensive experiments demonstrate that freePruner achieves 2x acceleration while maintaining comparable performance across mainstream visual question-answering benchmarks in the training-free setting. Moreover, freePruner is orthogonal to and can be combined with other post-training acceleration techniques, such as post-training quantization, providing a practical solution for efficient LMM deployment.

[Arxiv](https://arxiv.org/abs/2411.15446)