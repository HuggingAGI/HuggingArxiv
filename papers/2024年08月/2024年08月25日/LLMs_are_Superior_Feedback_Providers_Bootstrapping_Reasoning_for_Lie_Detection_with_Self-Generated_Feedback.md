# LLM 是出色的反馈源，通过自我生成的反馈机制，助力谎言检测中的推理过程。

发布时间：2024年08月25日

`LLM应用` `人工智能`

> LLMs are Superior Feedback Providers: Bootstrapping Reasoning for Lie Detection with Self-Generated Feedback

# 摘要

> 大型语言模型（LLM）在生成逼真对话和理解文本方面表现出色，但解析语言交流中的复杂细节仍具挑战。为此，我们设计了一个引导框架，通过自我生成的反馈来提升LLM的谎言检测推理能力。该框架分为三个阶段：初步预测、反馈收集和预测优化。在初步预测阶段，一个经济高效的语言模型根据游戏情境和对话生成初始预测；随后，在反馈收集阶段，另一语言模型对这些预测进行评估；最后，在预测优化阶段，更高级的语言模型利用这些自动生成的反馈来精炼初始预测。我们探索了该框架在《外交》游戏中识别背叛与欺骗的应用，并对比了其与专业玩家反馈的效果。结果显示，LLM生成的反馈质量卓越，大幅提升了模型性能，实现了无需训练数据的谎言检测F1分数39%的增长，与顶尖的监督学习成果不相上下。

> Large Language Models (LLMs) excel at generating human-like dialogues and comprehending text. However, understanding the subtleties of complex exchanges in language remains a challenge. We propose a bootstrapping framework that leverages self-generated feedback to enhance LLM reasoning capabilities for lie detection. The framework consists of three stages: suggestion, feedback collection, and modification. In the suggestion stage, a cost-effective language model generates initial predictions based on game state and dialogue. The feedback-collection stage involves a language model providing feedback on these predictions. In the modification stage, a more advanced language model refines the initial predictions using the auto-generated feedback. We investigate the application of the proposed framework for detecting betrayal and deception in Diplomacy games, and compare it with feedback from professional human players. The LLM-generated feedback exhibits superior quality and significantly enhances the performance of the model. Our approach achieves a 39% improvement over the zero-shot baseline in lying-F1 without the need for any training data, rivaling state-of-the-art supervised learning results.

[Arxiv](https://arxiv.org/abs/2408.13915)