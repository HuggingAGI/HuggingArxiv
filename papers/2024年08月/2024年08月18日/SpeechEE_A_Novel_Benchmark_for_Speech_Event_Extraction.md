# SpeechEE：引领语音事件提取的新基准

发布时间：2024年08月18日

`LLM应用` `语音识别` `信息抽取`

> SpeechEE: A Novel Benchmark for Speech Event Extraction

# 摘要

> 事件抽取（EE）是信息抽取领域的关键方向，对构建结构化知识库至关重要。尽管文本EE研究已十分充分，但许多实际应用仍需从语音等非文本来源直接获取信息。本文首创SpeechEE，旨在从音频中提取事件信息。为此，我们构建了大规模高质量语音数据集，涵盖多样场景与语言。基于此，我们设计了端到端的SpeechEE系统，创新性地引入了Shrinking Unit模块与检索辅助解码机制，实验证明其高效性。作为该领域先驱，我们亦展望了未来研究方向，相关资源已公开共享。

> Event extraction (EE) is a critical direction in the field of information extraction, laying an important foundation for the construction of structured knowledge bases. EE from text has received ample research and attention for years, yet there can be numerous real-world applications that require direct information acquisition from speech signals, online meeting minutes, interview summaries, press releases, etc. While EE from speech has remained under-explored, this paper fills the gap by pioneering a SpeechEE, defined as detecting the event predicates and arguments from a given audio speech. To benchmark the SpeechEE task, we first construct a large-scale high-quality dataset. Based on textual EE datasets under the sentence, document, and dialogue scenarios, we convert texts into speeches through both manual real-person narration and automatic synthesis, empowering the data with diverse scenarios, languages, domains, ambiences, and speaker styles. Further, to effectively address the key challenges in the task, we tailor an E2E SpeechEE system based on the encoder-decoder architecture, where a novel Shrinking Unit module and a retrieval-aided decoding mechanism are devised. Extensive experimental results on all SpeechEE subsets demonstrate the efficacy of the proposed model, offering a strong baseline for the task. At last, being the first work on this topic, we shed light on key directions for future research. Our codes and the benchmark datasets are open at https://SpeechEE.github.io/

[Arxiv](https://arxiv.org/abs/2408.09462)