# 探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。

发布时间：2024年06月04日

`RAG

这篇论文主要介绍了利用大型语言模型（LLMs）来提取和分析时间复杂事件（Temporal Complex Event，TCE）中的事件链，并设立了基准TCELongBench来评估LLMs的能力。特别强调了使用检索增强生成（RAG）技术及具有长上下文窗口的LLMs来处理长篇新闻。因此，这篇论文更符合RAG分类，因为它专注于使用RAG技术来增强LLMs在处理复杂时间事件上的能力。` `新闻分析` `事件预测`

> Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding

# 摘要

> 数字世界正因海量在线新闻的涌入而快速变化，这凸显了快速精准分析复杂事件的重要性。我们称那些由跨越长时间段的多篇新闻构成的复杂事件为时间复杂事件（Temporal Complex Event，TCE）。本文介绍了一种创新方法，利用大型语言模型（LLMs）来系统地提取和分析TCE中的事件链，这些事件链的关键点和时间戳是其特色。我们设立了名为TCELongBench的基准，用以衡量LLMs在处理时间动态和理解长篇文本方面的能力。该基准涵盖了阅读理解、时间序列排序和未来事件预测三个任务。实验中，我们采用了检索增强生成（RAG）技术及具有长上下文窗口的LLMs来应对TCE中的长篇新闻。研究结果显示，配备恰当检索器的模型与依赖长上下文窗口的模型表现不相上下。

> The digital landscape is rapidly evolving with an ever-increasing volume of online news, emphasizing the need for swift and precise analysis of complex events. We refer to the complex events composed of many news articles over an extended period as Temporal Complex Event (TCE). This paper proposes a novel approach using Large Language Models (LLMs) to systematically extract and analyze the event chain within TCE, characterized by their key points and timestamps. We establish a benchmark, named TCELongBench, to evaluate the proficiency of LLMs in handling temporal dynamics and understanding extensive text. This benchmark encompasses three distinct tasks - reading comprehension, temporal sequencing, and future event forecasting. In the experiment, we leverage retrieval-augmented generation (RAG) method and LLMs with long context window to deal with lengthy news articles of TCE. Our findings indicate that models with suitable retrievers exhibit comparable performance with those utilizing long context window.

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/example_intro.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/pipeline_data_constr.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/distr_day_gap.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/distr_token.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/starts_ques.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/pipeline_baselines.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/distr_long_qa_acc.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/lost_middle_detail.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/experi_retri_order_accbydate.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/Forecast_error_analysis.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/four_choice_distr_MCQ.png)

![探究大型语言模型如何应对时间复杂事件？这一基准旨在衡量其对长时序上下文的理解能力。](../../../paper_images/2406.02472/four_choice_distr_fore.png)

[Arxiv](https://arxiv.org/abs/2406.02472)