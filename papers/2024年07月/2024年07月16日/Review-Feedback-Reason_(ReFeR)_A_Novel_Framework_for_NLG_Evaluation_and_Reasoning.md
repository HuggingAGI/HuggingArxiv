# ReFeR：一个创新的 NLG 评估与推理框架

发布时间：2024年07月16日

`LLM应用` `人工智能`

> Review-Feedback-Reason (ReFeR): A Novel Framework for NLG Evaluation and Reasoning

# 摘要

> 评估大型语言模型（LLM）生成的自然语言（NLG）输出的质量面临重大挑战。传统方法要么依赖资源密集型的人工评估，要么采用与人类判断相关性较低的自动指标。本研究提出了一种名为Review-Feedback-Reason（ReFeR）的新型评估框架，利用LLM代理进行NLG评估。通过在两个多样化的NLG任务基准数据集上严格测试，ReFeR不仅将评估准确性提高了约20％，还提供了建设性反馈，显著增强了集体推理能力。这些反馈进一步用于构建指令调优数据集，当应用于微调Mistral-7B等小型模型时，使其评估能力大幅提升，与人类评估的相关性更佳，性能接近GPT-3.5。在三个推理基准测试中，我们的方法表现卓越，超越了众多顶尖技术，平均推理能力分别比GPT-3.5 Turbo和GPT-4高出约11.67％和1％。

> Assessing the quality of Natural Language Generation (NLG) outputs, such as those produced by large language models (LLMs), poses significant challenges. Traditional approaches involve either resource-intensive human evaluations or automatic metrics, which often exhibit a low correlation with human judgment. In this study, we propose Review-Feedback-Reason (ReFeR), a novel evaluation framework for NLG using LLM agents. We rigorously test ReFeR using two pre-existing benchmark datasets on diverse NLG tasks. The proposed framework not only enhances the accuracy of NLG evaluation, surpassing previous benchmarks by $\sim$20\%, but also generates constructive feedback and significantly improves collective reasoning. This feedback is then leveraged for the creation of instruction-tuning datasets, which, when used to fine-tune smaller models like Mistral-7B, makes them extremely good evaluators, yielding a better correlation with human evaluations and performance nearly on par with GPT-3.5. We highlight the effectiveness of our methodology through its application on three reasoning benchmarks, where it outperforms most of the state-of-the-art methods, and also outperforms the reasoning capabilities of models like GPT-3.5 Turbo by $\sim$11.67\% and GPT-4 by $\sim$1\% on an average.

![ReFeR：一个创新的 NLG 评估与推理框架](../../../paper_images/2407.12877/x1.png)

![ReFeR：一个创新的 NLG 评估与推理框架](../../../paper_images/2407.12877/x2.png)

![ReFeR：一个创新的 NLG 评估与推理框架](../../../paper_images/2407.12877/x3.png)

[Arxiv](https://arxiv.org/abs/2407.12877)