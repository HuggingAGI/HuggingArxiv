# [我们提出了一种利用离散语音单元预训练技术打造紧凑型语音翻译模型的方法，该方法能够有效压缩模型体积的同时保持较高的翻译性能。](https://arxiv.org/abs/2402.19333)

> Compact Speech Translation Models via Discrete Speech Units Pretraining

发布时间：2024年02月29日

> 现今，利用SSL预训练以实现强大的语音翻译（ST）性能已成为常态，但其较大的内存开销却限制了在设备端的部署。本文创新地在离散语音单元（DSU）上预训练小型模型，有效汲取SSL模型的优点。我们首先针对滤波器组至DSU和DSU至翻译数据，分别预训练编码器-解码器模型，随后取其编码器和解码器初始化一个新模型，并在少量语音翻译数据上进行微调。最终模型通过DSU预训练提炼SSL模型的知识，体积更为精巧。这种方法相较于直接将DSU作为模型输入，不仅拥有更简洁的推理过程和对DSU分词稳健性等优点，而且无需依赖转录文本，尤其适应于低资源环境。在CoVoST-2 X-En数据集上的评测显示，即使模型大小仅为原先一半，我们的方法仍能比直接微调SSL模型的ST系统高出0.5 BLEU以上，且性能堪比ASR预训练。

> Using Self-Supervised Learning (SSL) as model initialization is now common to obtain strong results in Speech Translation (ST). However, they also impose a large memory footprint, hindering on-device deployment. In this paper, we leverage the SSL models by pretraining smaller models on their Discrete Speech Units (DSU). We pretrain encoder-decoder models on 1) Filterbank-to-DSU and 2) DSU-to-Translation data, and take the encoder from 1) and the decoder from 2) to initialise a new model, finetuning this on limited speech-translation data. The final model becomes compact by using the DSU pretraining to distil the knowledge of the SSL model. Our method has several benefits over using DSU as model inputs, such as shorter inference pipeline and robustness over (DSU) tokenization. In contrast to ASR pretraining, it does not require transcripts, making it applicable to low-resource settings. Evaluation on CoVoST-2 X-En shows that our method is >$0.5$ BLEU better than a ST model that directly finetune the SSL model, given only half the model size, and on a par with ASR pretraining.

`Agent`