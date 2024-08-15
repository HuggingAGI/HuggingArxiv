# 知识叠加现象揭示了大型语言模型在终身知识编辑方面的不足。

发布时间：2024年08月14日

`LLM理论` `人工智能` `语言模型`

> Knowledge in Superposition: Unveiling the Failures of Lifelong Knowledge Editing for Large Language Models

# 摘要

> 知识编辑旨在更新大型语言模型中的过时或错误信息，但现有方法在终身编辑方面扩展性有限。本研究深入探讨了终身编辑失败的根本原因，从线性联想记忆的封闭形式解出发，扩展至终身编辑，并发现了一个干扰项，暗示编辑可能影响无关知识。进一步分析表明，干扰项与知识叠加紧密相关。当不存在知识叠加时，干扰消失，实现无损编辑。实验显示，知识叠加普遍存在，具有高峰度、零均值和重尾分布特征。结合理论与实验，我们证实知识叠加是终身编辑失败的关键。此外，本研究首次从叠加视角探讨知识编辑，并全面观察了现实世界语言模型中的叠加现象。代码已公开，详见 https://github.com/ChenhuiHu/knowledge_in_superposition。

> Knowledge editing aims to update outdated or incorrect knowledge in large language models (LLMs). However, current knowledge editing methods have limited scalability for lifelong editing. This study explores the fundamental reason why knowledge editing fails in lifelong editing. We begin with the closed-form solution derived from linear associative memory, which underpins state-of-the-art knowledge editing methods. We extend the solution from single editing to lifelong editing, and through rigorous mathematical derivation, identify an interference term in the final solution, suggesting that editing knowledge may impact irrelevant knowledge. Further analysis of the interference term reveals a close relationship with superposition between knowledge representations. When knowledge superposition does not exist in language models, the interference term vanishes, allowing for lossless knowledge editing. Experiments across numerous language models reveal that knowledge superposition is universal, exhibiting high kurtosis, zero mean, and heavy-tailed distributions with clear scaling laws. Ultimately, by combining theory and experiments, we demonstrate that knowledge superposition is the fundamental reason for the failure of lifelong editing. Moreover, this is the first study to investigate knowledge editing from the perspective of superposition and provides a comprehensive observation of superposition across numerous real-world language models. Code available at https://github.com/ChenhuiHu/knowledge_in_superposition.

[Arxiv](https://arxiv.org/abs/2408.07413)