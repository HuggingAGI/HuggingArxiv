# MVP-Bench：大型视觉-语言模型能否实现人类般的多层次视觉感知？

发布时间：2024年10月05日

`LLM应用` `人工智能` `计算机视觉`

> MVP-Bench: Can Large Vision--Language Models Conduct Multi-level Visual Perception Like Humans?

# 摘要

> 人类在视觉感知上分为低层次的物体识别和高层次的行为理解。细微的低层次差异能引发高层次的显著变化，比如将购物袋换成枪支，暗示暴力行为。尽管多模态任务有显著进展，大型视觉-语言模型（LVLMs）在多层次视觉感知上仍未充分探索。为探究LVLMs与人类的感知差距，我们推出了MVP-Bench，首个系统评估LVLMs低高层次视觉感知的基准。通过自然与合成图像，我们研究了内容操纵对模型感知的影响。诊断显示，高层次感知对现有LVLMs构成挑战，GPT-4o在是/否问题上的准确率仅为56%，远低于低层次的74%。此外，自然与操纵图像间的性能差距表明，LVLMs在理解合成图像的视觉语义上无法像人类那样泛化。数据与代码已公开，详见https://github.com/GuanzhenLi/MVP-Bench。

> Humans perform visual perception at multiple levels, including low-level object recognition and high-level semantic interpretation such as behavior understanding. Subtle differences in low-level details can lead to substantial changes in high-level perception. For example, substituting the shopping bag held by a person with a gun suggests violent behavior, implying criminal or violent activity. Despite significant advancements in various multimodal tasks, Large Visual-Language Models (LVLMs) remain unexplored in their capabilities to conduct such multi-level visual perceptions.
  To investigate the perception gap between LVLMs and humans, we introduce MVP-Bench, the first visual-language benchmark systematically evaluating both low- and high-level visual perception of LVLMs. We construct MVP-Bench across natural and synthetic images to investigate how manipulated content influences model perception. Using MVP-Bench, we diagnose the visual perception of 10 open-source and 2 closed-source LVLMs, showing that high-level perception tasks significantly challenge existing LVLMs. The state-of-the-art GPT-4o only achieves an accuracy of $56\%$ on Yes/No questions, compared with $74\%$ in low-level scenarios. Furthermore, the performance gap between natural and manipulated images indicates that current LVLMs do not generalize in understanding the visual semantics of synthetic images as humans do. Our data and code are publicly available at https://github.com/GuanzhenLi/MVP-Bench.

[Arxiv](https://arxiv.org/abs/2410.04345)