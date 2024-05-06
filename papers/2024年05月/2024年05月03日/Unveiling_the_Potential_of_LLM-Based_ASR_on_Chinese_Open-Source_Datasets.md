# 探索基于大型语言模型的自动语音识别技术在中文开源数据集中的应用潜力。

发布时间：2024年05月03日

`LLM应用` `自动语音识别`

> Unveiling the Potential of LLM-Based ASR on Chinese Open-Source Datasets

# 摘要

> 大型语言模型（LLM）在自然语言处理（NLP）任务上展现了非凡的效能，其与自动语音识别（ASR）技术的融合正逐渐成为主流。本研究乘势而上，深入分析了这一融合在大规模开源中文数据集上的表现。研究的核心在于评估不同配置的语音编码器、LLM及投影模块在语音基础编码器-LLM ASR框架中的作用。我们提出了一种三阶段训练策略，旨在提升模型整合听觉与文本信息的能力。这一策略的实施，结合ASR组件的精心整合，使我们在AISHELL1、TestNet和TestMeeting测试集上达到了行业领先水平。本研究不仅为未来基于LLM的ASR系统研究奠定了实证基础，还为使用中文数据集优化性能提供了洞见。为了推动可复制研究，我们将公开所有用于数据处理、模型训练、推理评分的脚本，以及预训练模型和训练记录。

> Large Language Models have demonstrated unparalleled effectiveness in various NLP tasks, and integrating LLMs with automatic speech recognition is becoming a mainstream paradigm. Building upon this momentum, our research delves into an indepth examination of this paradigm on a large opensource Chinese dataset. Specifically, our research aims to evaluate the impact of various configurations of speech encoders, LLMs, and projector modules in the context of the speech foundation encoderLLM ASR paradigm. Furthermore, we introduce a threestage training approach, expressly developed to enhance the model's ability to align auditory and textual information. The implementation of this approach, alongside the strategic integration of ASR components, enabled us to achieve the SOTA performance on the AISHELL1, TestNet, and TestMeeting test sets. Our analysis presents an empirical foundation for future research in LLMbased ASR systems and offers insights into optimizing performance using Chinese datasets. We will publicly release all scripts used for data preparation, training, inference, and scoring, as well as pretrained models and training logs to promote reproducible research.

[Arxiv](https://arxiv.org/abs/2405.02132)