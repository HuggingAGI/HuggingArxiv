# 通过大规模 LLM 代理模拟实现动态与文本图生成

发布时间：2024年10月13日

`Agent` `图生成` `网络分析`

> Dynamic and Textual Graph Generation Via Large-Scale LLM-based Agent Simulation

# 摘要

> 图生成在多个领域中备受关注，但传统方法在动态图演化中表现不佳。我们推出了GraphAgent-Generator（GAG），一个无需LLM训练的模拟框架，能有效捕捉图的宏观结构，并在图扩展任务中超越现有方法31%。GAG还能生成包含近10万节点和千万条边的复杂图，加速比高达90.4%。源代码已公开，详见https://anonymous.4open.science/r/GraphAgent-2206。

> Graph generation is a fundamental task that has been extensively studied in social, technological, and scientific analysis. For modeling the dynamic graph evolution process, traditional rule-based methods struggle to capture community structures within graphs, while deep learning methods only focus on fitting training graphs. This limits existing graph generators to producing graphs that adhere to predefined rules or closely resemble training datasets, achieving poor performance in dynamic graph generation. Given that graphs are abstract representations arising from pairwise interactions in human activities, a realistic simulation of human-wise interaction could provide deeper insights into the graph evolution mechanism. With the increasing recognition of large language models (LLMs) in simulating human behavior, we introduce GraphAgent-Generator (GAG), a novel simulation-based framework for dynamic graph generation. Without training or fine-tuning process of LLM, our framework effectively replicates seven macro-level structural characteristics in established network science theories while surpassing existing baselines in graph expansion tasks by 31\% on specific evaluation metrics. Through node classification task, we validate GAG effectively preserves characteristics of real-world network for node-wise textual features in generated text-rich graph. Furthermore, by incorporating parallel acceleration, GAG supports generating graphs with up to nearly 100,000 nodes or 10 million edges through large-scale LLM-based agent simulation, with a minimum speed-up of 90.4\%. The source code is available at https://anonymous.4open.science/r/GraphAgent-2206.

[Arxiv](https://arxiv.org/abs/2410.09824)