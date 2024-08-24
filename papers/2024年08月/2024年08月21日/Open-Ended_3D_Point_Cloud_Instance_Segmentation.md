# 三维点云实例的开放式分割

发布时间：2024年08月21日

`LLM应用` `计算机视觉` `人工智能`

> Open-Ended 3D Point Cloud Instance Segmentation

# 摘要

> OV-3DIS 方法虽能泛化至未见对象，但测试时仍需预定义类名，限制了自主性。为此，我们提出 OE-3DIS 问题，测试时无需预定义类名。我们还基于 OV-3DIS 方法和 2D 多模态 LLM，构建了一套全面基线。为评估 OE-3DIS 系统，我们引入了 Open-Ended 评分，综合考量预测掩码的语义和几何质量及标准 AP 评分。实验表明，我们的方法在 ScanNet200 和 ScanNet++ 数据集上显著提升，甚至在无真实类名时，也超越了当前 OV-3DIS 领域的顶尖方法 Open3DIS。

> Open-Vocab 3D Instance Segmentation methods (OV-3DIS) have recently demonstrated their ability to generalize to unseen objects. However, these methods still depend on predefined class names during testing, restricting the autonomy of agents. To mitigate this constraint, we propose a novel problem termed Open-Ended 3D Instance Segmentation (OE-3DIS), which eliminates the necessity for predefined class names during testing. Moreover, we contribute a comprehensive set of strong baselines, derived from OV-3DIS approaches and leveraging 2D Multimodal Large Language Models. To assess the performance of our OE-3DIS system, we introduce a novel Open-Ended score, evaluating both the semantic and geometric quality of predicted masks and their associated class names, alongside the standard AP score. Our approach demonstrates significant performance improvements over the baselines on the ScanNet200 and ScanNet++ datasets. Remarkably, our method surpasses the performance of Open3DIS, the current state-of-the-art method in OV-3DIS, even in the absence of ground-truth object class names.

[Arxiv](https://arxiv.org/abs/2408.11747)