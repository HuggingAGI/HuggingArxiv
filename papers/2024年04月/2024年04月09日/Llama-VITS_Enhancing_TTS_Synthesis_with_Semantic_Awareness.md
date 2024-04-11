# Llama-VITS：借助语义理解提升TTS语音合成效果

发布时间：2024年04月09日

`LLM应用` `语音合成`

> Llama-VITS: Enhancing TTS Synthesis with Semantic Awareness

# 摘要

> 自然语言处理（NLP）的最新进展让大型语言模型（LLMs）在生成各类高质量文本方面大放异彩。尤其是在文本转语音（TTS）系统方面，BERT在语义标记生成的融合运用，凸显了语义内容对于流畅语音输出的关键作用。然而，LLMs在提升TTS合成方面的潜力尚未充分挖掘。本研究提出了一种创新方案——Llama-VITS，该方案通过LLM增强文本的语义内容，从而提升TTS合成的质量。Llama-VITS结合了Llama2的语义嵌入和业界领先的端到端TTS框架VITS。利用Llama2主导语音合成过程，实验结果显示，Llama-VITS在LJSpeech数据集上的表现与原始VITS（ORI-VITS）和融合BERT的VITS（BERT-VITS）不相上下，该数据集收录了大量清晰、中立的语音样本。此外，我们的方法在EmoV_DB_bea_sem数据集上显著提升了情感表达力，该数据集精心挑选了情感连贯的语音样本，展现了Llama-VITS在生成富有情感的语音方面的巨大潜力。

> Recent advancements in Natural Language Processing (NLP) have seen Large-scale Language Models (LLMs) excel at producing high-quality text for various purposes. Notably, in Text-To-Speech (TTS) systems, the integration of BERT for semantic token generation has underscored the importance of semantic content in producing coherent speech outputs. Despite this, the specific utility of LLMs in enhancing TTS synthesis remains considerably limited. This research introduces an innovative approach, Llama-VITS, which enhances TTS synthesis by enriching the semantic content of text using LLM. Llama-VITS integrates semantic embeddings from Llama2 with the VITS model, a leading end-to-end TTS framework. By leveraging Llama2 for the primary speech synthesis process, our experiments demonstrate that Llama-VITS matches the naturalness of the original VITS (ORI-VITS) and those incorporate BERT (BERT-VITS), on the LJSpeech dataset, a substantial collection of neutral, clear speech. Moreover, our method significantly enhances emotive expressiveness on the EmoV_DB_bea_sem dataset, a curated selection of emotionally consistent speech from the EmoV_DB dataset, highlighting its potential to generate emotive speech.

![Llama-VITS：借助语义理解提升TTS语音合成效果](../../../paper_images/2404.06714/x1.png)

![Llama-VITS：借助语义理解提升TTS语音合成效果](../../../paper_images/2404.06714/x2.png)

![Llama-VITS：借助语义理解提升TTS语音合成效果](../../../paper_images/2404.06714/x3.png)

[Arxiv](https://arxiv.org/abs/2404.06714)