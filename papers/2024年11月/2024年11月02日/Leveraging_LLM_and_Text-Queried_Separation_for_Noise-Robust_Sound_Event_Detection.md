# 借助 LLM 和文本查询分离来进行抗噪声音事件检测

发布时间：2024年11月02日

`LLM应用` `音频处理` `声音检测`

> Leveraging LLM and Text-Queried Separation for Noise-Robust Sound Event Detection

# 摘要

> 声音事件检测（SED）在嘈杂环境中面临挑战，因为重叠的声音会遮蔽目标事件。语言查询音频源分离（LASS）旨在从嘈杂的片段里分离出目标声音事件。但当确切的目标声音不明时，尤其在嘈杂的测试集中，此方法可能失效，致使性能降低。为应对这一问题，我们借助大型语言模型（LLMs）的能力来分析和总结声学数据。利用 LLMs 识别并选取特定的噪声类型，我们实施了一种用于抗噪微调的噪声增强方法。微调后的模型用于预测片段级的事件预测，并作为 LASS 模型的文本查询。我们的研究表明，所提方法提升了嘈杂环境中的 SED 性能。此项工作是 LLMs 在抗噪 SED 中的早期应用，为处理 SED 中的重叠事件指明了有前景的方向。代码和预训练模型可在 https://github.com/apple-yinhan/Noise-robust-SED 获取。

> Sound Event Detection (SED) is challenging in noisy environments where overlapping sounds obscure target events. Language-queried audio source separation (LASS) aims to isolate the target sound events from a noisy clip. However, this approach can fail when the exact target sound is unknown, particularly in noisy test sets, leading to reduced performance. To address this issue, we leverage the capabilities of large language models (LLMs) to analyze and summarize acoustic data. By using LLMs to identify and select specific noise types, we implement a noise augmentation method for noise-robust fine-tuning. The fine-tuned model is applied to predict clip-wise event predictions as text queries for the LASS model. Our studies demonstrate that the proposed method improves SED performance in noisy environments. This work represents an early application of LLMs in noise-robust SED and suggests a promising direction for handling overlapping events in SED. Codes and pretrained models are available at https://github.com/apple-yinhan/Noise-robust-SED.

[Arxiv](https://arxiv.org/abs/2411.01174)