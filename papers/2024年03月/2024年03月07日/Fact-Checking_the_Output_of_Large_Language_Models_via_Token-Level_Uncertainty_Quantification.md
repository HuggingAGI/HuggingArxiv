# 针对大型语言模型的输出，我们采用Token级别不确定性量化方法进行深度事实核查。

发布时间：2024年03月07日

`LLM应用`

> Fact-Checking the Output of Large Language Models via Token-Level Uncertainty Quantification

# 摘要

> 大型语言模型（LLMs）时常会出现令人担忧的问题——输出中会“臆想”出错误的声明，这类错误由于混杂在大量真实信息中，往往难以被察觉，给用户带来潜在风险。目前依赖LLMs的服务大多未提供检测生成内容可靠性的方式。为此，我们致力于解决这一问题，创新性地提出了一个基于令牌级不确定性量化的事实核查与虚假信息甄别流程。通过挖掘神经网络输出及其内部各层蕴含的信息，利用不确定性得分识别出不可靠的预测，并证实了这一方法能有效应用于对LLM输出中基本事实声明的真实性验证。此外，我们还独创了一种消除生成特定声明及选用何种表述形式不确定性影响的令牌级不确定性量化方法——“条件概率声明”（CCP），它专注于度量模型表达特定声明内容的不确定性程度。实验证明，在涵盖六种不同的LLMs和三种语言的传记生成任务上，CCP相较于基准方法表现出强劲的提升效果。同时，经过人工评估，基于不确定性量化的事实核查流程与那些利用外部知识库的事实核查工具同样具有竞争力。

> Large language models (LLMs) are notorious for hallucinating, i.e., producing erroneous claims in their output. Such hallucinations can be dangerous, as occasional factual inaccuracies in the generated text might be obscured by the rest of the output being generally factual, making it extremely hard for the users to spot them. Current services that leverage LLMs usually do not provide any means for detecting unreliable generations. Here, we aim to bridge this gap. In particular, we propose a novel fact-checking and hallucination detection pipeline based on token-level uncertainty quantification. Uncertainty scores leverage information encapsulated in the output of a neural network or its layers to detect unreliable predictions, and we show that they can be used to fact-check the atomic claims in the LLM output. Moreover, we present a novel token-level uncertainty quantification method that removes the impact of uncertainty about what claim to generate on the current step and what surface form to use. Our method Claim Conditioned Probability (CCP) measures only the uncertainty of particular claim value expressed by the model. Experiments on the task of biography generation demonstrate strong improvements for CCP compared to the baselines for six different LLMs and three languages. Human evaluation reveals that the fact-checking pipeline based on uncertainty quantification is competitive with a fact-checking tool that leverages external knowledge.

[Arxiv](https://arxiv.org/abs/2403.04696)