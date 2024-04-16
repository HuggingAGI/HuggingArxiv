# OneChart：利用单一辅助标记净化图表结构提取过程。

发布时间：2024年04月15日

`LLM应用` `图表解析` `自动化工具`

> OneChart: Purify the Chart Structural Extraction via One Auxiliary Token

# 摘要

> 图表解析任务因样式和内容的多样性而极具挑战性，即便是参数众多的高级视觉-语言模型（LVLMs）也难以轻松应对。为此，我们推出了OneChart，这是一个专为提取图表结构信息而设计的高效工具。OneChart沿用了LVLMs的自回归主体，并创新性地引入了一个位于所有令牌之首的辅助令牌和一个附加解码器，以增强输出中数值数据的准确性。这个经过数值优化的辅助令牌使得图表解析过程中的后续令牌能够更精准地识别数值特征。借助这一机制，我们还开发了一种自我评估系统，让模型能够通过置信度评分来判断其解析结果的可靠性。在多个公共基准测试中，OneChart在图表结构提取的平均精度（AP）方面大幅超越了现有的最先进模型，如DePlot、ChartVLM和ChartAst，尽管其参数仅为2亿。此外，OneChart作为图表解析工具，还显著提升了流行LVLM（LLaVA-1.6）在ChartQA基准测试中的准确性，增幅超过10%。

> Chart parsing poses a significant challenge due to the diversity of styles, values, texts, and so forth. Even advanced large vision-language models (LVLMs) with billions of parameters struggle to handle such tasks satisfactorily. To address this, we propose OneChart: a reliable agent specifically devised for the structural extraction of chart information. Similar to popular LVLMs, OneChart incorporates an autoregressive main body. Uniquely, to enhance the reliability of the numerical parts of the output, we introduce an auxiliary token placed at the beginning of the total tokens along with an additional decoder. The numerically optimized (auxiliary) token allows subsequent tokens for chart parsing to capture enhanced numerical features through causal attention. Furthermore, with the aid of the auxiliary token, we have devised a self-evaluation mechanism that enables the model to gauge the reliability of its chart parsing results by providing confidence scores for the generated content. Compared to current state-of-the-art (SOTA) chart parsing models, e.g., DePlot, ChartVLM, ChartAst, OneChart significantly outperforms in Average Precision (AP) for chart structural extraction across multiple public benchmarks, despite enjoying only 0.2 billion parameters. Moreover, as a chart parsing agent, it also brings 10%+ accuracy gains for the popular LVLM (LLaVA-1.6) in the downstream ChartQA benchmark.

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/chart_6_v2.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/chart_3_v3.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/chart_2_v5.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/chart-infer2.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/append1.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/append2.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/append4.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/append3.png)

![OneChart：利用单一辅助标记净化图表结构提取过程。](../../../paper_images/2404.09987/chart_qa_all.png)

[Arxiv](https://arxiv.org/abs/2404.09987)