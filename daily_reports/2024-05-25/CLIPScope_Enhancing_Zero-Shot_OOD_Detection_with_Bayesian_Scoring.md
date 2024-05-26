# CLIPScope：借助贝叶斯评分提升零-shot 异常检测能力
发布时间：2024年05月23日

`提示工程`
> CLIPScope: Enhancing Zero-Shot OOD Detection with Bayesian Scoring
>
> 确保机器学习模型在现实世界中的安全部署，检测分布外（OOD）样本至关重要。得益于视觉语言基础模型的最新进展，我们现在能够不依赖分布内（ID）图像来识别OOD样本。尽管如此，这些零-shot方法往往因未充分考虑ID类别的似然性而在检测准确性上有所欠缺。为此，我们推出了CLIPScope，一种创新的零-shot OOD检测技术，它通过类别似然性对置信度分数进行归一化，类似于贝叶斯后验更新，从而提升了检测的准确性。CLIPScope还独创性地从庞大的词汇数据库中挖掘OOD类别，通过选择与ID类别在CLIP嵌入距离上最远和最近的类别标签，确保了OOD样本的最大覆盖。经过详尽的消融研究和实证评估，CLIPScope在多个OOD检测基准上展现了卓越的性能。
>
> https://arxiv.org/abs/2405.14737


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14737](https://arxiv.org/abs/2405.14737)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886