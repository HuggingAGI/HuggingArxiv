# 生物医学事件抽取：结构感知生成方法

发布时间：2024年08月12日

`LLM应用` `生物医学`

> Biomedical Event Extraction via Structure-aware Generation

# 摘要

> 生物医学事件抽取（BEE）任务复杂，涉及细粒度实体间的关系建模。现有BEE模型多依赖分类方法，忽视了标签语义和参数依赖结构。为此，我们提出GenBEE，一种结合结构感知前缀的生成模型，用于BEE。GenBEE利用LLM提炼的知识构建事件提示，兼顾标签语义与参数依赖。同时，引入结构前缀学习模块，生成富含结构特征的前缀，增强生成过程。实验表明，GenBEE在多个基准数据集上表现卓越，尤其在MLEE和GE11数据集上达到顶尖水平。分析还显示，结构前缀有效连接了结构提示与生成模型表示空间，优化了事件结构信息的整合。

> Biomedical Event Extraction (BEE) is a critical task that involves modeling complex relationships between fine-grained entities in biomedical text data. However, most existing BEE models rely on classification methods that neglect the label semantics and argument dependency structure within the data. To address these limitations, we propose GenBEE, a generative model enhanced with a structure-aware prefix for biomedical event extraction. GenBEE constructs event prompts that leverage knowledge distilled from large language models (LLMs), thereby incorporating both label semantics and argument dependency relationships. Additionally, GenBEE introduces a structural prefix learning module that generates structure-aware prefixes with structural prompts, enriching the generation process with structural features. Extensive experiments on three benchmark datasets demonstrate the effectiveness of GenBEE and it achieves state-of-the-art performance on the MLEE and GE11 datasets. Furthermore, our analysis shows that the structural prefixes effectively bridge the gap between structural prompts and the representation space of generative models, enabling better integration of event structural information.

[Arxiv](https://arxiv.org/abs/2408.06583)