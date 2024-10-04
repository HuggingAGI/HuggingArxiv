# Llama SLayer 8B：浅层层级是知识注入的关键所在

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Llama SLayer 8B: Shallow Layers Hold the Key to Knowledge Injection

# 摘要

> 知识注入是增强预训练 LLM 的关键，尤其在垂直领域模型的开发中备受关注。然而，现有方法如 PEFT 和块扩展，均将知识均匀注入所有层，这引发了一个疑问：各层对知识注入的重要性是否相同？我们首先评估各层的重要性，发现浅层在知识注入中尤为关键。基于此，我们提出了 S 策略，即在预训练后选择性增强浅层，同时修剪深层。实验结果表明，该策略在代码和数学语料库上表现出色，并在不同 LLM 和法律语料库中验证了其广泛适用性。代码已公开，详见：\https://github.com/txchen-USTC/Llama-Slayer

> As a manner to augment pre-trained large language models (LLM), knowledge injection is critical to develop vertical domain large models and has been widely studied. Although most current approaches, including parameter-efficient fine-tuning (PEFT) and block expansion methods, uniformly apply knowledge across all LLM layers, it raises the question: are all layers equally crucial for knowledge injection? We begin by evaluating the importance of each layer in finding the optimal layer range for knowledge injection. Intuitively, the more important layers should play a more critical role in knowledge injection and deserve a denser injection. We observe performance dips in question-answering benchmarks after the removal or expansion of the shallow layers, and the degradation shrinks as the layer gets deeper, indicating that the shallow layers hold the key to knowledge injection. This insight leads us to propose the S strategy, a post-pretraining strategy of selectively enhancing shallow layers while pruning the less effective deep ones. Based on this strategy, we introduce Llama Slayer-8B and Llama Slayer-8B-Instruct. We experimented on the corpus of code $\&$ math and demonstrated the effectiveness of our strategy. Further experiments across different LLM, Mistral-7B, and a legal corpus confirmed the general applicability of the approach, underscoring its wide-ranging efficacy. Our code is available at: \https://github.com/txchen-USTC/Llama-Slayer

[Arxiv](https://arxiv.org/abs/2410.02330)