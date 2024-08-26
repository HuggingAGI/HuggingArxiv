# GPT-4 模型是否能识别误导性图表？

发布时间：2024年08月08日

`LLM应用` `公共卫生` `社交媒体`

> Can GPT-4 Models Detect Misleading Visualizations?

# 摘要

> 在网络空间，误导性可视化内容的泛滥，尤其是在公共卫生危机和选举等关键时刻，已成为一大隐患。本研究聚焦于GPT-4系列模型（4V、4o及4o mini）在识别这些误导性可视化方面的能力。通过一个包含多种视觉误导元素的推文与可视化配对数据集，我们在四种不同指导程度的实验条件下对这些模型进行了测试。结果显示，即便未经预训练（即朴素零-shot），GPT-4模型也能以中等准确度识别误导性可视化，而当模型获得误导元素的定义（引导零-shot）时，其性能显著提升。但值得注意的是，并非单一的提示工程策略能适用于所有误导类型。具体来说，提供误导元素的定义及实例（引导少-shot）对识别推理类误导更为有效，而针对设计类误导，引导零-shot则表现更佳。此项研究不仅验证了大型视觉-语言模型在检测视觉虚假信息方面的可行性，也凸显了提示工程在提升检测准确性中的关键作用。

> The proliferation of misleading visualizations online, particularly during critical events like public health crises and elections, poses a significant risk. This study investigates the capability of GPT-4 models (4V, 4o, and 4o mini) to detect misleading visualizations. Utilizing a dataset of tweet-visualization pairs containing various visual misleaders, we test these models under four experimental conditions with different levels of guidance. We show that GPT-4 models can detect misleading visualizations with moderate accuracy without prior training (naive zero-shot) and that performance notably improves when provided with definitions of misleaders (guided zero-shot). However, a single prompt engineering technique does not yield the best results for all misleader types. Specifically, providing the models with misleader definitions and examples (guided few-shot) proves more effective for reasoning misleaders, while guided zero-shot performs better for design misleaders. This study underscores the feasibility of using large vision-language models to detect visual misinformation and the importance of prompt engineering for optimized detection accuracy.

[Arxiv](https://arxiv.org/abs/2408.12617)