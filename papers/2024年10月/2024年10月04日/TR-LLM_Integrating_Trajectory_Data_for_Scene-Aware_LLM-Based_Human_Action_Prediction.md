# TR-LLM：通过集成轨迹数据，实现基于场景感知的 LLM 人类动作预测

发布时间：2024年10月04日

`LLM应用` `机器人` `智能家居`

> TR-LLM: Integrating Trajectory Data for Scene-Aware LLM-Based Human Action Prediction

# 摘要

> 预测人类行为对 AI 系统在现实应用中至关重要，如自主机器人协助人类任务。然而，现实场景中的遮挡和不完整观察常影响预测准确性，使传统视频方法受限。大型语言模型 (LLM) 通过大量文本训练，可能在家居环境中编码人类行为序列，但缺乏空间意识和实时感知。为此，我们提出多模态框架，结合物理约束增强 LLM 预测。实验显示，结合轨迹数据显著提升预测性能，尤其在场景信息有限时，突显语言与物理约束的互补性。

> Accurate prediction of human behavior is crucial for AI systems to effectively support real-world applications, such as autonomous robots anticipating and assisting with human tasks. Real-world scenarios frequently present challenges such as occlusions and incomplete scene observations, which can compromise predictive accuracy. Thus, traditional video-based methods often struggle due to limited temporal and spatial perspectives. Large Language Models (LLMs) offer a promising alternative. Having been trained on a large text corpus describing human behaviors, LLMs likely encode plausible sequences of human actions in a home environment. However, LLMs, trained primarily on text data, lack inherent spatial awareness and real-time environmental perception. They struggle with understanding physical constraints and spatial geometry. Therefore, to be effective in a real-world spatial scenario, we propose a multimodal prediction framework that enhances LLM-based action prediction by integrating physical constraints derived from human trajectories. Our experiments demonstrate that combining LLM predictions with trajectory data significantly improves overall prediction performance. This enhancement is particularly notable in situations where the LLM receives limited scene information, highlighting the complementary nature of linguistic knowledge and physical constraints in understanding and anticipating human behavior.

[Arxiv](https://arxiv.org/abs/2410.03993)