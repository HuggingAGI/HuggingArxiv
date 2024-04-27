# 沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析

发布时间：2024年04月18日

`分类：RAG` `信息检索` `问答系统`

> Spiral of Silences: How is Large Language Model Killing Information Retrieval? -- A Case Study on Open Domain Question Answering

# 摘要

> 检索增强生成（RAG）技术，通过将大型语言模型（LLMs）与检索系统相结合，正变得越来越流行。但LLM生成内容对网络的影响及其对检索生成反馈循环的潜在后果，目前尚不为人所充分了解。本研究通过构建并迭代执行模拟流程，深入探讨了LLM文本对RAG系统影响的短期与长期效应。以当前热门的开放域问答（ODQA）任务为例，研究发现LLM生成的文本在搜索排名中持续超越人类创作内容，可能导致人类在线贡献的可见度和影响力下降，这种现象被形象地称为数字“沉默螺旋”效应。这一趋势有可能导致信息生态系统失衡，错误信息的不受控制的扩散可能会使准确信息被边缘化。我们呼吁学术界对此潜在问题保持警觉，以维护一个多元和真实的数字信息环境。

> The practice of Retrieval-Augmented Generation (RAG), which integrates Large Language Models (LLMs) with retrieval systems, has become increasingly prevalent. However, the repercussions of LLM-derived content infiltrating the web and influencing the retrieval-generation feedback loop are largely uncharted territories. In this study, we construct and iteratively run a simulation pipeline to deeply investigate the short-term and long-term effects of LLM text on RAG systems. Taking the trending Open Domain Question Answering (ODQA) task as a point of entry, our findings reveal a potential digital "Spiral of Silence" effect, with LLM-generated text consistently outperforming human-authored content in search rankings, thereby diminishing the presence and impact of human contributions online. This trend risks creating an imbalanced information ecosystem, where the unchecked proliferation of erroneous LLM-generated content may result in the marginalization of accurate information. We urge the academic community to take heed of this potential issue, ensuring a diverse and authentic digital information landscape.

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pipeline.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_sim.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_sim.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_sim.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_sim.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_loop_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_loop_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_loop_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_loop_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/percentage_nq.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/percentage_pop.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_bleu.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_bleu.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/context_nq.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/Overall_Average_Rank_Changes.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/Combined_Average_Ranks.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_loop_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_loop_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_loop_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_loop_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/percentage_webq.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/percentage_tqa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_bleu.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_bleu.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/mis_plot_nq_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/mis_plot_webq_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/mis_plot_tqa_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/mis_plot_pop_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/mis_context_nq.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/combined_qa_datasets.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_filter_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_filter_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_filter_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_filter_retrieval.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/nq_filter_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/webq_filter_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/tqa_filter_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/pop_filter_qa.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/top5-plot_nq_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/top5-plot_nq-filter-bleu_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/top5-plot_nq-filter-source_tsv.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/filter_bleu_context_nq.png)

![沉默的螺旋：探究大型语言模型如何影响信息检索的效能——以开放领域问答任务为案例分析](../../../paper_images/2404.10496/filter_source_context_nq.png)

[Arxiv](https://arxiv.org/abs/2404.10496)