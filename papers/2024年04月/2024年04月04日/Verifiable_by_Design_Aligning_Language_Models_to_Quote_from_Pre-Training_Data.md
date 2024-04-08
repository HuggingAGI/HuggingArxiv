# 设计之初即验证：确保语言模型能够引用预训练数据

发布时间：2024年04月04日

`LLM应用` `引用增强` `可信度提升`

> Verifiable by Design: Aligning Language Models to Quote from Pre-Training Data

# 摘要

> 人类要信任大型语言模型（LLMs）流畅的文本生成，模型必须能以可信的外部资料为依据，核实其准确性。近期研究尝试通过引用检索文档或事后追溯来源来提升可验证性，但这些引用容易出错，反而增加了核实的难度。为此，我们采取了一种新的哲学方法来提升可验证性：通过开发预训练时能逐字引用可信资料的模型，简化验证流程。我们提出了一种名为 Quote-Tuning 的方法，证明了让LLMs利用记忆信息并引用预训练数据的可行性。Quote-Tuning 利用高效的成员推断工具，在大型语料库中量化引用，并以此构建一个无需人工注释的引用偏好合成数据集。然后，通过偏好优化算法使目标模型学会引用。实验结果显示，Quote-Tuning 使得LLM生成内容中逐字引用高质量预训练文档的比例，从55%激增至130%，同时保持了回应的质量。更多实验也显示，Quote-Tuning 能将引用能力扩展到非领域数据，适用于多种任务，并为提升内容的真实性带来额外益处。Quote-Tuning 不仅是一种轻松提升引用量的策略，也为通过增强可验证性来提高LLM的可信度开辟了新路径。

> For humans to trust the fluent generations of large language models (LLMs), they must be able to verify their correctness against trusted, external sources. Recent efforts aim to increase verifiability through citations of retrieved documents or post-hoc provenance. However, such citations are prone to mistakes that further complicate their verifiability. To address these limitations, we tackle the verifiability goal with a different philosophy: we trivialize the verification process by developing models that quote verbatim statements from trusted sources in pre-training data. We propose Quote-Tuning, which demonstrates the feasibility of aligning LLMs to leverage memorized information and quote from pre-training data. Quote-Tuning quantifies quoting against large corpora with efficient membership inference tools, and uses the amount of quotes as an implicit reward signal to construct a synthetic preference dataset for quoting, without any human annotation. Next, the target model is aligned to quote using preference optimization algorithms. Experimental results show that Quote-Tuning significantly increases the percentage of LLM generation quoted verbatim from high-quality pre-training documents by 55% to 130% relative to untuned models while maintaining response quality. Further experiments demonstrate that Quote-Tuning generalizes quoting to out-of-domain data, is applicable in different tasks, and provides additional benefits to truthfulness. Quote-Tuning not only serves as a hassle-free method to increase quoting but also opens up avenues for improving LLM trustworthiness through better verifiability.

[Arxiv](https://arxiv.org/abs/2404.03862)