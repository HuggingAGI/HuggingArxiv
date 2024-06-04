# 大型视觉语言模型能否胜任图表理解和推理的重任？本研究深入探讨了LVLMs的能力与局限，旨在全面评估其在复杂任务中的表现。

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了大型视觉语言模型（LVLMs）在图表理解和推理任务上的表现，包括对GPT-4V和Gemini等模型在四大图表推理任务上的评估。论文通过定性分析揭示了这些模型在处理图表数据时的优势和局限，特别是在流畅表达高级数据洞察方面的能力，以及存在的问题如幻觉、事实错误和数据偏差。这些内容直接关联到LLM在特定应用场景（即数据可视化）的实际应用和性能评估，因此属于LLM应用分类。` `数据可视化`

> Are Large Vision Language Models up to the Challenge of Chart Comprehension and Reasoning? An Extensive Investigation into the Capabilities and Limitations of LVLMs

# 摘要

> 自然语言为数据可视化，如条形图和折线图，提供了强有力的补充交流方式。为了推动基于图表的自然语言推理，近期涌现了图表问答、图表摘要和图表事实核查等任务。这些任务不仅要求视觉-语言推理能力，还需要对图表数据、视觉编码及自然语言提示有深入理解。尽管大型语言模型（LLMs）在多个NLP领域取得了显著成就，但其在数据可视化方面的潜力与局限尚未充分挖掘，部分原因可能是缺乏多模态能力。为此，本文首次对新兴的大型视觉语言模型（LVLMs）在图表理解和推理任务上的表现进行了全面评估，涵盖了GPT-4V和Gemini等模型在四大图表推理任务上的表现。我们还对LVLMs在多样图表上的性能进行了深入的定性分析，揭示了它们在流畅表达高级数据洞察方面的卓越能力，同时也指出了幻觉、事实错误和数据偏差等问题。本文强调了图表理解任务的关键优势与局限，为未来研究提供了方向。

> Natural language is a powerful complementary modality of communication for data visualizations, such as bar and line charts. To facilitate chart-based reasoning using natural language, various downstream tasks have been introduced recently such as chart question answering, chart summarization, and fact-checking with charts. These tasks pose a unique challenge, demanding both vision-language reasoning and a nuanced understanding of chart data tables, visual encodings, and natural language prompts. Despite the recent success of Large Language Models (LLMs) across diverse NLP tasks, their abilities and limitations in the realm of data visualization remain under-explored, possibly due to their lack of multi-modal capabilities. To bridge the gap, this paper presents the first comprehensive evaluation of the recently developed large vision language models (LVLMs) for chart understanding and reasoning tasks. Our evaluation includes a comprehensive assessment of LVLMs, including GPT-4V and Gemini, across four major chart reasoning tasks. Furthermore, we perform a qualitative evaluation of LVLMs' performance on a diverse range of charts, aiming to provide a thorough analysis of their strengths and weaknesses. Our findings reveal that LVLMs demonstrate impressive abilities in generating fluent texts covering high-level data insights while also encountering common problems like hallucinations, factual errors, and data bias. We highlight the key strengths and limitations of chart comprehension tasks, offering insights for future research.

[Arxiv](https://arxiv.org/abs/2406.00257)