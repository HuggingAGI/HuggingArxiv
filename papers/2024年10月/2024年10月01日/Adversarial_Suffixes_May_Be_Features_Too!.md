# 对抗性后缀，或许也是特征之一！

发布时间：2024年10月01日

`LLM理论` `网络安全` `人工智能`

> Adversarial Suffixes May Be Features Too!

# 摘要

> 尽管在安全对齐方面投入了大量努力，GPT-4 和 LLaMA 3 等大型语言模型仍易受 jailbreak 攻击，这些攻击能诱导有害行为，包括由对抗性后缀触发的行为。我们假设这些后缀不仅是漏洞，还可能是主导 LLM 行为的特征。为此，我们进行了多项实验。首先，我们展示了良性特征如何被转化为对抗性后缀，从而破坏安全对齐。其次，我们发现 jailbreak 攻击生成的后缀包含特定特征，这些特征在不同提示下产生一致的响应。最后，我们证明即使在没有有害内容的情况下，通过微调良性数据集也能引入这些特征。这凸显了训练数据中良性特征的风险，并呼吁加强 LLM 安全对齐的研究。我们的代码和数据可在 \url{https://github.com/anonymous} 获取。

> Despite significant ongoing efforts in safety alignment, large language models (LLMs) such as GPT-4 and LLaMA 3 remain vulnerable to jailbreak attacks that can induce harmful behaviors, including those triggered by adversarial suffixes. Building on prior research, we hypothesize that these adversarial suffixes are not mere bugs but may represent features that can dominate the LLM's behavior. To evaluate this hypothesis, we conduct several experiments. First, we demonstrate that benign features can be effectively made to function as adversarial suffixes, i.e., we develop a feature extraction method to extract sample-agnostic features from benign dataset in the form of suffixes and show that these suffixes may effectively compromise safety alignment. Second, we show that adversarial suffixes generated from jailbreak attacks may contain meaningful features, i.e., appending the same suffix to different prompts results in responses exhibiting specific characteristics. Third, we show that such benign-yet-safety-compromising features can be easily introduced through fine-tuning using only benign datasets, i.e., even in the absence of harmful content. This highlights the critical risk posed by dominating benign features in the training data and calls for further research to reinforce LLM safety alignment. Our code and data is available at \url{https://github.com/anonymous}.

[Arxiv](https://arxiv.org/abs/2410.00451)