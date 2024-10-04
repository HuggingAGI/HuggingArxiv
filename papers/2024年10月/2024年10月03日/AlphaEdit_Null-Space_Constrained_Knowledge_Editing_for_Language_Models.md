# AlphaEdit：一种专为语言模型设计的零空间约束知识编辑技术

发布时间：2024年10月03日

`LLM理论` `人工智能` `软件工程`

> AlphaEdit: Null-Space Constrained Knowledge Editing for Language Models

# 摘要

> 大型语言模型 (LLM) 常因知识错误或过时而产生幻觉，为此，模型编辑方法应运而生，以实现精准的知识更新。主流方法是先定位关键参数，再通过引入扰动进行编辑。然而，现有研究表明，这种扰动会破坏 LLM 中原本保留的知识，尤其是在多次编辑时。为解决这一问题，我们推出了 AlphaEdit，一种新颖的解决方案，它在应用扰动前，将其投影到保留知识的零空间中。理论证明，这种投影确保了在查询保留知识时，编辑后 LLM 的输出保持不变，从而有效缓解了破坏问题。实验表明，AlphaEdit 使多种定位-然后-编辑方法的性能平均提升了 36.4%，仅需添加一行额外代码即可实现。代码已开源，详见：https://github.com/jianghoucheng/AlphaEdit。

> Large language models (LLMs) often exhibit hallucinations due to incorrect or outdated knowledge. Hence, model editing methods have emerged to enable targeted knowledge updates. To achieve this, a prevailing paradigm is the locating-then-editing approach, which first locates influential parameters and then edits them by introducing a perturbation. While effective, current studies have demonstrated that this perturbation inevitably disrupt the originally preserved knowledge within LLMs, especially in sequential editing scenarios. To address this, we introduce AlphaEdit, a novel solution that projects perturbation onto the null space of the preserved knowledge before applying it to the parameters. We theoretically prove that this projection ensures the output of post-edited LLMs remains unchanged when queried about the preserved knowledge, thereby mitigating the issue of disruption. Extensive experiments on various LLMs, including LLaMA3, GPT2-XL, and GPT-J, show that AlphaEdit boosts the performance of most locating-then-editing methods by an average of 36.4% with a single line of additional code for projection solely. Our code is available at: https://github.com/jianghoucheng/AlphaEdit.

[Arxiv](https://arxiv.org/abs/2410.02355)