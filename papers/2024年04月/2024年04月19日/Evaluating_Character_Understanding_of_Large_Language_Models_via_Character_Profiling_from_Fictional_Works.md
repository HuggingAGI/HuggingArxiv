# 本研究通过分析虚构作品中的角色描述，来评估大型语言模型对角色认知的深度和准确性。

发布时间：2024年04月19日

`分类：Agent` `角色扮演代理` `虚构角色`

> Evaluating Character Understanding of Large Language Models via Character Profiling from Fictional Works

# 摘要

> 大型语言模型（LLMs）以其卓越的性能引领了众多AI应用的潮流，其中角色扮演代理（RPAs）尤其受到青睐，尤其是在虚构角色领域。RPAs的核心在于LLMs对虚构作品中角色的深刻理解。过去的研究尝试通过基础分类任务或特征模仿来评估LLMs的这种能力，但这并未充分捕捉到LLMs对角色细节的理解。本文提出了一种新的评估方法——通过角色剖析任务来衡量LLMs对角色的理解，即从相关材料中提炼角色档案，这一方法在RPAs的开发中被广泛采用，但研究尚不充分。我们特别构建了CroSS数据集，并通过对生成的角色档案与真实参考的比较以及它们在下游任务中的适用性来评估其效果。我们的实验覆盖了多种总结方法和LLMs，结果令人鼓舞，有力地证实了LLMs在角色理解上的能力。我们期待这一研究成果能够推动该领域的进一步探索。相关资源已在 https://github.com/Joanna0123/character_profiling 上线。

> Large language models (LLMs) have demonstrated impressive performance and spurred numerous AI applications, in which role-playing agents (RPAs) are particularly popular, especially for fictional characters. The prerequisite for these RPAs lies in the capability of LLMs to understand characters from fictional works. Previous efforts have evaluated this capability via basic classification tasks or characteristic imitation, failing to capture the nuanced character understanding with LLMs. In this paper, we propose evaluating LLMs' character understanding capability via the character profiling task, i.e., summarizing character profiles from corresponding materials, a widely adopted yet understudied practice for RPA development. Specifically, we construct the CroSS dataset from literature experts and assess the generated profiles by comparing ground truth references and their applicability in downstream tasks. Our experiments, which cover various summarization methods and LLMs, have yielded promising results. These results strongly validate the character understanding capability of LLMs. We believe our constructed resource will promote further research in this field. Resources are available at https://github.com/Joanna0123/character_profiling.

[Arxiv](https://arxiv.org/abs/2404.12726)