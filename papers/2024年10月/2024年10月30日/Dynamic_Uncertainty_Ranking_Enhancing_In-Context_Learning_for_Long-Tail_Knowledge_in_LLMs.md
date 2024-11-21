# 动态不确定性排名：提升大型语言模型中长尾知识的上下文学习能力

发布时间：2024年10月30日

`LLM应用` `问答系统`

> Dynamic Uncertainty Ranking: Enhancing In-Context Learning for Long-Tail Knowledge in LLMs

# 摘要

> 大型语言模型（LLMs）在预训练时能从多个领域学到海量知识。但专业领域的长尾知识往往稀缺且占比少，在模型的记忆里很少出现。此前的研究显示，带有检索器增强的上下文学习（ICL）能助力 LLMs 更好地获取长尾知识，降低对预训练数据的依赖。即便有这些进步，我们发现 LLM 对长尾问题的预测仍会因检索样本的变化而不确定。为利用 ICL 中的不确定性，引导 LLM 对长尾样本的预测走向正确答案，我们提出一种基于强化学习的 ICL 动态不确定性排序法，它考虑了每个检索样本对 LLM 预测的不同影响。我们的方法优先选择更具信息量和稳定性的样本，降低误导性样本的优先级，并依据 LLM 对每个检索样本的反馈更新排名。为提升训练效率、降低查询成本，我们引入了一个可学习的动态排名阈值，当模型遭遇负面预测变化时进行调整。在不同领域的各种问答数据集上的实验结果表明，我们的方法比最优基线高出 2.76%，在零样本推理难以解决的长尾问题上，准确率大幅提升 5.96%。

> Large language models (LLMs) can learn vast amounts of knowledge from diverse domains during pre-training. However, long-tail knowledge from specialized domains is often scarce and underrepresented, rarely appearing in the models' memorization. Prior work has shown that in-context learning (ICL) with retriever augmentation can help LLMs better capture long-tail knowledge, reducing their reliance on pre-trained data. Despite these advances, we observe that LLM predictions for long-tail questions remain uncertain to variations in retrieved samples. To take advantage of the uncertainty in ICL for guiding LLM predictions toward correct answers on long-tail samples, we propose a reinforcement learning-based dynamic uncertainty ranking method for ICL that accounts for the varying impact of each retrieved sample on LLM predictions. Our approach prioritizes more informative and stable samples while demoting misleading ones, updating rankings based on the feedback from the LLM w.r.t. each retrieved sample. To enhance training efficiency and reduce query costs, we introduce a learnable dynamic ranking threshold, adjusted when the model encounters negative prediction shifts. Experimental results on various question-answering datasets from different domains show that our method outperforms the best baseline by $2.76\%$, with a notable $5.96\%$ boost in accuracy on long-tail questions that elude zero-shot inference.

[Arxiv](https://arxiv.org/abs/2410.23605)