# MMRole：开发与评估多模态角色扮演代理的综合框架

发布时间：2024年08月07日

`Agent` `人工智能`

> MMRole: A Comprehensive Framework for Developing and Evaluating Multimodal Role-Playing Agents

# 摘要

> 角色扮演代理 (RPAs) 因其情感价值和社会学研究潜力而备受瞩目，但现有研究多限于文本形式，未能模拟人类的多感官体验。为此，我们提出多模态角色扮演代理 (MRPAs) 概念，并构建了包含 85 个角色、11K 图像及 14K 对话的 MMRole-Data 数据集，以及涵盖三维度八指标的 MMRole-Eval 评估方法。我们还开发了首个 MRPA——MMRole-Agent，其卓越表现凸显了多模态理解和角色一致性的重要性。相关资源将在 GitHub 上公开。

> Recently, Role-Playing Agents (RPAs) have garnered increasing attention for their potential to deliver emotional value and facilitate sociological research. However, existing studies are primarily confined to the textual modality, unable to simulate humans' multimodal perceptual capabilities. To bridge this gap, we introduce the concept of Multimodal Role-Playing Agents (MRPAs), and propose a comprehensive framework, MMRole, for their development and evaluation, which comprises a personalized multimodal dataset and a robust evaluation method. Specifically, we construct a large-scale, high-quality dataset, MMRole-Data, consisting of 85 characters, 11K images, and 14K single or multi-turn dialogues. Additionally, we present a robust evaluation method, MMRole-Eval, encompassing eight metrics across three dimensions, where a reward model is trained to score MRPAs with the constructed ground-truth data for comparison. Moreover, we develop the first specialized MRPA, MMRole-Agent. Extensive evaluation results demonstrate the improved performance of MMRole-Agent and highlight the primary challenges in developing MRPAs, emphasizing the need for enhanced multimodal understanding and role-playing consistency. The data, code, and models will be available at https://github.com/YanqiDai/MMRole.

[Arxiv](https://arxiv.org/abs/2408.04203)