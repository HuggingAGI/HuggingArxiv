# 借助 LLM 的迭代自修订，提升复杂事实核查的真实性与解释力

发布时间：2024年10月19日

`LLM应用`

> Augmenting the Veracity and Explanations of Complex Fact Checking via Iterative Self-Revision with LLMs

# 摘要

> 解释生成在提升结果可解释性和促进全面事实核查方面，比事实验证更为关键，近期备受瞩目。然而，以往研究在解释生成上存在局限，如仅限于英语环境、推理过程复杂，且未能充分挖掘真实性标签与解释文本间的相互反馈潜力。为此，我们构建了两个中文复杂事实核查数据集：CHEF-EG 和 TrendFact，涵盖健康、政治、社会等领域，对事实验证方法构成挑战。针对这些挑战，我们提出统一框架 FactISR，通过迭代自修订机制，利用大型语言模型（LLM）实现真实性与解释间的相互反馈。FactISR 以单一模型处理事实验证与解释生成，其自修订机制能优化真实性标签、解释文本与证据间的一致性，并剔除无关噪声。实验结果显示，FactISR 在提升事实核查效果上表现出色。

> Explanation generation plays a more pivotal role than fact verification in producing interpretable results and facilitating comprehensive fact-checking, which has recently garnered considerable attention. However, previous studies on explanation generation has shown several limitations, such as being confined to English scenarios, involving overly complex inference processes, and not fully unleashing the potential of the mutual feedback between veracity labels and explanation texts. To address these issues, we construct two complex fact-checking datasets in the Chinese scenarios: CHEF-EG and TrendFact. These datasets involve complex facts in areas such as health, politics, and society, presenting significant challenges for fact verification methods. In response to these challenges, we propose a unified framework called FactISR (Augmenting Fact-Checking via Iterative Self-Revision) to perform mutual feedback between veracity and explanations by leveraging the capabilities of large language models(LLMs). FactISR uses a single model to address tasks such as fact verification and explanation generation. Its self-revision mechanism can further revision the consistency between veracity labels, explanation texts, and evidence, as well as eliminate irrelevant noise. We conducted extensive experiments with baselines and FactISR on the proposed datasets. The experimental results demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.15135)