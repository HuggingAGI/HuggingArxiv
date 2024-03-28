# 现今的主流70亿参数语言模型普遍展现出强劲的数学处理能力。

发布时间：2024年03月07日

`LLM应用`

> Common 7B Language Models Already Possess Strong Math Capabilities

# 摘要

> 过去普遍认为，数学能力要在大型或专精于数学预训练的语言模型中才能崭露头角。但本研究揭示，经过常规预训练的 LLaMA-2 7B 模型已具备出色的数学技能，其在 GSM8K 和 MATH 两大基准测试中，从256个随机生成的答案中选出最优解的准确率分别高达 97.7% 和 72.0%。目前的问题在于，如何稳定挖掘出该基础模型内在的数学潜能，尤其是在 GSM8K 和 MATH 测试中，首条答案的准确率陡降为 49.5% 和 7.9%。研究进一步表明，适度增加 SFT 数据量能有效提升模型生成正确答案的稳定性，然而，受限于公开数学题目的稀缺，大规模扩展面临着挑战。为突破这一瓶颈，我们采用合成数据，并证实它几乎与真实数据同样有效，即便扩增至约百万级别的样本量，效果仍未见饱和。运用这一简便策略后，LLaMA-2 7B 模型在 GSM8K 测试上的准确率达到了 82.6%，在 MATH 测试上也达到了 40.6%，分别较之前模型提升了 14.2% 和 20.8%。同时，我们还深入探讨了模型在不同推理难度和各类错误类型下的扩展特性。

> Mathematical capabilities were previously believed to emerge in common language models only at a very large scale or require extensive math-related pre-training. This paper shows that the LLaMA-2 7B model with common pre-training already exhibits strong mathematical abilities, as evidenced by its impressive accuracy of 97.7% and 72.0% on the GSM8K and MATH benchmarks, respectively, when selecting the best response from 256 random generations. The primary issue with the current base model is the difficulty in consistently eliciting its inherent mathematical capabilities. Notably, the accuracy for the first answer drops to 49.5% and 7.9% on the GSM8K and MATH benchmarks, respectively. We find that simply scaling up the SFT data can significantly enhance the reliability of generating correct answers. However, the potential for extensive scaling is constrained by the scarcity of publicly available math questions. To overcome this limitation, we employ synthetic data, which proves to be nearly as effective as real data and shows no clear saturation when scaled up to approximately one million samples. This straightforward approach achieves an accuracy of 82.6% on GSM8K and 40.6% on MATH using LLaMA-2 7B models, surpassing previous models by 14.2% and 20.8%, respectively. We also provide insights into scaling behaviors across different reasoning complexities and error types.

[Arxiv](https://arxiv.org/abs/2403.04706)