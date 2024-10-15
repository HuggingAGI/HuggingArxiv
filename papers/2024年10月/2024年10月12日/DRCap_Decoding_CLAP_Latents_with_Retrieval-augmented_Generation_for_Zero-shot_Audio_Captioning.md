# DRCap：通过检索增强生成技术，解码 CLAP 潜在变量，实现零-shot 音频字幕生成。

发布时间：2024年10月12日

`LLM应用` `音频处理` `人工智能`

> DRCap: Decoding CLAP Latents with Retrieval-augmented Generation for Zero-shot Audio Captioning

# 摘要

> 尽管自动音频字幕（AAC）取得了显著进展，但传统的全监督AAC模型仍面临两个关键挑战：需要昂贵的音频-文本对数据进行训练，以及在跨域转移时性能下降。为了克服这些限制，我们提出了DRCap，这是一个数据高效且灵活的零样本音频字幕系统，仅需要文本数据进行训练，并且可以快速适应新领域而无需额外微调。DRCap集成了对比语言-音频预训练（CLAP）模型和大型语言模型（LLM）作为其骨干。在训练期间，模型使用CLAP中的固定文本编码器预测真实字幕，而在推理期间，文本编码器被音频编码器替换，以零样本方式生成音频片段的字幕。为了缓解CLAP模型的模态差距，我们同时使用了编码器侧的投影策略和解码器侧的检索增强生成策略。具体来说，音频嵌入首先被投影到文本嵌入支持上，以吸收CLAP联合多模态空间中的广泛语义信息。同时，从数据存储中检索到的相似字幕作为提示输入到LLM中，结合外部知识充分利用其强大的生成能力。在投影的CLAP嵌入和检索到的相似字幕的条件下，模型能够生成更准确且语义丰富的文本描述。通过针对目标领域定制文本嵌入支持和字幕数据存储，DRCap获得了无需训练即可适应新领域的强大能力。实验结果表明，DRCap在域内场景中优于所有其他零样本模型，并在跨域场景中达到了最先进的性能。

> While automated audio captioning (AAC) has made notable progress, traditional fully supervised AAC models still face two critical challenges: the need for expensive audio-text pair data for training and performance degradation when transferring across domains. To overcome these limitations, we present DRCap, a data-efficient and flexible zero-shot audio captioning system that requires text-only data for training and can quickly adapt to new domains without additional fine-tuning. DRCap integrates a contrastive language-audio pre-training (CLAP) model and a large-language model (LLM) as its backbone. During training, the model predicts the ground-truth caption with a fixed text encoder from CLAP, whereas, during inference, the text encoder is replaced with the audio encoder to generate captions for audio clips in a zero-shot manner. To mitigate the modality gap of the CLAP model, we use both the projection strategy from the encoder side and the retrieval-augmented generation strategy from the decoder side. Specifically, audio embeddings are first projected onto a text embedding support to absorb extensive semantic information within the joint multi-modal space of CLAP. At the same time, similar captions retrieved from a datastore are fed as prompts to instruct the LLM, incorporating external knowledge to take full advantage of its strong generative capability. Conditioned on both the projected CLAP embedding and the retrieved similar captions, the model is able to produce a more accurate and semantically rich textual description. By tailoring the text embedding support and the caption datastore to the target domain, DRCap acquires a robust ability to adapt to new domains in a training-free manner. Experimental results demonstrate that DRCap outperforms all other zero-shot models in in-domain scenarios and achieves state-of-the-art performance in cross-domain scenarios.

[Arxiv](https://arxiv.org/abs/2410.09472)