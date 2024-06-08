# 探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。

发布时间：2024年06月04日

`RAG

理由：这篇论文主要探讨了如何利用检索增强生成（RAG）方法和具有长上下文窗口的大型语言模型（LLMs）来处理和分析时间复杂事件（TCE）。论文中提到的使用RAG方法和长上下文窗口的LLMs来应对长篇新闻文章，以及设立的基准TCELongBench来评估LLMs的能力，都直接关联到RAG的应用。因此，这篇论文应归类为RAG。` `新闻分析` `事件预测`

> Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding

# 摘要

> 随着在线新闻量的激增，数字环境正迅速变化，迫切需要对复杂事件进行快速而精确的分析。我们称由多篇跨越长时间段的新闻文章构成的复杂事件为时间复杂事件（TCE）。本文提出了一种创新方法，利用大型语言模型（LLMs）系统地提取和分析TCE中的事件链，这些事件链以关键点和时间戳为特征。我们设立了名为TCELongBench的基准，以评估LLMs在处理时间动态和理解大量文本方面的能力，涵盖了阅读理解、时间排序和未来事件预测三个任务。实验中，我们采用了检索增强生成（RAG）方法和具有长上下文窗口的LLMs来应对TCE的长篇新闻文章。研究结果显示，配备合适检索器的模型与使用长上下文窗口的模型表现相当。

> The digital landscape is rapidly evolving with an ever-increasing volume of online news, emphasizing the need for swift and precise analysis of complex events. We refer to the complex events composed of many news articles over an extended period as Temporal Complex Event (TCE). This paper proposes a novel approach using Large Language Models (LLMs) to systematically extract and analyze the event chain within TCE, characterized by their key points and timestamps. We establish a benchmark, named TCELongBench, to evaluate the proficiency of LLMs in handling temporal dynamics and understanding extensive text. This benchmark encompasses three distinct tasks - reading comprehension, temporal sequencing, and future event forecasting. In the experiment, we leverage retrieval-augmented generation (RAG) method and LLMs with long context window to deal with lengthy news articles of TCE. Our findings indicate that models with suitable retrievers exhibit comparable performance with those utilizing long context window.

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/example_intro.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/pipeline_data_constr.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/distr_day_gap.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/distr_token.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/starts_ques.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/pipeline_baselines.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/distr_long_qa_acc.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/lost_middle_detail.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/experi_retri_order_accbydate.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/Forecast_error_analysis.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/four_choice_distr_MCQ.png)

![探究大型语言模型如何处理时间复杂事件？这一基准旨在评估其对时间及长上下文的理解能力。](../../../paper_images/2406.02472/four_choice_distr_fore.png)

[Arxiv](https://arxiv.org/abs/2406.02472)