# 深入解析大型语言模型中的微调遗忘现象

发布时间：2024年10月09日

`LLM理论` `人工智能` `网络安全`

> Dissecting Fine-Tuning Unlearning in Large Language Models

# 摘要

> 尽管基于微调的遗忘方法在保护大型语言模型免受有害信息侵害方面表现出色，但其真正效果仍存疑。本文通过实验揭示，这些方法仅改变了知识检索方式，而非彻底清除问题知识。此外，遗忘机制还会波及模型其他功能。我们呼吁研发更有效的遗忘技术，并已将相关代码公开在 https://github.com/yihuaihong/Dissecting-FT-Unlearning。

> Fine-tuning-based unlearning methods prevail for preventing targeted harmful, sensitive, or copyrighted information within large language models while preserving overall capabilities. However, the true effectiveness of these methods is unclear. In this paper, we delve into the limitations of fine-tuning-based unlearning through activation patching and parameter restoration experiments. Our findings reveal that these methods alter the model's knowledge retrieval process, rather than genuinely erasing the problematic knowledge embedded in the model parameters. Furthermore, behavioral tests demonstrate that the unlearning mechanisms inevitably impact the global behavior of the models, affecting unrelated knowledge or capabilities. Our work advocates the development of more resilient unlearning techniques for truly erasing knowledge. Our code is released at https://github.com/yihuaihong/Dissecting-FT-Unlearning.

[Arxiv](https://arxiv.org/abs/2410.06606)