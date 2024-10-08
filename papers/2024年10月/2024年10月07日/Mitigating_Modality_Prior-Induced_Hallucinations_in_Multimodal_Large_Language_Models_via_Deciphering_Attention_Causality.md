# 通过揭示注意力因果，缓解多模态大型语言模型中模态先验引发的幻觉问题。

发布时间：2024年10月07日

`LLM应用` `人工智能` `计算机视觉`

> Mitigating Modality Prior-Induced Hallucinations in Multimodal Large Language Models via Deciphering Attention Causality

# 摘要

> 多模态大型语言模型 (MLLM) 在工业界和学术界备受瞩目，但常因视觉和语言先验引入的偏见而产生多模态幻觉。这些偏见源自视觉编码器和 LLM 骨干，影响多模态输入的对齐。现有缓解方法忽视了注意力机制与输出间的因果关系，效果有限。为此，我们提出 CausalMM 框架，通过结构因果建模，将模态先验视为混杂因素，采用后门调整和反事实推理，显著提升 MLLM 输入输出的对齐效果，最高得分提升 65.3%，MME 基准测试提升 164 分。实验证明其有效性，且即插即用。代码见：https://github.com/The-Martyr/CausalMM

> Multimodal Large Language Models (MLLMs) have emerged as a central focus in both industry and academia, but often suffer from biases introduced by visual and language priors, which can lead to multimodal hallucination. These biases arise from the visual encoder and the Large Language Model (LLM) backbone, affecting the attention mechanism responsible for aligning multimodal inputs. Existing decoding-based mitigation methods focus on statistical correlations and overlook the causal relationships between attention mechanisms and model output, limiting their effectiveness in addressing these biases. To tackle this issue, we propose a causal inference framework termed CausalMM that applies structural causal modeling to MLLMs, treating modality priors as a confounder between attention mechanisms and output. Specifically, by employing backdoor adjustment and counterfactual reasoning at both the visual and language attention levels, our method mitigates the negative effects of modality priors and enhances the alignment of MLLM's inputs and outputs, with a maximum score improvement of 65.3% on 6 VLind-Bench indicators and 164 points on MME Benchmark compared to conventional methods. Extensive experiments validate the effectiveness of our approach while being a plug-and-play solution. Our code is available at: https://github.com/The-Martyr/CausalMM

[Arxiv](https://arxiv.org/abs/2410.04780)