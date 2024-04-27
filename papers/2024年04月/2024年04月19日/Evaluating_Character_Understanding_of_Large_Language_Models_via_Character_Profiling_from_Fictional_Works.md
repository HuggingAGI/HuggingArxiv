# 通过分析虚构作品中的角色描述，我们对大型语言模型在角色理解方面的洞察力进行了评估。

发布时间：2024年04月19日

`Agent` `AI应用` `角色扮演代理`

> Evaluating Character Understanding of Large Language Models via Character Profiling from Fictional Works

# 摘要

> 大型语言模型（LLMs）以其卓越的性能引领了众多AI应用的发展，其中角色扮演代理（RPAs）尤其受到青睐，尤其是在虚构角色的塑造上。RPAs的核心在于LLMs对虚构作品中角色的深刻理解。尽管以往的研究尝试通过基础分类或特征模仿任务来评估LLMs的这一能力，但这些方法并未能充分捕捉到LLMs对角色细节的理解。本文提出了一种新的评价方法——通过角色画像任务来衡量LLMs对角色的理解，即从相关资料中提炼出角色画像，这一方法在RPAs的发展中被广泛应用，却鲜有深入研究。我们特别构建了CroSS数据集，并通过对生成的角色画像与真实案例的比较，以及它们在下游任务中的适用性进行评估。我们的实验覆盖了多种总结技术和LLMs，结果令人鼓舞，有力地证实了LLMs在角色理解方面的能力。我们期望本研究能够推动该领域的进一步探索。相关资源可在 https://github.com/Joanna0123/character_profiling 查找。

> Large language models (LLMs) have demonstrated impressive performance and spurred numerous AI applications, in which role-playing agents (RPAs) are particularly popular, especially for fictional characters. The prerequisite for these RPAs lies in the capability of LLMs to understand characters from fictional works. Previous efforts have evaluated this capability via basic classification tasks or characteristic imitation, failing to capture the nuanced character understanding with LLMs. In this paper, we propose evaluating LLMs' character understanding capability via the character profiling task, i.e., summarizing character profiles from corresponding materials, a widely adopted yet understudied practice for RPA development. Specifically, we construct the CroSS dataset from literature experts and assess the generated profiles by comparing ground truth references and their applicability in downstream tasks. Our experiments, which cover various summarization methods and LLMs, have yielded promising results. These results strongly validate the character understanding capability of LLMs. We believe our constructed resource will promote further research in this field. Resources are available at https://github.com/Joanna0123/character_profiling.

[Arxiv](https://arxiv.org/abs/2404.12726)