# SMART 技术能够自动缩减语言模型的规模，同时确保模型精度，从而有效降低处理成本。

发布时间：2024年03月11日

`LLM应用` `云计算`

> SMART: Automatically Scaling Down Language Models with Accuracy Guarantees for Reduced Processing Fees

# 摘要

> 随着LLMs的发展，NLP任务的表现有了显著跃升，但高性能LLMs的部署成本高昂，尤其是在追求更多参数以提升模型效能的情况下。这让普通用户使用顶尖LLMs的代价增大。尽管OpenAI、Anthropic等供应商提供了多款性能和价格各异的LLM版本，用户在选取性价比适中的LLM以完成特定任务时仍有困难。为此，我们创新提出SMART框架（智能适应性模型缩放以降低代币成本），该框架致力于在保证NLP任务结果质量的同时最大限度降低推理成本。SMART允许用户设定一个与最强LLM输出等效的精度要求，然后系统将确保生成结果的偏差概率低于用户预设阈值。SMART通过一个性能评估阶段，筛选出能满足用户所需精度等级的LLM集合，并在分析开销与预期节约成本之间取得最佳平衡。更进一步，我们采取策略性混合运用不同LLMs的方式，有效削减了推理成本。实验证明，在对三个实际数据集应用基于OpenAI模型的SMART后，相比GPT-4，成本最高可降低至原来的1/25.6。

> The advancement of Large Language Models (LLMs) has significantly boosted performance in natural language processing (NLP) tasks. However, the deployment of high-performance LLMs incurs substantial costs, primarily due to the increased number of parameters aimed at enhancing model performance. This has made the use of state-of-the-art LLMs more expensive for end-users. AI service providers, such as OpenAI and Anthropic, often offer multiple versions of LLMs with varying prices and performance. However, end-users still face challenges in choosing the appropriate LLM for their tasks that balance result quality with cost.
  We introduce SMART, Scaling Models Adaptively for Reduced Token Fees, a novel LLM framework designed to minimize the inference costs of NLP tasks while ensuring sufficient result quality. It enables users to specify an accuracy constraint in terms of the equivalence of outputs to those of the most powerful LLM. SMART then generates results that deviate from the outputs of this LLM only with a probability below a user-defined threshold. SMART employs a profiling phase that evaluates the performance of multiple LLMs to identify those that meet the user-defined accuracy level. SMART optimizes the tradeoff between profiling overheads and the anticipated cost savings resulting from profiling. Moreover, our approach significantly reduces inference costs by strategically leveraging a mix of LLMs. Our experiments on three real-world datasets show that, based on OpenAI models, SMART achieves significant cost savings, up to 25.6x in comparison to GPT-4.

[Arxiv](https://arxiv.org/abs/2403.13835)