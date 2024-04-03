# 等等，难道这一切仅仅是标记噪声？从始至终都是如此：通过 Shapley 值来解读大型语言模型（LLM）的行为特征。

发布时间：2024年03月29日

`LLM应用` `市场营销` `消费者行为分析`

> Wait, It's All Token Noise? Always Has Been: Interpreting LLM Behavior Using Shapley Value

# 摘要

> 大型语言模型（LLMs）的问世，为模拟人类行为和认知过程开辟了无限可能，其在市场研究、消费者行为分析等多个领域的应用前景广阔。然而，鉴于LLMs与人类受试者之间存在显著差异，以及LLM对提示变化的高度敏感性，其作为人类替代品的可靠性尚未得到充分验证。本研究提出了一种创新方法，借鉴合作博弈论中的Shapley值，以解读LLM的行为模式，并衡量每个提示元素对输出结果的具体贡献。通过两项实验——一项离散选择实验和一项认知偏见研究——我们展示了如何运用Shapley值方法揭示“标记噪声”效应，即LLM的决策在很大程度上受到那些信息量极低的标记的影响。这一发现对于依赖LLMs模拟人类行为所得见解的稳健性和普适性提出了挑战。我们的方法不受特定模型限制，适用于各种专有LLMs，为营销人员和研究者提供了战略性优化提示和减少认知偏见的有效工具。我们的研究结果提醒我们，在将LLMs作为人类受试者的替代品之前，必须更深入地理解影响其响应的各种因素。同时，我们敦促研究者在报告结果时明确提示模板的具体条件，并在将人类行为与LLMs进行比较时保持审慎。

> The emergence of large language models (LLMs) has opened up exciting possibilities for simulating human behavior and cognitive processes, with potential applications in various domains, including marketing research and consumer behavior analysis. However, the validity of utilizing LLMs as stand-ins for human subjects remains uncertain due to glaring divergences that suggest fundamentally different underlying processes at play and the sensitivity of LLM responses to prompt variations. This paper presents a novel approach based on Shapley values from cooperative game theory to interpret LLM behavior and quantify the relative contribution of each prompt component to the model's output. Through two applications-a discrete choice experiment and an investigation of cognitive biases-we demonstrate how the Shapley value method can uncover what we term "token noise" effects, a phenomenon where LLM decisions are disproportionately influenced by tokens providing minimal informative content. This phenomenon raises concerns about the robustness and generalizability of insights obtained from LLMs in the context of human behavior simulation. Our model-agnostic approach extends its utility to proprietary LLMs, providing a valuable tool for marketers and researchers to strategically optimize prompts and mitigate apparent cognitive biases. Our findings underscore the need for a more nuanced understanding of the factors driving LLM responses before relying on them as substitutes for human subjects in research settings. We emphasize the importance of researchers reporting results conditioned on specific prompt templates and exercising caution when drawing parallels between human behavior and LLMs.

[Arxiv](https://arxiv.org/abs/2404.01332)