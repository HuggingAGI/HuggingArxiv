# SimpleToM：揭示了 LLM 中显式 ToM 推理与隐式 ToM 应用之间的差异

发布时间：2024年10月17日

`LLM理论` `社交互动` `人工智能`

> SimpleToM: Exposing the Gap between Explicit ToM Inference and Implicit ToM Application in LLMs

# 摘要

> 尽管先前研究探讨了大型语言模型 (LLM) 是否具备“心智理论” (ToM)，即理解他人心理状态的能力，但很少有研究测试 LLM 能否隐含地应用这种知识来预测行为或判断行为是否合理。这些技能对于社交互动至关重要。我们创建了新数据集 SimpleTom，包含简洁多样的故事，每个故事附带三个问题，测试不同程度的 ToM 推理，如预测心理状态、行为和判断行为合理性。据我们所知，SimpleToM 是首个系统探索现实场景中心理状态知识对下游推理影响的数据集。实验结果显示，大多数模型能可靠预测心理状态，但常在预测行为和判断行为合理性上失败。尽管模型知晓主角心理状态，这些次要预测仍不明显。通过干预措施，如提醒模型早期心理状态答案和特定心理状态的思维链提示，我们能显著提升行为预测和判断的准确性。这表明模型可通过引导表现良好，但需任务特定干预，自然模型表现仍低，对 LLM 部署提出警示。

> While prior work has explored whether large language models (LLMs) possess a "theory of mind" (ToM) - the ability to attribute mental states to oneself and others - there has been little work testing whether LLMs can implicitly apply such knowledge to predict behavior, or to judge whether an observed behavior is rational. Such skills are critical for appropriate interaction in social environments. We create a new dataset, SimpleTom, containing concise, diverse stories (e.g., "The can of Pringles has moldy chips in it. Mary picks up the can in the supermarket and walks to the cashier."), each with three questions that test different degrees of ToM reasoning, asking models to predict (a) mental state ("Is Mary aware of the mold?"), (b) behavior ("Will Mary pay for the chips or report the mold?"), and (c) judgment ("Mary paid for the chips. Was that reasonable?"). To our knowledge, SimpleToM is the first dataset to systematically explore downstream reasoning requiring knowledge of mental states in realistic scenarios. Our experimental results are intriguing: While most models can reliably predict mental state on our dataset (a), they often fail to correctly predict the behavior (b), and fare even worse at judging whether given behaviors are reasonable (c), despite being correctly aware of the protagonist's mental state should make such secondary predictions obvious. We further show that we can help models do better at (b) and (c) via interventions such as reminding the model of its earlier mental state answer and mental-state-specific chain-of-thought prompting, raising the action prediction accuracies (e.g., from 49.5% to 93.5% for GPT-4o) and judgment accuracies (e.g., from 15.3% to 94.7% in GPT-4o). While this shows that models can be coaxed to perform well, it requires task-specific interventions, and the natural model performances remain low, a cautionary tale for LLM deployment.

[Arxiv](https://arxiv.org/abs/2410.13648)