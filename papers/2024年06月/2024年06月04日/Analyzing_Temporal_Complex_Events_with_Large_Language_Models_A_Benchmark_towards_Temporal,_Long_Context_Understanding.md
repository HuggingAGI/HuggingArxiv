# 探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。

发布时间：2024年06月04日

`RAG

这篇论文主要介绍了如何使用大型语言模型（LLMs）来提取和分析时间复杂事件（TCE）中的事件链，并为此设立了基准TCELongBench。特别强调了使用检索增强生成（RAG）技术以及具有长上下文窗口的LLMs来处理长篇新闻文章。因此，这篇论文的核心在于探讨和应用RAG技术在处理复杂事件分析中的应用，属于RAG分类。` `新闻媒体`

> Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding

# 摘要

> 数字领域的快速发展伴随着在线新闻量的激增，这凸显了对复杂事件进行快速精准分析的迫切需求。我们将这类由多篇新闻文章组成、跨越较长时间的事件定义为时间复杂事件（TCE）。本文介绍了一种创新方法，运用大型语言模型（LLMs）来系统地提取和分析TCE中的事件链，这些事件链的关键点和时间戳是其显著特征。为此，我们设立了名为TCELongBench的基准，用以评估LLMs在处理时间动态和理解大量文本方面的能力。该基准涵盖了阅读理解、时间排序和未来事件预测三大任务。实验中，我们采用了检索增强生成（RAG）技术及具有长上下文窗口的LLMs来应对TCE中的长篇新闻文章。研究结果显示，配备高效检索器的模型与依赖长上下文窗口的模型在性能上不相上下。

> The digital landscape is rapidly evolving with an ever-increasing volume of online news, emphasizing the need for swift and precise analysis of complex events. We refer to the complex events composed of many news articles over an extended period as Temporal Complex Event (TCE). This paper proposes a novel approach using Large Language Models (LLMs) to systematically extract and analyze the event chain within TCE, characterized by their key points and timestamps. We establish a benchmark, named TCELongBench, to evaluate the proficiency of LLMs in handling temporal dynamics and understanding extensive text. This benchmark encompasses three distinct tasks - reading comprehension, temporal sequencing, and future event forecasting. In the experiment, we leverage retrieval-augmented generation (RAG) method and LLMs with long context window to deal with lengthy news articles of TCE. Our findings indicate that models with suitable retrievers exhibit comparable performance with those utilizing long context window.

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/example_intro.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/pipeline_data_constr.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/distr_day_gap.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/distr_token.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/starts_ques.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/pipeline_baselines.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/distr_long_qa_acc.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/lost_middle_detail.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/experi_retri_order_accbydate.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/Forecast_error_analysis.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/four_choice_distr_MCQ.png)

![探究大型语言模型如何应对时间复杂事件？我们提出了一项基准测试，旨在评估模型在处理长时序上下文理解方面的能力。](../../../paper_images/2406.02472/four_choice_distr_fore.png)

[Arxiv](https://arxiv.org/abs/2406.02472)