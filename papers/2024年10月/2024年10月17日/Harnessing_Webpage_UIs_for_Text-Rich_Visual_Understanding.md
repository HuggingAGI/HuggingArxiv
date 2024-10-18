# 借助网页UI，深入探索文本与视觉的丰富结合

发布时间：2024年10月17日

`LLM应用` `网页设计` `人工智能`

> Harnessing Webpage UIs for Text-Rich Visual Understanding

# 摘要

> 文本与视觉结合的丰富理解能力，对多模态大型语言模型（MLLM）与结构化环境互动至关重要。为此，我们提出利用基于文本的大型语言模型（LLM）从网页UI中生成多模态指令。尽管缺乏视觉输入，LLM仍能处理网页可访问性树中的结构化文本。这些指令随后与UI截图结合，用于训练多模态模型。我们创建了MultiUI数据集，包含730万个样本，来自100万个网站，涵盖多种多模态任务和UI布局。在MultiUI上训练的模型不仅在网页UI任务中表现优异，如在VisualWebBench上提升48%，在Mind2Web上动作准确性提高19.1%，还能出色地泛化到非网页UI任务和非UI领域，如文档理解、OCR和图表解读。这些成果展示了网页UI数据在提升各种场景中文本视觉理解能力的广泛应用。

> Text-rich visual understanding-the ability to process environments where dense textual content is integrated with visuals-is crucial for multimodal large language models (MLLMs) to interact effectively with structured environments. To enhance this capability, we propose synthesizing general multimodal instructions from webpage UIs using text-based large language models (LLMs). Despite lacking direct visual input, text-based LLMs are able to process structured text representations from webpage accessibility trees. These instructions are then paired with UI screenshots to train multimodal models. We introduce MultiUI, a dataset containing 7.3 million samples from 1 million websites, covering diverse multimodal tasks and UI layouts. Models trained on MultiUI not only excel in web UI tasks-achieving up to a 48\% improvement on VisualWebBench and a 19.1\% boost in action accuracy on a web agent dataset Mind2Web-but also generalize surprisingly well to non-web UI tasks and even to non-UI domains, such as document understanding, OCR, and chart interpretation. These results highlight the broad applicability of web UI data for advancing text-rich visual understanding across various scenarios.

[Arxiv](https://arxiv.org/abs/2410.13824)