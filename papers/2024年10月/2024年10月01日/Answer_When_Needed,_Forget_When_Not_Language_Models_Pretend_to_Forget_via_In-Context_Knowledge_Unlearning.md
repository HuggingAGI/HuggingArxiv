# 语言模型能够“按需遗忘”：在需要时提供答案，在不需要时通过上下文知识遗忘来假装遗忘。

发布时间：2024年10月01日

`LLM应用` `人工智能` `信息安全`

> Answer When Needed, Forget When Not: Language Models Pretend to Forget via In-Context Knowledge Unlearning

# 摘要

> 随着 LLM 在各领域的广泛应用，选择性遗忘特定信息的能力变得至关重要。例如，LLM 需向内部授权用户提供机密信息，同时对外部用户保密。为此，我们提出“上下文知识遗忘”方法，使模型在测试时根据查询上下文选择性遗忘信息。实验表明，该方法在遗忘准确率上高达 95%，同时保留 80% 不相关知识，显著优于基线。深入研究发现，微调后的 LLM 在最后一层做出遗忘决定，即“LLM 假装遗忘”。这一发现为提升 LLM 遗忘机制的鲁棒性提供了新思路，为未来研究奠定基础。

> As large language models (LLMs) are applied across diverse domains, the ability to selectively unlearn specific information has become increasingly essential. For instance, LLMs are expected to provide confidential information to authorized internal users, such as employees or trusted partners, while withholding it from external users, including the general public and unauthorized entities. In response to this challenge, we propose a novel method termed ``in-context knowledge unlearning'', which enables the model to selectively forget information in test-time based on the context of the query. Our method fine-tunes pre-trained LLMs to enable prompt unlearning of target knowledge within the context, while preserving other knowledge. Experiments on the TOFU and AGE datasets using Llama2-7B/13B and Mistral-7B models show our method achieves up to 95% forgetting accuracy while retaining 80% of unrelated knowledge, significantly outperforming baselines in both in-domain and out-of-domain scenarios. Further investigation into the model's internal behavior revealed that while fine-tuned LLMs generate correct predictions in the middle layers and maintain them up to the final layer, they make the decision to forget at the last layer, i.e., ``LLMs pretend to forget''. Our findings offer valuable insights into enhancing the robustness of unlearning mechanisms in LLMs, setting a foundation for future research in the field.

[Arxiv](https://arxiv.org/abs/2410.00382)