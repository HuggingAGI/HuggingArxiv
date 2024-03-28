# 本研究旨在探究大型语言模型在摘要心理健康咨询会谈内容方面的效能，通过设立基准进行深入研究。

发布时间：2024年02月29日

`LLM应用`

> Exploring the Efficacy of Large Language Models in Summarizing Mental Health Counseling Sessions: A Benchmark Study

# 摘要

> 全面的会谈总结对于保持心理健康咨询的连贯性和制定明智的治疗方案至关重要，但手动摘要是项耗时且易分散咨询师注意力的任务。本研究探讨了最新大型语言模型（LLMs）在通过基于方面的摘要方式有针对性地总结各类治疗会谈内容上的表现，并通过构建MentalCLOUDS数据集来进行基准测试。该数据集包含191个会谈记录及其分别针对三种关键咨询组成部分的摘要。同时，我们考察了11种顶尖LLMs在完成针对咨询组成部分的引导式摘要任务中的能力。生成的摘要不仅使用了标准量化摘要指标（如Rouge-1、Rouge-2、Rouge-L和BERTScore）进行详尽评估，还获得了心理健康专业人士的定性认可。结果显示，MentalLlama、Mistral和MentalBART这类针对任务优化的LLMs在各个咨询组成部分均展现出卓越的量化性能。然而，专家评审指出，尽管Mistral在情感态度、负担、伦理考量、连贯性、机会成本及感知效果六大评价维度上优于MentalLlama和MentalBART，但三者在机会成本与感知效果这两项指标上仍有待提升的空间。

> Comprehensive summaries of sessions enable an effective continuity in mental health counseling, facilitating informed therapy planning. Yet, manual summarization presents a significant challenge, diverting experts' attention from the core counseling process. This study evaluates the effectiveness of state-of-the-art Large Language Models (LLMs) in selectively summarizing various components of therapy sessions through aspect-based summarization, aiming to benchmark their performance. We introduce MentalCLOUDS, a counseling-component guided summarization dataset consisting of 191 counseling sessions with summaries focused on three distinct counseling components (aka counseling aspects). Additionally, we assess the capabilities of 11 state-of-the-art LLMs in addressing the task of component-guided summarization in counseling. The generated summaries are evaluated quantitatively using standard summarization metrics and verified qualitatively by mental health professionals. Our findings demonstrate the superior performance of task-specific LLMs such as MentalLlama, Mistral, and MentalBART in terms of standard quantitative metrics such as Rouge-1, Rouge-2, Rouge-L, and BERTScore across all aspects of counseling components. Further, expert evaluation reveals that Mistral supersedes both MentalLlama and MentalBART based on six parameters -- affective attitude, burden, ethicality, coherence, opportunity costs, and perceived effectiveness. However, these models share the same weakness by demonstrating a potential for improvement in the opportunity costs and perceived effectiveness metrics.

[Arxiv](https://arxiv.org/abs/2402.19052)