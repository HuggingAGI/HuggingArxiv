# 通过检索增强的自然语言推理，实现视觉问答的可解释性

发布时间：2024年08月30日

`LLM应用` `计算机视觉`

> Retrieval-Augmented Natural Language Reasoning for Explainable Visual Question Answering

# 摘要

> VQA-NLE任务因其对推理能力的高要求而颇具挑战。近期研究虽致力于提升模型推理力，但成本高且稳定性不足。为此，我们推出了ReRe模型，通过利用记忆检索信息，无需复杂网络或额外数据集，便能产出精准答案与有力解释。ReRe采用编码器-解码器架构，结合预训练视觉编码器与GPT-2语言模型，并增设交叉注意力层处理检索特征。实测表明，ReRe在VQA准确度与解释质量上均超越以往，NLE表现更见说服力与可靠性。

> Visual Question Answering with Natural Language Explanation (VQA-NLE) task is challenging due to its high demand for reasoning-based inference. Recent VQA-NLE studies focus on enhancing model networks to amplify the model's reasoning capability but this approach is resource-consuming and unstable. In this work, we introduce a new VQA-NLE model, ReRe (Retrieval-augmented natural language Reasoning), using leverage retrieval information from the memory to aid in generating accurate answers and persuasive explanations without relying on complex networks and extra datasets. ReRe is an encoder-decoder architecture model using a pre-trained clip vision encoder and a pre-trained GPT-2 language model as a decoder. Cross-attention layers are added in the GPT-2 for processing retrieval features. ReRe outperforms previous methods in VQA accuracy and explanation score and shows improvement in NLE with more persuasive, reliability.

[Arxiv](https://arxiv.org/abs/2408.17006)