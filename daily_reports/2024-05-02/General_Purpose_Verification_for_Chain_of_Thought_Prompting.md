![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 针对思维链提示的通用验证方法
发布时间：2024年04月30日

`提示工程`
> 大型语言模型（LLMs）近期展现的众多能力，很大程度上得益于其对上下文信息的高效利用。本文旨在探讨如何通过探索多样化的思维路径和对推理过程中的各个环节进行验证，来提升LLMs的推理能力。我们提出了三个推理时应遵循的原则：（一）相关性，（二）数学精确性，以及（三）逻辑连贯性。这些原则被转化为对LLM生成的推理步骤的约束，以提高最终结果的准确性。模型需自我验证生成的步骤是否符合这些约束。此外，我们还引入了推理步骤的困惑度作为额外的验证标准，以引导模型朝着更高质量的解决方案发展。我们的方法在四种不同类别的推理任务上进行了测试，涵盖了九个不同的数据集。实验结果表明，我们的方法在所有情况下均优于传统生成方法，在九个数据集中的六个上，其表现也超过了N最佳采样方法，后者通过采样N条推理链并选择困惑度最低的生成结果。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CoT_Fig1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CoT_fig2_hr.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/GSM8k_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/BigBenchDate_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/GSM8k_sc_sp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA_sc_sp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/BigBenchDate_sc_sp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/overall_correlation3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/BigBenchDate_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA2.0_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/Strategy_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/Coinflip_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/LastLetter2_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/GSM8k_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/SVAMP_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/AddSub_sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/BigBenchDate_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA2.0_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/Strategy_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/Coinflip_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/LastLetter2_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/GSM8k_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/SVAMP_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/AddSub_sc_src.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/GSM8k_sc_sa.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/CSQA_sc_sa.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/BigBenchDate_sc_sa.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/interannotator_agreement-relevance_score.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/interannotator_agreement-mathematical_accuracy_score.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/interannotator_agreement-logical_consistency_score.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/interannotator_agreement-everything_fine.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/correlation-everything_fine_aggregated_verifiers.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/correlation-everything_fine_aggregated_verifiers_and_ppl.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/correlation-logical_consistency.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/correlation-mathematical_accuracy.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/correlation-relevance.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00204/overall_correlation.png)


- 论文原文: [https://arxiv.org/abs/2405.00204](https://arxiv.org/abs/2405.00204)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)