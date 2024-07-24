# CHiME-8 DASR 挑战赛聚焦于提升远场自动语音识别和话者分类的通用性与阵列无关性。

发布时间：2024年07月23日

`LLM应用` `会议技术` `语音识别`

> The CHiME-8 DASR Challenge for Generalizable and Array Agnostic Distant Automatic Speech Recognition and Diarization

# 摘要

> 本文推出CHiME-8 DASR挑战赛，延续自CHiME-7 DASR及CHiME-6挑战赛，聚焦于多通道远场语音识别与分段技术，适用于多种设备。挑战旨在推动研究，开发能适应任意说话人数、不同对话环境、会议时长及录音配置的转录方法。相较于C7DASR，本次新增了NOTSOFAR-1办公场景、校正后的Mixer 6开发集、允许使用大型语言模型的新赛道，并设立陪审团奖以激励创新实践。为简化参与流程，我们提供了数据集处理与评分工具包，并推出了基于ESPnet与NeMo的两套基线系统。基线测试显示，NOTSOFAR-1因其高密度说话人与短时长，显著提升了任务难度。

> This paper presents the CHiME-8 DASR challenge which carries on from the previous edition CHiME-7 DASR (C7DASR) and the past CHiME-6 challenge. It focuses on joint multi-channel distant speech recognition (DASR) and diarization with one or more, possibly heterogeneous, devices. The main goal is to spur research towards meeting transcription approaches that can generalize across arbitrary number of speakers, diverse settings (formal vs. informal conversations), meeting duration, wide-variety of acoustic scenarios and different recording configurations. Novelties with respect to C7DASR include: i) the addition of NOTSOFAR-1, an additional office/corporate meeting scenario, ii) a manually corrected Mixer 6 development set, iii) a new track in which we allow the use of large-language models (LLM) iv) a jury award mechanism to encourage participants to explore also more practical and innovative solutions. To lower the entry barrier for participants, we provide a standalone toolkit for downloading and preparing such datasets as well as performing text normalization and scoring their submissions. Furthermore, this year we also provide two baseline systems, one directly inherited from C7DASR and based on ESPnet and another one developed on NeMo and based on NeMo team submission in last year C7DASR. Baseline system results suggest that the addition of the NOTSOFAR-1 scenario significantly increases the task's difficulty due to its high number of speakers and very short duration.

[Arxiv](https://arxiv.org/abs/2407.16447)