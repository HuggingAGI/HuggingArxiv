# 语音翻译中的语言扩展任务算术

发布时间：2024年09月17日

`LLM应用` `语音识别` `机器翻译`

> Task Arithmetic for Language Expansion in Speech Translation

# 摘要

> 大型语言模型 (LLM) 的最新进展激发了对语音-文本多模态模型的研究，这些模型在基于指令的语音翻译 (ST) 任务中表现出色。然而，扩展现有 ST 系统的语言对需要在新旧数据集上重新训练，成本高昂。我们提出通过任务算术将新语言模型与现有模型合并，以实现语言对的扩展。但直接应用任务算术会导致模型生成错误语言的翻译。为此，我们引入了一种增强的任务算术方法，结合了一个语言控制模型，确保生成正确的目标语言。实验结果显示，该方法在 MuST-C 和 CoVoST-2 数据集上分别提升了 4.66 和 4.92 BLEU 分数。此外，我们的框架还能在没有配对 ST 数据或预训练 ST 模型的情况下，扩展到新的语言对，通过任务类比从 MT 系统合成 ST 系统，再进行模型合并。

> Recent advances in large language models (LLMs) have gained interest in speech-text multimodal foundation models, achieving strong performance on instruction-based speech translation (ST). However, expanding language pairs from an existing instruction-tuned ST system is costly due to the necessity of re-training on a combination of new and previous datasets. We propose to expand new language pairs by merging the model trained on new language pairs and the existing model, using task arithmetic. We find that the direct application of task arithmetic for ST causes the merged model to fail to follow instructions; thus, generating translation in incorrect languages. To eliminate language confusion, we propose an augmented task arithmetic method that merges an additional language control model. It is trained to generate the correct target language token following the instructions. Our experiments demonstrate that our proposed language control model can achieve language expansion by eliminating language confusion. In our MuST-C and CoVoST-2 experiments, it shows up to 4.66 and 4.92 BLEU scores improvement, respectively. In addition, we demonstrate the use of our task arithmetic framework can expand to a language pair where neither paired ST training data nor a pre-trained ST model is available. We first synthesize the ST system from machine translation (MT) systems via task analogy, then merge the synthesized ST system to the existing ST model.

[Arxiv](https://arxiv.org/abs/2409.11274)