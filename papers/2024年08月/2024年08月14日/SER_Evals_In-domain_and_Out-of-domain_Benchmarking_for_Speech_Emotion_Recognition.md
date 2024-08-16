# 语音情感识别（SER）评估：涵盖域内与域外的基准测试

发布时间：2024年08月14日

`LLM应用` `语音识别` `情感分析`

> SER Evals: In-domain and Out-of-domain Benchmarking for Speech Emotion Recognition

# 摘要

> 随着自监督学习模型的兴起，语音情感识别技术取得了长足进步。然而，这些模型在跨语言和情感表达的泛化方面仍面临挑战。为此，我们设计了一个大规模基准测试，旨在全面评估最先进 SER 模型在不同场景下的鲁棒性与适应性。该基准涵盖了多样化的多语言数据集，特别关注那些使用较少的语料库，以检验模型对新数据的适应能力。通过采用对数调整策略来平衡类别分布，我们构建了一个统一的数据集集群进行系统性评估。令人意外的是，专为自动语音识别设计的 Whisper 模型在跨语言情感识别任务中表现出色，超越了专门的 SSL 模型。这一发现凸显了开发更强大、更通用 SER 模型的必要性，而我们的基准测试将成为推动该领域未来研究的重要资源。

> Speech emotion recognition (SER) has made significant strides with the advent of powerful self-supervised learning (SSL) models. However, the generalization of these models to diverse languages and emotional expressions remains a challenge. We propose a large-scale benchmark to evaluate the robustness and adaptability of state-of-the-art SER models in both in-domain and out-of-domain settings. Our benchmark includes a diverse set of multilingual datasets, focusing on less commonly used corpora to assess generalization to new data. We employ logit adjustment to account for varying class distributions and establish a single dataset cluster for systematic evaluation. Surprisingly, we find that the Whisper model, primarily designed for automatic speech recognition, outperforms dedicated SSL models in cross-lingual SER. Our results highlight the need for more robust and generalizable SER models, and our benchmark serves as a valuable resource to drive future research in this direction.

[Arxiv](https://arxiv.org/abs/2408.07851)