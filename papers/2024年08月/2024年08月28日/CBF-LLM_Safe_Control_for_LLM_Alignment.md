# CBF-LLM：确保 LLM 对齐的安全控制方案

发布时间：2024年08月28日

`LLM应用` `人工智能`

> CBF-LLM: Safe Control for LLM Alignment

# 摘要

> 本文通过利用控制屏障函数（CBF），提出了一种新颖的框架，旨在确保大型语言模型（LLM）生成用户期望的文本。该框架通过应用基于CBF的安全过滤器，对基线LLM的令牌序列输出进行干预，以优化文本生成。实验结果显示，该系统结合了Llama 3和RoBERTa模型，有效减少了用户指定对齐任务所需的干预次数，展现了其卓越的控制能力。源代码已公开，供进一步研究与应用。

> This paper proposes a control-based framework for aligning large language models (LLMs) by leveraging a control barrier function (CBF) to ensure user-desirable text generation. The presented framework applies the safety filter, designed based on the CBF, to the output generation of the baseline LLM, i.e., the sequence of the token, with the aim of intervening in the generated text. The overall text-generation system is implemented with Llama 3 and a RoBERTa model, and the source code is available at https://github.com/Mya-Mya/CBF-LLM. The experiment demonstrates its control ability and effectiveness in reducing the number of interventions needed for user-specified alignment tasks.

[Arxiv](https://arxiv.org/abs/2408.15625)