# ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。

发布时间：2024年04月21日

`LLM应用` `对话系统` `搜索引擎`

> ChatRetriever: Adapting Large Language Models for Generalized and Robust Conversational Dense Retrieval

# 摘要

> 对话搜索需精准解读多轮对话中的用户意图。本论文提出了 ChatRetriever，它利用大型语言模型的强泛化能力，有效捕捉复杂对话场景，以实现密集检索。我们引入了一种简洁高效的双学习策略，通过对比学习对 LLM 进行检索优化，并通过在优质对话指令数据上进行掩码指令微调，提升对复杂会话的理解。在五个对话搜索基准上的广泛测试显示，ChatRetriever 在性能上显著超越了现有的对话密集检索系统，并与基于 LLM 的改写方法达到了同等的最先进水平。ChatRetriever 在应对多样化对话场景时也展现了更高的鲁棒性。本研究强调了为检索任务适配 LLM 的潜力，尤其是在处理如对话搜索会话这类复杂输入时，并提出了一种推进该研究方向的有效方法。

> Conversational search requires accurate interpretation of user intent from complex multi-turn contexts. This paper presents ChatRetriever, which inherits the strong generalization capability of large language models to robustly represent complex conversational sessions for dense retrieval. To achieve this, we propose a simple and effective dual-learning approach that adapts LLM for retrieval via contrastive learning while enhancing the complex session understanding through masked instruction tuning on high-quality conversational instruction tuning data. Extensive experiments on five conversational search benchmarks demonstrate that ChatRetriever substantially outperforms existing conversational dense retrievers, achieving state-of-the-art performance on par with LLM-based rewriting approaches. Furthermore, ChatRetriever exhibits superior robustness in handling diverse conversational contexts. Our work highlights the potential of adapting LLMs for retrieval with complex inputs like conversational search sessions and proposes an effective approach to advance this research direction.

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x1.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x2.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x3.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x4.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x5.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x6.png)

![ChatRetriever：为对话密集检索量身定制大型语言模型，以实现更广泛和更稳健的应用。](../../../paper_images/2404.13556/x7.png)

[Arxiv](https://arxiv.org/abs/2404.13556)