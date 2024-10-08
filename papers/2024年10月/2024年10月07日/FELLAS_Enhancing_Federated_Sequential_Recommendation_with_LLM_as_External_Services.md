# FELLAS：借助 LLM 作为外部服务，提升联邦序列推荐的性能

发布时间：2024年10月07日

`LLM应用` `推荐系统` `隐私保护`

> FELLAS: Enhancing Federated Sequential Recommendation with LLM as External Services

# 摘要

> 联邦顺序推荐（FedSeqRec）因其保护用户隐私的能力而备受关注，但其性能因模型轻量化需求而受限。近期，大型语言模型（LLMs）在 NLP 领域展示了强大的语言理解能力，许多任务通过 LLMs 服务实现了卓越性能。受此启发，我们提出了 FELLAS 框架，利用 LLMs 增强 FedSeqRec。FELLAS 通过 LLM 服务器提供项目级和序列级表示辅助，丰富项目嵌入并保护隐私。实验证明，FELLAS 不仅有效，还能保护隐私。

> Federated sequential recommendation (FedSeqRec) has gained growing attention due to its ability to protect user privacy. Unfortunately, the performance of FedSeqRec is still unsatisfactory because the models used in FedSeqRec have to be lightweight to accommodate communication bandwidth and clients' on-device computational resource constraints. Recently, large language models (LLMs) have exhibited strong transferable and generalized language understanding abilities and therefore, in the NLP area, many downstream tasks now utilize LLMs as a service to achieve superior performance without constructing complex models. Inspired by this successful practice, we propose a generic FedSeqRec framework, FELLAS, which aims to enhance FedSeqRec by utilizing LLMs as an external service. Specifically, FELLAS employs an LLM server to provide both item-level and sequence-level representation assistance. The item-level representation service is queried by the central server to enrich the original ID-based item embedding with textual information, while the sequence-level representation service is accessed by each client. However, invoking the sequence-level representation service requires clients to send sequences to the external LLM server. To safeguard privacy, we implement dx-privacy satisfied sequence perturbation, which protects clients' sensitive data with guarantees. Additionally, a contrastive learning-based method is designed to transfer knowledge from the noisy sequence representation to clients' sequential recommendation models. Furthermore, to empirically validate the privacy protection capability of FELLAS, we propose two interacted item inference attacks. Extensive experiments conducted on three datasets with two widely used sequential recommendation models demonstrate the effectiveness and privacy-preserving capability of FELLAS.

[Arxiv](https://arxiv.org/abs/2410.04927)