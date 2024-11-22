# 区分 LLM 幻觉中的无知与错误

发布时间：2024年10月29日

`LLM应用` `问答系统`

> Distinguishing Ignorance from Error in LLM Hallucinations

# 摘要

> 大型语言模型（LLMs）容易出现幻觉，其输出要么毫无依据，要么事实错误，要么与之前的生成不一致。我们聚焦于闭卷问答（CBQA），此前的工作尚未充分厘清两种可能的幻觉之别，即模型（1）在其参数中未持有正确答案，还是（2）虽具备所需知识却回答错误。我们认为，区分这两种情形对于检测和缓解幻觉至关重要。具体来说，情形（2）可通过干预模型的内部计算来缓解，因为知识就在模型的参数里。相反，情形（1）没有可用于缓解的参数知识，所以应借助外部知识源或放弃作答来处理。为助力区分这两种情况，我们引入了“尽管拥有正确知识但回答错误（WACK）”这一方法，用于为第二种幻觉类型构建模型特定的数据集。我们的探测实验表明，这两种幻觉在模型的内部状态中呈现方式各异。接下来，我们展示使用 WACK 构建的数据集在不同模型间存在差异，这表明即便模型共享某些事实的知识，在导致幻觉的具体示例上仍有不同。最后，我们表明在我们的 WACK 数据集上训练探测器，相比使用常见的通用型一刀切数据集，能更出色地检测情形（2）的幻觉。代码可在 https://github.com/technion-cs-nlp/hallucination-mitigation 获取。

> Large language models (LLMs) are susceptible to hallucinations-outputs that are ungrounded, factually incorrect, or inconsistent with prior generations. We focus on close-book Question Answering (CBQA), where previous work has not fully addressed the distinction between two possible kinds of hallucinations, namely, whether the model (1) does not hold the correct answer in its parameters or (2) answers incorrectly despite having the required knowledge. We argue that distinguishing these cases is crucial for detecting and mitigating hallucinations. Specifically, case (2) may be mitigated by intervening in the model's internal computation, as the knowledge resides within the model's parameters. In contrast, in case (1) there is no parametric knowledge to leverage for mitigation, so it should be addressed by resorting to an external knowledge source or abstaining. To help distinguish between the two cases, we introduce Wrong Answer despite having Correct Knowledge (WACK), an approach for constructing model-specific datasets for the second hallucination type. Our probing experiments indicate that the two kinds of hallucinations are represented differently in the model's inner states. Next, we show that datasets constructed using WACK exhibit variations across models, demonstrating that even when models share knowledge of certain facts, they still vary in the specific examples that lead to hallucinations. Finally, we show that training a probe on our WACK datasets leads to better hallucination detection of case (2) hallucinations than using the common generic one-size-fits-all datasets. The code is available at https://github.com/technion-cs-nlp/hallucination-mitigation .

[Arxiv](https://arxiv.org/abs/2410.22071)