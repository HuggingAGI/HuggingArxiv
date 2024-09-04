# Booster：通过减轻有害扰动，有效应对大型语言模型在微调过程中产生的不良影响。

发布时间：2024年09月02日

`LLM理论` `人工智能`

> Booster: Tackling Harmful Fine-tuing for Large Language Models via Attenuating Harmful Perturbation

# 摘要

> 有害微调问题对大型语言模型的微调服务构成了严重安全威胁。尽管已有防御措施被提出，但其效果仍不尽如人意，问题的根源也未彻底解决。本文首次揭示，模型权重上的有害扰动是破坏微调对齐的元凶。为此，我们创新性地提出了名为 Booster 的对齐阶段解决方案。技术上，我们在对齐优化中引入了一个损失正则化器，确保模型在遭受模拟有害扰动时，其有害损失减少得到有效控制，从而降低微调风险。实证结果表明，Booster 不仅能显著降低微调模型的有害分数，还能保持下游任务的性能。相关代码已公开在 \url{https://github.com/git-disl/Booster}。

> Harmful fine-tuning issue \citep{qi2023fine} poses serious safety concerns for Large language models' fine-tuning-as-a-service. While existing defenses \citep{huang2024vaccine,rosati2024representation} have been proposed to mitigate the issue, their performances are still far away from satisfactory, and the root cause of the problem has not been fully recovered. For the first time in the literature, we in this paper show that \textit{harmful perturbation} over the model weights should be the root cause of alignment-broken of harmful fine-tuning. In order to attenuate the negative impact of harmful perturbation, we propose an alignment-stage solution, dubbed Booster. Technically, along with the original alignment loss, we append a loss regularizer in the alignment stage's optimization. The regularizer ensures that the model's harmful loss reduction before/after simulated harmful perturbation is attenuated, thereby mitigating the subsequent fine-tuning risk. Empirical results show that Booster can effectively reduce the harmful score of the fine-tuned models while maintaining the performance of downstream tasks. Our code is available at \url{https://github.com/git-disl/Booster}.

[Arxiv](https://arxiv.org/abs/2409.01586)