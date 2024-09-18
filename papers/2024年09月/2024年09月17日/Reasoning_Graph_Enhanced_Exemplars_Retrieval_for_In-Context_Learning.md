# 通过增强推理图进行示例检索，助力上下文学习

发布时间：2024年09月17日

`LLM应用` `人工智能`

> Reasoning Graph Enhanced Exemplars Retrieval for In-Context Learning

# 摘要

> 大型语言模型 (LLM) 通过 in-context learning (ICL) 技术，不仅展示了卓越的少样本学习能力，还统一了 NLP 任务的处理方式。然而，ICL 的成功很大程度上依赖于示例演示的质量。现有方法多聚焦于查询与示例间的语义相似性，却忽略了推理步骤间的逻辑联系。为此，我们提出了 Reasoning Graph-enhanced Exemplar Retrieval (RGER) 方法。RGER 首先让 LLM 生成初始响应，然后将问题解决步骤转化为图结构，再利用图核选择语义与结构双重相似的示例。实验证明，结构关系能有效提升查询与示例的匹配度。RGER 在数学与逻辑推理任务中的表现，显著超越了现有最先进的检索方法。代码已公开于 https://github.com/Yukang-Lin/RGER。

> Large language models(LLMs) have exhibited remarkable few-shot learning capabilities and unified the paradigm of NLP tasks through the in-context learning(ICL) technique. Despite the success of ICL, the quality of the exemplar demonstrations can significantly influence the LLM's performance. Existing exemplar selection methods mainly focus on the semantic similarity between queries and candidate exemplars. On the other hand, the logical connections between reasoning steps can be beneficial to depict the problem-solving process as well. In this paper, we proposes a novel method named Reasoning Graph-enhanced Exemplar Retrieval(RGER). RGER first quires LLM to generate an initial response, then expresses intermediate problem-solving steps to a graph structure. After that, it employs graph kernel to select exemplars with semantic and structural similarity. Extensive experiments demonstrate the structural relationship is helpful to the alignment of queries and candidate exemplars. The efficacy of RGER on math and logit reasoning tasks showcases its superiority over state-of-the-art retrieval-based approaches. Our code is released at https://github.com/Yukang-Lin/RGER.

[Arxiv](https://arxiv.org/abs/2409.11147)